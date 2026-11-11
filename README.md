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
