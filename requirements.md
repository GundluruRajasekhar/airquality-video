# Requirements: Urban Air Quality Assistant Video Demo

## 1. Purpose
A narrated, self-running demo page that explains the Urban Air Quality Assistant (description, features, live example, roles and responsibilities) so judges and management can understand the project in about 2 minutes without installing anything.

## 2. Functional Requirements
| ID | Requirement | Priority |
|----|-------------|----------|
| FR-1 | **Start** button begins the demo from scene 1 | Must |
| FR-2 | **Stop** button immediately halts narration and animation and resets to the welcome screen | Must |
| FR-3 | Start is disabled while playing; Stop is disabled when idle | Must |
| FR-4 | 8 scenes advance automatically: Intro, Problem, Description, Features, Live Demo, Roles and Responsibilities, Four Files, Thank You | Must |
| FR-5 | Voice narration via the browser Speech Synthesis API, with a checkbox to turn it off | Must |
| FR-6 | Live captions show the narration text for every scene | Must |
| FR-7 | Progress bar, scene dots, scene counter, and elapsed timer | Should |
| FR-8 | Animated mini demo types AQI 135 and shows the category, gauge, and advice | Should |
| FR-9 | Full script is readable in an expandable section for voice-over recording | Should |
| FR-10 | If speech is unavailable, scenes advance on a timer using the caption text | Must |

## 3. Roles and Responsibilities Shown in the Demo
| Role | Responsibility |
|------|----------------|
| Product Owner | Defines the problem, users, and acceptance criteria |
| Full Stack Developer | Builds logic, validation, history, and deployment |
| UI/UX and Accessibility Lead | Layout, contrast, focus order, screen reader support |
| QA Tester | Runs the 15-point test checklist |
| Security and Privacy Officer | Safe input handling; no data leaves the device |
| Documentation and DevOps | README, GitHub repository, GitHub Pages hosting |

## 4. Non-Functional Requirements
| Area | Requirement |
|------|-------------|
| Accessibility | Skip link, labelled controls, `role="status"` and `aria-live` captions, visible focus, captions for all audio, reduced-motion support |
| Responsiveness | Works from 320px to desktop |
| Performance | Single file, no external requests or libraries |
| Security | All text rendered with `textContent`; no `innerHTML`; no third-party scripts |
| Reliability | No stale timers or voices after Stop (token-based cancellation); safety timeout if speech never ends |
| Compatibility | Chrome, Edge, Safari, Firefox; light and dark mode |

## 5. Acceptance Criteria
1. Clicking Start plays all 8 scenes in order with captions and (if enabled) voice.
2. Clicking Stop at any moment silences audio, stops the timer, and shows the welcome screen.
3. Start can be pressed again after Stop or after the demo finishes.
4. Unchecking "Voice narration" still plays the full demo using timed captions.
5. Page works by double-clicking `index.html` and on GitHub Pages; no console errors.

## 6. Out of Scope
Recorded video files, background music, and multi-language narration (future).
