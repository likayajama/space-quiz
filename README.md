# Copilot coding guidance

## Project structure

- Public project URL: https://github.com/likayajama/space-quiz
- Local quiz file URL: file:///Users/jama/Documents/Space%20Quiz/index.html
- This is a dependency-free static web app. The quiz markup, styles, question data, and behavior are all in `index.html`.
- There is no package manager manifest, build system, or configured test or lint command. Keep changes in the existing single-file structure unless the task calls for a broader change.

## Implementation conventions

- Use semantic HTML and preserve the existing accessible interaction patterns, including button controls, status announcements, visible keyboard focus, and reduced-motion support.
- Keep styling in the document's `<style>` block. Reuse the existing CSS custom properties and light/dark color-scheme approach.
- Keep quiz content in the `questions` array and interaction logic in the existing vanilla JavaScript; do not add frameworks or dependencies for routine changes.
- Use the existing naming and formatting conventions: descriptive kebab-case CSS classes, `const` by default, and template literals for interpolated strings.

## Running and checking

- Open `index.html` directly in a browser to run the app; no server or installation is required.
- Since no automated checks are configured, manually verify relevant quiz flows and responsive/accessibility behavior when changing the app.
