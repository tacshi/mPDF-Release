<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/mPDF-icon-dark.svg">
  <img src="assets/mPDF-icon.svg" width="144" height="144" alt="mPDF logo">
</picture>

# mPDF

**A fast, distraction-free PDF reader and editor for Mac and Windows.**

Read, annotate, edit text and images, organize pages, fill and sign forms —
on the page itself, with the tools out of sight until you reach for them.
Coming soon to iPhone and iPad.

[![Latest release](https://img.shields.io/github/v/release/tacshi/mPDF-Release?label=release)](https://github.com/tacshi/mPDF-Release/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/tacshi/mPDF-Release/total)](https://github.com/tacshi/mPDF-Release/releases)
![macOS 13+](https://img.shields.io/badge/macOS-13%2B-black?logo=apple)
![Windows 10+](https://img.shields.io/badge/Windows-10%2B-0078D4?logo=windows)

**[Download the latest release](https://github.com/tacshi/mPDF-Release/releases/latest)**

<br>

<img src="assets/screenshots/ipad/02-markup.jpg" width="860" alt="mPDF marking up a report: highlighted and underlined text, a note and a circled chart legend, with the Markup toolbar along the bottom">

<sub>Markup on iPad. More screenshots [below](#screenshots).</sub>

</div>

## Install

Download the file for your computer from the
[latest release](https://github.com/tacshi/mPDF-Release/releases/latest):

| File | For |
| --- | --- |
| `mPDF-<version>-arm64.dmg` | Apple Silicon Macs (M-series) |
| `mPDF-<version>-amd64.dmg` | Intel Macs |
| `mPDF-<version>-universal.dmg` | Any Mac (larger download) |
| `mPDF-<version>-windows-x64-setup.exe` | Windows installer |
| `mPDF-<version>-windows-x64.zip` | Windows, portable (no install) |

mPDF checks for newer versions automatically (you can turn this off in
Settings).

### Mac

1. Download the DMG for your Mac. Not sure which Mac you have? Apple menu →
   **About This Mac**: a "Chip" line means Apple Silicon, a "Processor" line
   means Intel.
2. Open it and drag **mPDF** into **Applications**.
3. Launch mPDF from Applications.

**Requirements:** macOS 13 Ventura or later. Every Mac build is signed and
notarized by Apple.

### Windows

1. Download and run `mPDF-<version>-windows-x64-setup.exe`.
2. The installer sets mPDF up for your account only, so it asks for no
   administrator rights. It can also add mPDF to the apps that open PDF files.
3. Launch mPDF from the Start menu.

The Windows packages are not code-signed yet, so SmartScreen may say "Windows
protected your PC" the first time. Choose **More info** → **Run anyway**.

For the portable ZIP, extract it anywhere and run `mpdf.exe`. To open PDFs
with it, run `Register-mPDF.ps1` from the same folder.

**Requirements:** Windows 10 or later, 64-bit.

### iPhone and iPad

mPDF for iPhone and iPad is coming to the App Store (iOS and iPadOS 26 or
later).

## Highlights

- **Reader-first design** — immersive reading with chrome that steps aside,
  tabs that come back where you left off, thumbnails, bookmarks, full-text
  search, single or two-page layout, and normal, sepia or night page
  appearance
- **True content editing** — edit existing text and images in place, find and
  replace text
- **Annotations** — highlights, underlines, strike-outs, notes, free text,
  pen, shapes and arrows, with full undo and redo
- **Page organizer** — reorder, rotate, duplicate, insert (blank pages,
  other PDFs, images, the clipboard), replace, extract, and split by page
  count, size or bookmarks
- **Forms and signatures** — fill forms, sign with a drawn signature, and
  reuse your own stamps; on Mac, iPhone and iPad, also sign with a
  certificate and validate digital signatures
- **Privacy tools** — find & redact (redacted content is removed from the
  saved file), remove hidden text, strip web links, add or remove password
  protection
- **Housekeeping** — reduce file size, attachments and links panels, print
- **Publications** — import Adobe Digital Editions (ACSM) and LCP
  publications on Mac and Windows
- **Command line** — an `mpdf` tool to split, rotate, compress, fill forms,
  encrypt and verify signatures from a terminal (on a Mac, install it from
  the **Tools** menu; `mpdf help` lists every command)
- **No account, no cloud** — mPDF works on your files where they are and
  collects no data

### On iPhone and iPad

- Liquid Glass bars that float over the page and hide while you read
- Apple Pencil ink with pressure, hover previews, double-tap and squeeze
- Scan paper documents into PDF pages with the camera
- Several windows side by side on iPad, with the iPad menu bar and keyboard
  shortcuts
- Built for iPhone Duo: the layout follows the device as it folds and
  unfolds

## Screenshots

<table>
  <tr>
    <td width="50%"><img src="assets/screenshots/ipad/01-reading.jpg" alt="Reading Walden with the page thumbnails sidebar and document tabs"></td>
    <td width="50%"><img src="assets/screenshots/ipad/03-edit.jpg" alt="Editing a paragraph of a lease in place"></td>
  </tr>
  <tr>
    <td align="center"><sub>Read with thumbnails and tabs</sub></td>
    <td align="center"><sub>Edit the text itself</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="assets/screenshots/ipad/02-markup.jpg" alt="Highlights, an underline, a note and a circled legend on a report"></td>
    <td width="50%"><img src="assets/screenshots/ipad/06-find-redact.jpg" alt="Find and Redact panel listing matches beside the page"></td>
  </tr>
  <tr>
    <td align="center"><sub>Mark up</sub></td>
    <td align="center"><sub>Find and redact</sub></td>
  </tr>
</table>

<table>
  <tr>
    <td width="25%"><img src="assets/screenshots/iphone/01-reading.jpg" alt="Reading on iPhone"></td>
    <td width="25%"><img src="assets/screenshots/iphone/02-markup.jpg" alt="Markup on iPhone"></td>
    <td width="25%"><img src="assets/screenshots/iphone/05-organize.jpg" alt="Organizing pages on iPhone"></td>
    <td width="25%"><img src="assets/screenshots/iphone/06-library.jpg" alt="The Library of recent documents on iPhone"></td>
  </tr>
  <tr>
    <td align="center"><sub>Read</sub></td>
    <td align="center"><sub>Mark up</sub></td>
    <td align="center"><sub>Organize pages</sub></td>
    <td align="center"><sub>Library</sub></td>
  </tr>
</table>

<table>
  <tr>
    <td width="33%"><img src="assets/screenshots/iphone-duo/01-reading.jpg" alt="Reading on an unfolded iPhone Duo"></td>
    <td width="33%"><img src="assets/screenshots/iphone-duo/03-edit.jpg" alt="Editing text on an unfolded iPhone Duo"></td>
    <td width="33%"><img src="assets/screenshots/iphone-duo/05-organize.jpg" alt="Organizing pages on an unfolded iPhone Duo"></td>
  </tr>
  <tr>
    <td colspan="3" align="center"><sub>iPhone Duo, unfolded</sub></td>
  </tr>
</table>

## Feedback

Found a bug or have a suggestion? Please
[open an issue](https://github.com/tacshi/mPDF-Release/issues).

When reporting a bug, it helps to include:

- The mPDF version (mPDF → About mPDF on a Mac, or the file name you
  downloaded)
- Your system: macOS version and Apple Silicon or Intel, or your Windows
  version
- Steps to reproduce, and a sample PDF if the issue is file-specific
  (only share files you're comfortable making public)

---

<div align="center">
<sub>© 2026 NovaOtter. Mac builds are signed and notarized by Apple.</sub>
</div>
