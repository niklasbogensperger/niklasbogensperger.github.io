---
title: "atlas-preamble"
subtitle: "LaTeX"
weight: 30
date: "2024-05-01T12:00:00+02:00"
image: "gallery/30_atlas-preamble.png"
alt: "atlas-preamble"
github:
    repo: "niklasbogensperger/atlas-preamble"
    showInfo: true
    showButtons: true
draft: false
---


My personal standard LaTeX preamble, written as a modular package. This `.sty` file intended to replace the dozens (sometimes hundreds!) of lines in a neatly configured LaTeX document with just one - it handles all the (my) standard imports and settings so you can concentrate on writing the actual text instead of copy-pasting together preamble code snippets from previous documents.

Available presets include "base", "extra", "experiment", "script", "compsci", "probability", "complete", and "all".

The package and all its included imports, features, and settings can be activated by copying the `.sty` file to your document tree (or making it a shared resource in your preferred LaTeX editor) and placing `\usepackage[options and/or preset]{atlas-preamble}` in your document preamble.
