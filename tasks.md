# Tasks: Urban Air Quality Assistant Video Demo

Legend: ✅ done · ⬜ to do

## Phase 1: Planning
- ✅ T1. Define demo goal: explain description, features, and roles in about 2 minutes
- ✅ T2. Write the 8-scene script (see `readme.md`)
- ✅ T3. List roles and responsibilities to present

## Phase 2: Build (`index.html`)
- ✅ T4. Start and Stop buttons with correct enabled/disabled states
- ✅ T5. Scene engine that advances automatically
- ✅ T6. Voice narration via Speech Synthesis with on/off checkbox
- ✅ T7. Timed fallback when speech is unavailable
- ✅ T8. Live captions, progress bar, scene dots, and elapsed timer
- ✅ T9. Animated mini demo (types AQI 135, shows category, gauge, and tips)
- ✅ T10. Expandable full script for voice-over recording
- ✅ T11. Token-based cancellation so Stop leaves no stale audio or timers

## Phase 3: Test Checklist
| # | Action | Expected |
|---|--------|----------|
| 1 | Open page | Welcome screen; Stop disabled |
| 2 | Click Start | Scene 1 plays; Start disabled, Stop enabled; timer runs |
| 3 | Let it run | All 8 scenes play in order, then "Demo finished" |
| 4 | Click Stop mid-scene | Voice stops at once, timer stops, welcome screen returns |
| 5 | Click Start again after Stop | Plays from scene 1 with no overlapping voices |
| 6 | Untick Voice narration, Start | Full demo runs silently on timed captions |
| 7 | Keyboard only (Tab, Enter) | Both buttons reachable and operable, focus visible |
| 8 | Phone width (320px) | No horizontal page scroll |
| 9 | Dark mode | Text and buttons remain readable |
| 10 | Scene 5 | Types 1, 3, 5, shows Unhealthy for Sensitive Groups and 3 tips |

## Phase 4: Release and Recording
- ⬜ T12. Upload the four files to a public GitHub repository
- ⬜ T13. Enable GitHub Pages and open the live link
- ⬜ T14. Run the test checklist above
- ⬜ T15. Screen-record the demo (Start to Thank You scene, about 2 minutes)
- ⬜ T16. Upload the video and add its link to the submission
- ⬜ T17. Share the live link and video link with Hack2skill

## Phase 5: Future Enhancements
- ⬜ Telugu and Hindi narration
- ⬜ Pause and resume button
- ⬜ Background music toggle
