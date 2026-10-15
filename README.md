# saudstack.github.io

A plain static site: no build step, no dependencies.

- `index.html` – home page (bio, project list, links)
- `style.css` – all styling, with automatic dark mode
- `projects/<name>/index.html` – one folder per project

To add a project: copy `projects/this-site/`, rename the folder, edit the
text, and add an entry to the `projects` list in `index.html` (next ID: P02).

Push to the default branch and GitHub Pages serves it.
