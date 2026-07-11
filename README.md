# sanskrit-fonts

_Created: 19-06-2026 · Last updated: 11-07-2026_

Hosting repository for the web font used to render Devanagari Sanskrit text in
the [Cologne Digital Sanskrit Lexicon (CDSL)](https://www.sanskrit-lexicon.uni-koeln.de/)
web interface and related tools.

The repository's default branch is **`gh-pages`**, so the font is published
directly via GitHub Pages at
[sanskrit-lexicon.github.io/sanskrit-fonts](https://sanskrit-lexicon.github.io/sanskrit-fonts/).

## Contents

| File | Purpose |
|---|---|
| [`siddhanta.ttf`](https://github.com/sanskrit-lexicon/sanskrit-fonts/blob/gh-pages/siddhanta.ttf) | Siddhanta Devanagari TrueType font, for Unicode Devanagari glyph shaping |
| [`LICENSE`](https://github.com/sanskrit-lexicon/sanskrit-fonts/blob/gh-pages/LICENSE) | CC BY-SA 4.0 — covers this repository's own config, docs, and packaging **only** |
| [`NOTICE`](https://github.com/sanskrit-lexicon/sanskrit-fonts/blob/gh-pages/NOTICE) | Third-party notice: the font is not relicensed by this repository |

## The font

**Siddhanta** is a Devanagari Unicode font designed by **Mihail Bayaryn**
(Міхаіл Баярын). The font's own embedded metadata records:

- Copyright © 2011 Mihail Bayaryn
- License: [Creative Commons Attribution-NonCommercial-NoDerivs 3.0 (CC BY-NC-ND 3.0)](https://creativecommons.org/licenses/by-nc-nd/3.0/)

## Licensing — two separate licenses

This repository carries **two distinct licenses**, and they must not be conflated
(see [`NOTICE`](https://github.com/sanskrit-lexicon/sanskrit-fonts/blob/gh-pages/NOTICE)):

- **Repository files** (configuration, documentation, packaging) are under
  [CC BY-SA 4.0](https://github.com/sanskrit-lexicon/sanskrit-fonts/blob/gh-pages/LICENSE).
- **`siddhanta.ttf`** is a **third-party work** distributed under the font
  author's own terms (CC BY-NC-ND 3.0, per the font's embedded license field).
  It is **not** relicensed by this repository and is **not** covered by the
  repository LICENSE. Refer to the font author's terms for permitted use.

## Usage

CDSL web displays render Devanagari using the Siddhanta font under the CSS
`font-family: siddhanta_deva` (see, e.g.,
[`csl-apidev/css/basic.css`](https://github.com/sanskrit-lexicon/csl-apidev/blob/master/css/basic.css),
which keeps its own local copy of the font file). Load the font from the
GitHub Pages URL above, or vendor a local copy, honoring the font's
CC BY-NC-ND 3.0 terms.

## Issue conventions

This is a build-meta / asset-hosting repository and follows the
[Cologne tooling-repo taxonomy](https://github.com/sanskrit-lexicon/csl-observatory/blob/main/runbook/cologne-tooling-runbook.md)
for labels, severities, and milestones.

---

_Dr. Mārcis Gasūns_
