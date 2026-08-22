<div align="center">

[![LAZY-LOL](https://img.shields.io/badge/LAZY--LOL-Methodology-8B5CF6?style=for-the-badge&logo=book&logoColor=white)](https://github.com/gmoralesm-dev/lazy-lol-book)
[![Format](https://img.shields.io/badge/format-LaTeX%20%E2%86%92%20PDF-008080?style=for-the-badge&logo=latex&logoColor=white)](LAZYyLOL.tex)
[![Status](https://img.shields.io/badge/status-1st%20Edition-FF6F00?style=for-the-badge)]()
[![License](https://img.shields.io/badge/license-Custom-green?style=for-the-badge)](LICENSE)
[![Stars](https://img.shields.io/github/stars/gmoralesm-dev/lazy-lol-book?style=for-the-badge&color=yellow)](https://github.com/gmoralesm-dev/lazy-lol-book/stargazers)

</div>

# LAZY-LOL 📖 — Arquitectura Metodológica

> **LAZY-LOL**: the open methodology for structuring software projects —
> Lazy scaffolding, then Layered, Observable, Loosely-coupled builds.
> This repository holds the book's LaTeX source, figures, and build files.

## Building the book

```bash
pdflatex LAZYyLOL.tex
pdflatex LAZYyLOL.tex   # run twice for the table of contents
```

Or with latexmk:

```bash
latexmk -pdf LAZYyLOL.tex
```

Output: `LAZYyLOL.pdf`

## Repository layout

| Path | Contents |
|---|---|
| `LAZYyLOL.tex` | main book source |
| `imagenes/` | figures |
| `about/` | front matter |
| `LICENSE` | usage terms for the book's content |

## Related projects

LAZY-LOL is the methodology behind [Ollagent](https://github.com/gmoralesm-dev/ollagent)
🦙 — a local terminal coding agent built following this book.

## License

Copyright (c) 2026 Gabriel Andrés Morales Mago. See [LICENSE](LICENSE) for
the usage terms (the repository mixes code and book content, each with its
own conditions).
