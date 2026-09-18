# Subash S — personal academic website

Static single-page site (`index.html`), served with GitHub Pages. No build step.

## Editing content
All lists live as plain JavaScript arrays near the bottom of `index.html`:

| What | Array | Format |
|---|---|---|
| Journal articles | `P` | `[year, "authors", "title", "journal", "vol(issue), pages", "url", "optional note"]` |
| Book chapters | `C` | `["year", "authors", "title", "in … (eds.) …"]` |
| Projects | `PR` | `["years", "PI / Co-PI", "title", "sponsor"]` |
| Graduated PhDs | `AL` | `["year", "name", "thesis", "current position"]` |
| Op-eds | `OP` | `["title", "outlet", "date", "co-authors"]` |

Add a new paper by inserting a line at the top of `P`. Theme tags and the counts on the About section update automatically.
Update the headline numbers (articles, chapters, PhDs) in the `.figures` block by hand.
