# Barnark website style guide

**This guide extends the [Barn website style guide](../../../../website/docs/style-guide.md)**
(`website/docs/style-guide.md` in the suite folder), which extends the Barn suite base style guide. Both
win for anything they state. This guide adds only Barnark's vocabulary, colour and exceptions.

## 1. Colour

Barnark is orange. Every page has `<body data-brand="ark">`, and components read `--brand`,
`--brand-ink`, `--brand-text`, `--brand-bright` and `--brand-tint`. No hex value appears in a page or in
`assets/site.css`; the tokens come from `assets/base/tokens.css`.

## 2. Vocabulary

The site uses Barnark's own words, the same ones as its browser app and command line:

- **Template** for every tree, the project's own included. Never "schema". "Bound" and "unbound" say
  which template is which: the **bound** template follows the project's one folder; **unbound**
  templates are the project's other copies.
- **Shipped template** for a catalogue entry, which is read-only. **Clone** copies a template as the
  project's template and makes its folder; **copy** makes an unbound template and no folder.
- A template's folders are **fixed folders**, **collections**, **members** and **member types**. A member
  is added to a collection, never "filled". The command line calls a member type a **slot**; the site
  says so once and uses *member type* elsewhere.
- **Revision**, **meaning**, **tag**, **check**, **missing** and **unexpected** keep one meaning
  across the site and are defined once in the glossary.
- **Area of business** is never shortened, if it comes up at all.
- Say what a template says: folders only. Never write that Barnark checks, creates or manages files,
  apart from the `.gitkeep` it adds so that git keeps an empty folder.
- Examples use a hotel (contexts such as Reservation and FrontDesk, an aggregate Booking), never Jupiter
  or Pleasant Stay.

## 3. Page set

`index.html` (introduction), `philosophy.html`, `quick-start.html`, and `docs/` with a page per topic.
The header navigation is the same on every page: Philosophy, Quick start, Documentation, Barn.

## 4. Exceptions

- The site header's wordmark is Barnark's own mark in an orange tile, not the Barn barn mark. Reason:
  each tool site reads as if the other tools did not exist (website guide §1). The `.tool-mark` rule is
  in `assets/site.css`.
- The header links to the main Barn site as "Barn", in place of the tool tabs of the main site.
- The introduction shows no commands except one illustration of a command and its folders, which the
  quick start runs for real; nothing on it needs verifying against a release.
- `assets/site.css` adds `.tree`, a folder-tree illustration for panels, which the base stylesheet does
  not have.
