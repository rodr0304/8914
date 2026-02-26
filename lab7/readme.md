## Lab 7 – Keyboard Accessibility & Accessible Web Forms

### Q1 – Keyboard accessibility
- Fixed broken tab order by removing incorrect `tabindex` usage
- Kept visible focus indicators (did not suppress outlines)
- Added a “Skip to main content” link for keyboard users
- Replaced placeholder links (`href="#"`) with real in-page targets
- Removed focus-triggered behavior (new window opens only on click)

### Q2/Q3 – Accessible web form + validation
- Added correct label/input associations (`for` / `id`)
- Grouped radio buttons using `fieldset` and `legend`
- Implemented an accessible error summary with focus management
- Added clickable error links that move focus to the related field
- Added inline error messages with `aria-describedby` and `aria-invalid`
- Replaced `alert()` with an on-page success message
- Implemented URL parameter prefill using `URLSearchParams` (no jQuery dependency)
