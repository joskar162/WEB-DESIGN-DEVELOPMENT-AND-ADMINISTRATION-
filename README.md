## WEB-DESIGN-DEVELOPMENT-AND-ADMINISTRATION-

This repository contains a small set of instructional HTML files used for learning basic
HTML structure, anchors, hyperlinks and simple formatting. The files live in the `HTML BASICS/` and 'HTML TABLES/' folder.

This README was created after reviewing the files (no source files were modified while preparing this README).

## What I looked at

- `HTML BASICS/index.html` — Main page. Contains headings, paragraphs, internal section anchors named
	`section_two` and `section_three`, and top-of-page links to those anchors. Also contains external link(s).
- `HTML BASICS/filetwo.html` — A second page. Contains internal anchors `section_two` and `section_three` so
	cross-file links like `filetwo.html#section_two` and `filetwo.html#section_three` can jump to those sections.
- `HTML BASICS/filethree.html` — Another simple page with navigation links back to `index.html` and others.
- `HTML BASICS/filefour.html` — Simple page with basic links (similar to `filethree.html`).
- `HTML BASICS/format.html` — Demonstrates text formatting, lists (ordered/unordered), `<pre>`, `<hr>`, and definition lists.
- `HTML BASICS/start.html` — A minimal first-page example with a simple personal intro.

Note: the HTML files are basic teaching examples. There are a few inconsistencies in markup (closing tags and casing), which is normal in beginner exercises. I did not change any of the HTML while writing this README.

## File list (one-line purpose)

- `HTML BASICS/index.html` — Main example page: content, internal anchors, and top navigation links.
- `HTML BASICS/filetwo.html` — Page with matching anchors to demonstrate linking from `index.html`.
- `HTML BASICS/filethree.html` — Additional page with navigation back to `index.html`.
- `HTML BASICS/filefour.html` — Extra example page with navigation links.
- `HTML BASICS/format.html` — Formatting examples: paragraphs, breaks, lists, and preformatted text.
- `HTML BASICS/start.html` — A tiny personal intro page used as a starting example.

## How to test locally (quick steps)

1. Open your file manager and navigate to the project folder, then into `HTML BASICS`.
2. Double-click `index.html` (or right-click -> Open with -> your web browser). The browser will load the page using a `file://` URL.
3. At the top of the page you should see links:
	 - "Section Two" — jumps to the `section_two` anchor inside `index.html`.
	 - "Section Three" — jumps to the `section_three` anchor inside `index.html`.
	 - "File Two: Section Two" — opens `filetwo.html` and jumps to its `section_two` anchor.
	 - "File Two: Section Three" — opens `filetwo.html` and jumps to its `section_three` anchor.
4. Click each link and confirm the browser moves to the correct section (internal jumps) or opens the other file and scrolls to the named anchor (cross-file jumps).

Tips: If a cross-file anchor doesn't work, make sure both files are in the same directory and that the anchor names match exactly (case sensitive in some setups). Also ensure the browser is loading the local file from the correct folder.

## Notes & observations

- The HTML files use legacy attributes (for example `BGCOLOR`, `TEXT`, `LINK`, `VLINK`, `ALINK`) on the `<BODY>` tag. These still work in browsers but are deprecated in modern HTML; CSS is the recommended approach for styling.
- Some pages include extra or inconsistent tags and casing (for example `HTML` / `HEAD` casing, duplicate `BODY` tags in one file). These are common in beginner exercises but browsers are generally tolerant. If you want, I can clean and modernize the markup (convert inline attributes to CSS, fix tag nesting), but I did not change any code.

## Next steps I can help with

- Clean up and modernize the HTML (semantic tags, proper closing tags, convert color attributes to CSS).
- Add a simple local development instruction (e.g., run a tiny static server with Python: `python -m http.server`) if you want to test relative links under `http://localhost`.
- Fix any broken links or incorrect anchor names if you point them out.

If you'd like, I can now (A) keep the files untouched and just commit this README, or (B) propose and implement code cleanups as a follow-up PR — tell me which you prefer.

---
Generated: (review of files performed). If you want me to commit this README to the repository or to adjust the wording, say "Please write README" or give edits.

