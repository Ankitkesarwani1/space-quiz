# Project rules

- Keep the app as a single standalone HTML file unless the task explicitly requires a multi-file setup.
- Do not add runtime dependencies or a local server for simple demos.
- Prefer semantic HTML, keyboard accessibility, and visible focus states for interactive controls.
- Keep the design polished, centered, and narrow-column with readable sans-serif text.
- Respect both light and dark themes via `prefers-color-scheme`.
- Use subtle animation only for feedback states: correct = green, wrong = red shake, disabled/next state transitions.
- Verify browser behavior with a quick smoke test for keyboard navigation, score updates, answer feedback, and results screen flow.
- Keep changes small and targeted; avoid unrelated refactors.
