<h3 id="kanata-config" align="center">
  <br>
    <img src="assets/logo.png" alt="logo" width="120">
  <br>
  Kanata Config
  <br>
</h1>

##

<div align="center">
  <p>My personal Kanata configuration for non-QMK/non-ZMK keyboards.</p>
</div>

<p align="center">
  <a href="https://github.com/sjlex/kanata-config/releases/latest"><img alt="Version" src="https://img.shields.io/github/v/release/sjlex/kanata-config?labelColor=black&color=black"></a>&nbsp;
  <a href="https://github.com/sjlex/kanata-config/blob/main/LICENSE"><img alt="GitHub License" src="https://img.shields.io/github/license/sjlex/kanata-config?labelColor=black&color=black"></a>&nbsp;
</p>

![Screenshot](assets/layers/base.png)

## Table of contents

- [Kanata Config](#kanata-config)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
  - [Features](#features)
  - [Layouts](#layouts)
    - [qPhyx](#qPhyx)
  - [Layers](#layers)
    - [Navigation](#navigation)
    - [Mouse](#mouse)
    - [Numbers](#numbers)
    - [Symbol layers](#symbol-layers)
    - [Fn keys](#fn-keys)
    - [Workflow](#workflow)
  - [Getting started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Build Kanata](#build-kanata)
    - [Installation](#installation)
    - [Running](#running)
  - [Inspiration](#inspiration)
  - [License](#license)
  - [Third-Party Assets](#third-party-assets)

## Overview

My personal Kanata configuration for non-QMK/non-ZMK keyboards.

Features the qPhyx base, specialized layers, and an enhanced home row with sticky and hold modes.

## Features

- Home-Row:
  - Home-Row Sticky
  - Home-Row Hold
- Layer Hold
- Mouse Control
- Language Switching
- Tab Navigation
- History Navigation
- Quick Hotkeys: (сopy, paste, cut, save, undo, redo)
- Fast Window Control (minimize, close) with AltSnap integration
- Quick Previous Window Switching
- QWERTY Compatibility
- Game Mode
- ... and more

## Layouts

### qPhyx

- [qPhyx-lat](https://github.com/uqqu/layout)
- [qPhyx-cyr](https://github.com/uqqu/layout)

![](assets/layers/qphyx-typing.png)
![](assets/layers/layouts.png)

## Layers

### Navigation

![](assets/layers/navigation.png)
![](assets/layers/navigation-alt.png)

### Mouse

![](assets/layers/mouse.png)
![](assets/layers/mouse-alt.png)

### Numbers

![](assets/layers/numbers.png)

### Symbol layers

![](assets/layers/quick-math.png)
![](assets/layers/symbols.png)

### Fn keys

![](assets/layers/functions.png)

### Workflow

![](assets/layers/workflow.png)

## Getting started

### Prerequisites

- Kanata v1.9.0 or greater

<h3 id="build-kanata">Build Kanata</h3>

Build Kanata with the required feature flags:

```shell
git clone https://github.com/jtroo/kanata.git
cd kanata
cargo build --release --features win_manifest,gui,cmd,win_sendinput_send_scancodes,win_llhook_read_scancodes
```

<h3 id="installation">Installation</h3>

```shell
git clone https://github.com/sjlex/kanata-config.git
```

<h3 id="running">Running</h3>

Run the configuration with the Kanata GUI:

  - Launch it with the highest privileges and at high priority!

```shell
target\release\kanata.exe --quiet --nodelay --cfg "main.kbd"
```

## Inspiration

- [qPhyx Layout](https://github.com/uqqu/layout)

## License

[MIT License](LICENSE)

## Third-Party Assets

This project may include or reference third-party assets under their own licenses. Any such assets are used in accordance with their licensing terms.

- Inter
  - Source: [Inter](https://fonts.google.com/specimen/Inter)
  - License: [SIL OPEN FONT LICENSE Version 1.1 - 26 February 2007](https://fonts.google.com/specimen/Inter/license)

- Jersey 20
  - Source: [Jersey 20](https://fonts.google.com/specimen/Jersey+20)
  - License: [SIL OPEN FONT LICENSE Version 1.1 - 26 February 2007](https://fonts.google.com/specimen/Jersey+20/license)

- Material Symbols
  - Source:
    - [Material Icons](https://fonts.google.com/icons)
    - [Material Symbols Github](https://github.com/google/material-design-icons)
  - License: [Apache License Version 2.0](https://www.apache.org/licenses/LICENSE-2.0.html)
