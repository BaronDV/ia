# First Rep Coach

A phone-first gym log and coach for a beginner training 3 days a week with a fat-loss goal.

Live app (private to the owner): https://claude.ai/artifact/U5dH3q4vRHjL5zwKszrTXv

`index.html` is the whole app. It is published as a Claude artifact, which gives it:

- **db**: stores the log (profile, weigh-ins, waist, workouts, daily habits, check-ins). Access rules make it readable and writable by the owner only.
- **sample**: the in-app coach chat and weekly reviews, which can swap exercises, change targets or start an easy week.

Opened outside Claude, it falls back to saving in the browser's local storage.

## The plan it runs

- Full-body sessions A and B, alternating, 3 days a week.
- Phase 1 (weeks 1–4) uses machines only, phase 2 (weeks 5–8) adds dumbbells, phase 3 adds sets.
- Double progression: when every set hits the top of the rep range, the next session suggests more weight.
- Weekly check-in compares 7-day weight averages: two slow weeks (under 0.25 kg/week) lower calories by 150, and losing more than 1 kg/week raises them by 150.
