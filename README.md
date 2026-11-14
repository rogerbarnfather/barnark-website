# Barnark website

Part of [Barn](https://rogerbarnfather.github.io/barn-website/).

Live at <https://rogerbarnfather.github.io/barnark-website/>.

The website for [Barnark](https://packagist.org/packages/rmb32/barnark): an introduction, the
philosophy, a quick start and the documentation. Static HTML, no build step; open `index.html` in a
browser. Links between pages are relative, because GitHub Pages serves a project site from a subpath.

- `assets/base/`: the shared Barn website stylesheet. An identical copy of the main site's, checked by
  `bin/ci-all` in the suite folder. Don't edit it here.
- `assets/site.css`: Barnark's own components.
- `assets/screens/`: real captures of the tool, 2× resolution, from a disposable barn with made-up
  hotel data.
- `docs/style-guide.md`: this site's style guide.

Pages: `index.html` (introduction), `philosophy.html`, `quick-start.html`, and `docs/` (overview,
templates, choose, grow, check, yours, history, gui, cli, php, install, data, glossary,
troubleshooting). Every command shown was run for real in a disposable barn with the released
packages, and its output pasted in with paths shortened by "…". Retake them when a command's output
changes.

## Captures retaken 2026-11-14

Real Chrome captures at 1280 CSS pixels and 2× resolution, in light and dark themes, from
a disposable hotel barn using published Barnark core 0.3.0 and GUI 0.2.10. The local barn path
is hidden, following the main site's capture convention; tool content is unchanged.

- `ark-browse`: Hotel’s Tree at `/src`, with three contexts, Booking and layer tags.
- `ark-scaffolds`: the three sidebar groups, My Hotel’s shipped origin and tagged scaffold.
- `ark-template`: Hotel’s Scaffold, its My Hotel origin, meanings and member types.
- `ark-history`: five revisions and the current scaffold.
- `ark-check`: a conforming ark.
- `ark-check-unexpected`: an unexpected `/src/Scratch` and Add to scaffold.
- `ark-file-rules`: `notes.txt` violates Domain’s `*.php` / `*.ts` rule.

Each `-dark` companion is selected by the page’s theme; existing published filenames stay stable.
Seed and capture scripts are retained in `/private/tmp/barnark-stage4-scratch/`.
The main Barn site keeps the same `ark-browse` pair for existing README embed URLs.
