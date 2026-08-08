# Nivedita Prakash — personal website

A single-page personal site: author of *The Crimson Shift* and *Your Moment Begins Now*,
and a Project & Program Management Leader based in Bengaluru.

**Live:** https://niveditaprakash14-creator.github.io/Website/

## Files

| Path | Purpose |
|------|---------|
| `index.html` | The entire site — HTML, CSS and JS in one file. No build step, no dependencies. |
| `images/` | Book cover art. |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is rather than running Jekyll. |

## Editing

Open `index.html` in any editor and edit the markup directly. To preview, open the file
in a browser — there is nothing to install or compile.

Colours, spacing and fonts are CSS custom properties in the `:root` block at the top of
the file, with matching light and dark values. Changing `--accent` in all four theme
blocks restyles the whole page.

Anything still to be filled in is wrapped in `class="ph"`, which renders with a dashed
underline so it is easy to spot. Once the last one is replaced, delete the `.ph` rule at
the bottom of the stylesheet.

## Not in this repo

The source LinkedIn PDF exports are excluded via `.gitignore`. They contain names,
comments and profile details of third parties, and this repository is public.
