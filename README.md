# Personal website

A list of my talks with abstracts and notes, published with GitHub Pages.

## Adding a talk

1. Copy the PDF of the notes into the `talks/` folder (e.g. `talks/2026-11-harvard.pdf`).
2. In `talks.html`, copy an existing `<article class="talk"> ... </article>` block and paste it at the top of the list.
3. Edit the `id` (in both places), title, venue, date, abstract and PDF link.
4. Commit and push. The live site updates within about a minute.

A direct link to a single talk looks like `https://<username>.github.io/talks.html#<id>`.

The "About me" text is on the home page (`index.html`), inside `<section class="about">`. Add paragraphs as `<p>...</p>`.

## Changing the look (style.css)

Browsers keep a copy of `style.css` for up to 10 minutes. After editing it, change the
version tag on the stylesheet line in both `index.html` and `talks.html` (e.g. `style.css?v=2026-11-14a` → `?v=2026-11-14b`)
so visitors get the new styles right away.
