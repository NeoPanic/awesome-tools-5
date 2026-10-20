---
type: Tool
title: Glim
description: A free macOS viewer for documents, data, images and source files, with basic text editing.
resource: https://github.com/NeoPanic/Glim
tags: [macos, file-viewer, markdown, open-source]
platforms: [macOS]
license: MIT
sources:
  - id: glim-readme
    resource: https://github.com/NeoPanic/Glim/blob/v0.2.6/README.md
    title: Glim README
  - id: glim-formats
    resource: https://github.com/NeoPanic/Glim/blob/v0.2.6/docs/file-format-support.md
    title: Glim file format support and limitations
  - id: glim-release
    resource: https://github.com/NeoPanic/Glim/releases/tag/v0.2.6
    title: Glim v0.2.6 release and installation notes
  - id: glim-architecture
    resource: https://github.com/NeoPanic/Glim/blob/v0.2.6/docs/architecture.md
    title: Glim architecture and editing workflow
  - id: glim-license
    resource: https://github.com/NeoPanic/Glim/blob/v0.2.6/LICENSE
    title: Glim MIT license
---
# Glim

A free, open-source file viewer for macOS. Markdown, PDFs, images, JSON, CSV and source files share one workspace. The source is MIT-licensed.[^glim-readme][^glim-license]

## Features

- Markdown preview with diagrams and formulas.[^glim-formats]
- JSON trees, CSV tables and read-only SQLite previews.[^glim-formats]
- Basic UTF-8 editing and autosave; document/image previews and diff views remain read-only.[^glim-architecture]

## Platforms and pricing

macOS only, with separate Apple Silicon and Intel downloads. The project describes the app as free and open source.[^glim-readme][^glim-release]

Office and ebook previews have format-specific fidelity limits; they are not full document editors.[^glim-formats]

## Install

Download the matching DMG from the [official releases](https://github.com/NeoPanic/Glim/releases/latest), open it and drag Glim.app into Applications. The packages are ad-hoc signed and not Apple-notarized; macOS can require first-launch approval in Privacy & Security.[^glim-release]

A Homebrew lookup for `glim` on 2026-10-21 returned no matching cask. No Homebrew or Windows package command is listed here.

## See also

- [macOS utilities](../concepts/macos-utilities.md)
- [Local machine setup](../concepts/local-machine-setup.md)

[^glim-readme]: [Glim README](https://github.com/NeoPanic/Glim/blob/v0.2.6/README.md)
[^glim-formats]: [Format support and limitations](https://github.com/NeoPanic/Glim/blob/v0.2.6/docs/file-format-support.md)
[^glim-release]: [Glim v0.2.6](https://github.com/NeoPanic/Glim/releases/tag/v0.2.6)
[^glim-license]: [MIT license](https://github.com/NeoPanic/Glim/blob/v0.2.6/LICENSE)
[^glim-architecture]: [Architecture and editing workflow](https://github.com/NeoPanic/Glim/blob/v0.2.6/docs/architecture.md)
