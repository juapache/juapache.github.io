# Course Layout & Look Standards (based on lesson_intropc.html)

Use these rules when building any new course page so it matches the visual and interaction pattern of lesson_intropc.html.

## Page shell
- Use the same global header nav (Home, About, Research, Teaching, Contact, Data Lab, Blog) and site footer. Include a language toggle if relevant.
- Load the existing `style.css` plus the two Google fonts (Space Grotesk + Source Serif 4) and keep the canonical/alternate meta tags.
- Include a skip link to `#main-content` for accessibility.

## Structure & minimum content
- Each course must have **at least 5 modules/sections**. Render them inside a `.lesson-content` article.
- Add a course header block (`.course-header`) with the home/back button, title, and subtitle/tagline.
- Provide a progress block showing completed sections out of total and a visual bar.
- Add a module navigation bar (`.module-nav`) with one button per module; highlight the active one via `aria-current="true"`.

## Module pattern (per section)
- Wrap each module in a `<section class="module-section" aria-labelledby="mX-title">` with a numbered `<h2>` and a short `.lead` paragraph.
- Include **subsections** as `<details class="concept concept-alt-0|concept-alt-1">` entries. Alternate `concept-alt-0` and `concept-alt-1` to achieve the two-tone backgrounds.
- Provide an **Additional Resources** block (`.resources-block`) in every module: heading + description + placeholders/embeds as needed.
- Include a **Notes** block (`.notes-block`) with a label and `<textarea class="notes">` for autosave.
- Add **navigation controls** at the bottom of each module (`.module-actions module-actions-centered`):
  - Previous button (`data-prev`), Next button (`data-next`), and a primary **Mark section complete** button (`data-complete`).
  - Keep alignment consistent: previous on the left, mark complete centered/left, next on the right.
- For quizzes: use a `.quiz-block` with `<form class="quiz">`, fieldsets, and `.quiz-actions` buttons for check/try again. Store answers in the JS key map.
- Optionally include highlights (`.highlight`) for key takeaways.

## Styling tokens (match lesson_intropc.html)
- Containers: `.course-wrapper` max-width ~1000px; `.lesson-content` max-width ~860px.
- Buttons: use the shared button classes (`.button-primary`, `.button-secondary`, `.button-quiet`, `.button-danger`, `.button-link`) with the existing palette.
- Concept blocks: `concept-alt-0` background `#e8f0f9`, `concept-alt-1` background `#d4e6f1`; both use border colors from lesson_intropc.html.
- Resources, quizzes, and notes use card-style borders (`var(--stroke)`) and rounded corners (`var(--radius)`).
- Keep responsive rules from lesson_intropc.html (module nav collapses to 2 columns at ≤800px; module actions stack).

## Behavior (JS expectations)
- Use the same interaction model as lesson_intropc.html:
  - `showSection()` toggles sections with `hidden` and updates `aria-current` on module nav buttons.
  - Progress is tracked in `localStorage` (set of completed module IDs). Update the progress text and bar width.
  - Notes autosave to `localStorage` with a prefix per lesson (e.g., `lessonX_notes_`).
  - Completion buttons push the module ID into progress and optionally advance to the next section.
  - Provide a reset/restart control to clear progress, notes, and quiz answers.
  - Quizzes: check-answer functions compare against an answer key object; provide a try-again button to reset selections.

## Required elements per course
- Header + subtitle, progress block, module nav, and footer back-to-Teaching link.
- **Minimum five modules**, each with: numbered title, lead, alternating concept blocks (at least two per module), resources block, notes block, navigation buttons, and a complete button.
- At least one quiz in the course (module-specific or final comprehensive).
- Additional Resources section must exist in every module (can start with placeholders but should be present).
- Navigation buttons (prev/next/complete) must be present in every module; Next in the last module can be replaced with a back-to-Teaching link.

## Accessibility & semantics
- Use `aria-labelledby` on modules, `aria-label` on nav/progress where applicable, and `aria-current` on active module buttons.
- Preserve focusable skip link and ensure buttons are keyboard navigable.
- Use semantic headings (h1 for course title, h2 for modules, h3 for subheads inside modules if needed).

## Color & typography parity
- Keep the two-tone subsection backgrounds via `concept-alt-0/1` classes; do not introduce new color schemes without updating tokens in CSS.
- Maintain the same font stack and spacing (padding/margins) as lesson_intropc.html for visual consistency.

## File naming & assets
- Follow existing naming: `lesson_<course>.html` for English; parallel `-es` for Spanish when needed.
- Use the existing assets and style variables; avoid inline styles unless matching current practice (e.g., image sizing/placeholders).
