# Half Marathon Training Plan

A self-contained training tracker for a 13-cycle (52-week) half marathon plan. Just one HTML file — no build step, no dependencies.

## Use

Open `half-marathon-plan.html` in a browser, or host it with GitHub Pages.

- Browse phases and cycles with the tabs and arrow buttons.
- Check off a run once you've done it, then log your actual distance, plus time as separate minutes/seconds boxes (no colon needed — works fine on a phone keypad). Your pace per mile is calculated automatically.
- Your log is saved automatically in the browser via `localStorage`.

## Notes

- Tracking data is stored **per browser/device**. It won't sync between your phone and laptop — each keeps its own log.
- To wipe your logged data, use "reset tracking data" in the footer.
- Everything (paces, schedule, styling) is editable directly in `half-marathon-plan.html` — the training data lives in the `phases` array near the top of the `<script>` section.
