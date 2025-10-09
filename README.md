# HTML Basics Demo

This repository contains small example files that demonstrate basic HTML concepts. The files are self-contained so you can open them in a browser or edit them in a plain text editor (Notepad) to learn how HTML works.

## Files in this folder

- `format.html` — Demonstrates text formatting with paragraphs (`<p>`), line breaks (`<br>`), preformatted text (`<pre>`), headings (`<h1>`, `<h2>`), lists (unordered `<ul>`, ordered `<ol>`, definition `<dl>`), horizontal rules (`<hr>`), and HTML comments.
- `index.html` — Homepage of a multi-page site with links to other pages and sections within documents using anchors (`<a name>` and `<a href="#section">`).
- `filetwo.html` — Second page with sections for linking, demonstrating internal and external page links.
- `filethree.html` — Third linked page.
- `filefour.html` — Fourth linked page.
- `start.html` — Basic HTML document structure with bold (`<b>`) and italic (`<i>`) text.
- `start.txt` — Plain text file for comparison and editing exercises.
- `README.md` — This documentation file.

## What this demonstrates

The examples cover:

- Document structure: `<!doctype html>`, `<html>`, `<head>`, `<body>` and semantic elements like `<header>`, `<main>`, `<article>`, `<aside>`, and `<footer>`.
- Text formatting: headings (`<h1>`–`<h6>`), paragraphs (`<p>`), bold (`<B>` / recommended `<strong>`), and italics (`<I>` / recommended `<em>`), preformatted text (`<pre>`), horizontal rules (`<hr>`).
- Lists: unordered (`<ul>`), ordered (`<ol>`), and definition (`<dl>`, `<dt>`, `<dd>`).
- Links (`<a>`), including to sections within a page (`<a href="#section">`) and between pages (`<a href="page.html#section">`), with anchors (`<a name="section">`).
- Images (`<img>`), figures (`<figure>` / `<figcaption>`), tables (`<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`).
- Forms with labels and inputs (accessible pairing of `<label>` and `<input>`).
- HTML comments (`<!-- -->`).
- A small inline SVG example (used as a data URL image) and a tiny JavaScript example that updates the UI.

## How to open the files

- Double-click any `.html` file (e.g., `format.html`, `index.html`, `start.html`) in File Explorer to open them in your default browser.
- From PowerShell you can run:

```powershell
Start-Process .\format.html
# or
Start-Process .\index.html
# etc.
```

- To edit in Notepad: right-click the file and choose "Open with > Notepad" (or open Notepad first and select File → Open).

## Notes and tips

- The `start.html` file purposely uses uppercase tags `<B>` and `<I>` to match the Notepad exercise you described. In modern HTML it's recommended to use lowercase and semantic tags (`<strong>` instead of `<b>`, and `<em>` instead of `<i>`), since they convey meaning to browsers and assistive technology.
- Save changes and reload the page in your browser to see them take effect. Use DevTools (F12) to inspect elements, view console output, and experiment with styles.

## Next steps (suggestions)

- Replace `<B>` and `<I>` with `<strong>` and `<em>` in `start.html` to practice semantic markup.
- Add more form controls (radio groups, selects, textarea) and validate them with HTML attributes.
- Make `html_basics.html` responsive by adding a few CSS media queries.
- Convert the inline script into a separate `main.js` file and link it from the HTML.

## License

Feel free to copy, modify, and learn from these files for your personal projects or lessons.

---

If you'd like, I can update `start.html` to use modern semantic tags, or create a short step-by-step tutorial file that walks through editing the file in Notepad and reloading it in a browser.