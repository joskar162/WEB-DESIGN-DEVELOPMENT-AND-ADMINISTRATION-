# HTML Basics Demo

This repository contains small example files that demonstrate basic HTML concepts. The files are self-contained so you can open them in a browser or edit them in a plain text editor (Notepad) to learn how HTML works.

## Files in this folder

- `html_basics.html` — A readable demo page showing semantic structure, headings, paragraphs, lists, links, images, tables, a small form, and a tiny JavaScript snippet (dark mode toggle and form handling).
- `start.txt` — A plain text version of a simple example used in the Notepad exercise.
- `start.html` — A minimal HTML file created from `start.txt` that demonstrates using `<B>` and `<I>` tags (bold and italic).

## What this demonstrates

The examples cover:

- Document structure: `<!doctype html>`, `<html>`, `<head>`, `<body>` and semantic elements like `<header>`, `<main>`, `<article>`, `<aside>`, and `<footer>`.
- Text formatting: headings (`<h1>`–`<h6>`), paragraphs (`<p>`), bold (`<B>` / recommended `<strong>`), and italics (`<I>` / recommended `<em>`).
- Lists: unordered (`<ul>`) and ordered (`<ol>`).
- Links (`<a>`), images (`<img>`), and figures (`<figure>` / `<figcaption>`).
- Tables (`<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`).
- Forms with labels and inputs (accessible pairing of `<label>` and `<input>`).
- A small inline SVG example (used as a data URL image) and a tiny JavaScript example that updates the UI.

## How to open the files

- Double-click `html_basics.html` or `start.html` in File Explorer to open them in your default browser.
- From PowerShell you can run:

```powershell
Start-Process .\html_basics.html
# or
Start-Process .\start.html
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