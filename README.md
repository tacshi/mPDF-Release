<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/mPDF-icon-dark.svg">
  <img src="assets/mPDF-icon.svg" width="144" height="144" alt="mPDF logo">
</picture>

# mPDF

**A fast, native PDF reader and editor for macOS.**

Read, annotate, edit text and images, organize pages, fill and sign forms —
in a clean, distraction-free interface built for the Mac.

[![Latest release](https://img.shields.io/github/v/release/tacshi/mPDF-Release?label=release)](https://github.com/tacshi/mPDF-Release/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/tacshi/mPDF-Release/total)](https://github.com/tacshi/mPDF-Release/releases)

</div>

## Install

1. Download the DMG for your Mac from the
   [latest release](https://github.com/tacshi/mPDF-Release/releases/latest):

   | File | For |
   | --- | --- |
   | `mPDF-<version>-arm64.dmg` | Apple Silicon Macs (M-series) |
   | `mPDF-<version>-amd64.dmg` | Intel Macs |
   | `mPDF-<version>-universal.dmg` | Either (larger download) |

   Not sure which Mac you have? Apple menu → **About This Mac**: a "Chip"
   line means Apple Silicon, a "Processor" line means Intel.
2. Open it and drag **mPDF** into **Applications**.
3. Launch mPDF from Applications.

**Requirements:** macOS 13 Ventura or later.

Every build is signed and notarized by Apple. mPDF checks for newer versions
automatically (you can turn this off in Settings).

## Highlights

- **Reader-first design** — immersive reading with auto-hiding chrome, tabs
  that come back where you left off, thumbnails, bookmarks, full-text search,
  and normal, sepia or night page appearance
- **True content editing** — edit existing text and images in place, find and
  replace text
- **Annotations** — highlights, underlines, strike-outs, notes, free text,
  pen, shapes and arrows, with full undo and redo
- **Page organizer** — reorder, rotate, duplicate, insert (blank pages,
  other PDFs, images, the clipboard), replace, extract, and split by page
  count, size or bookmarks
- **Forms and signatures** — fill forms, sign with a drawn signature or a
  certificate, validate digital signatures, and reuse your own stamps
- **Privacy tools** — find & redact, remove hidden text, strip web links,
  add or remove password protection
- **Housekeeping** — reduce file size, attachments and links panels, print
- **Publications** — import Adobe Digital Editions (ACSM) and LCP
  publications
- **Command line** — install the `mpdf` tool from the **Tools** menu to
  split, rotate, compress, fill forms, encrypt and verify signatures from
  Terminal (`mpdf help` lists every command)

## Releases and previews

Regular releases (tagged `v1.2.3`) don't expire.

Preview builds (tagged `preview-…`) try out upcoming changes early and are
valid for **45 days** from their release date; the exact date is shown in
each preview's notes. When a preview reaches the end of its window it
switches to **read-only mode**:

- ✅ Reading, searching, and exporting keep working
- ✅ **Save As** always works — your changes are never locked in
- ⛔ Editing, annotating, organizing pages, and in-place saving are paused

Install a newer release or preview to pick up right where you left off.

## Feedback

Found a bug or have a suggestion? Please
[open an issue](https://github.com/tacshi/mPDF-Release/issues).

When reporting a bug, it helps to include:

- The mPDF version (mPDF → About mPDF, or the DMG file name)
- Your macOS version, and whether your Mac is Apple Silicon or Intel
- Steps to reproduce, and a sample PDF if the issue is file-specific
  (only share files you're comfortable making public)

## Roadmap

After 1.0, mPDF will be a paid app — preview users will have a smooth
upgrade path.

---

<div align="center">
<sub>© 2026 NovaOtter. All builds are signed and notarized for macOS.</sub>
</div>
