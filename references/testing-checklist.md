# Frontend Testing Checklist

Select checks appropriate to the current project. Do not install a new test framework just to tick every box.

## 1. Project-aware checks
- [ ] Read `package.json` and identify the actual package manager and scripts.
- [ ] Check repository instructions before running commands.
- [ ] Review the diff and ensure unrelated user changes are preserved.
- [ ] Run existing lint, typecheck, unit test, and build scripts when available.

## 2. Static site
- [ ] Confirm the intended entry HTML file exists.
- [ ] Check stylesheet and script paths.
- [ ] Check asset path spelling and filename casing.
- [ ] Verify navigation targets and anchor IDs.
- [ ] Check for obvious console errors if a browser is available.

## 3. React application
- [ ] Confirm the app entry point and routing approach.
- [ ] Check for missing keys in mapped lists and invalid component usage.
- [ ] Check state updates and effect dependencies.
- [ ] Verify no secrets are exposed in client code.
- [ ] Run the project's existing build/lint/test commands.

## 4. User-facing behavior
- [ ] Main navigation and mobile menu.
- [ ] Primary and secondary buttons.
- [ ] Forms: validation, success, and error feedback.
- [ ] Tabs, filters, accordions, modals, and search where present.
- [ ] Keyboard operation and visible focus.
- [ ] Images load and have suitable alternative text.
- [ ] Responsive layout at narrow and wide widths.
- [ ] Reduced-motion preference is respected where animation exists.

## 5. Reporting
Report each check as one of:
- **Passed** — the check was actually run and passed.
- **Failed** — the check was run and failed; explain the observed issue.
- **Not run** — unavailable, not configured, or not appropriate; explain briefly.

Never describe a check as passed merely because the code appears correct.
