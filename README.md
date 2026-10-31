# Liner Notes — GitHub Pages version

This package preserves the supplied HTML page and its 39 JavaScript files.

## Structure
- `index.html` — main entry page
- `js/` — 39 JavaScript files used by the page
- `resources/saved_resource.html` — saved local HTML resource referenced by a hidden iframe in the original page

The JavaScript files were renamed from `.js.download` to `.js`, and the references in `index.html` were updated. The JavaScript contents and script loading order were not changed.

## Publish
Upload the contents of this folder to the root of your GitHub repository, then enable GitHub Pages from `main` / `(root)`.

After deployment, open the repository's Pages URL.
