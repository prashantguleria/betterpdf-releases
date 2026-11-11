# Changelog

Every release of Better PDF for Mac (direct download), newest first. The format follows
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/) and versions follow
[Semantic Versioning](https://semver.org/spec/v2.0.0.html). The same notes appear in the app's
update window and on [betterpdf.co/changelog](https://betterpdf.co/changelog/).

This file is generated from the release notes of each version. Please do not edit it by hand.

## [1.0.2] - 2026-11-11

### Changed

- Go › Back (⌘[) and Go › Forward (⌘]) return you to where you were before a jump: a link inside the document, a search result, a bookmark or an outline entry, a comment in the list, Go to Page, or the first and last page commands.
- Find has two options at the right of the field: Match Case and Whole Words. Both are off to start with.
- The menu for selected text now also has the system's Translate, the web search and Share.
- A document reopens at the exact spot you left it, not at the top of that page, and with the page layout you last used for it (single page, continuous, two pages).
- View › Fit Page (⌘8) zooms so the whole page fits in the window.
- With Reduce Motion turned on in System Settings, panels, bars and palettes appear without sliding or fading.
- Signing with a certificate: the save dialog now suggests the document's own name instead of "name signed.pdf". Saving with that name replaces the document after the usual Replace question, and the previous version is kept; type another name to save a separate signed copy.
- A PDF that opens without a password but was restricted by its author no longer blocks you outright. The first time you print, copy or start editing, a card says the file is restricted by its author. Cancel leaves things as they are; Continue Anyway carries on and is remembered until you close the file. A file that needs a password to open still needs it.
- File › Document Properties… › Security now shows the security method, the encryption level (for example 128-bit RC4), whether there is a password to open and a permissions password, and a line each for printing (high or low resolution), changing the document, commenting, filling form fields and signing, document assembly, content copying, copying for accessibility and page extraction.
- File › Document Properties… has a Custom tab that lists the extra details some apps store in a PDF, such as a company name, as names and values you can select and copy.

### Fixed

- Saving with E-ink on no longer turns pages into pictures. With E-ink reading or the E-ink appearance on, a save (including the automatic save after an edit), Save As, an export, a conversion, extracted or split pages and a print all wrote each page as one grey image: the text could no longer be selected or searched, fonts and colour were gone, and highlights were drawn into the picture. Every one of these now writes the document as it was authored, in full colour, with its text, fonts and annotations. E-ink only changes what you see on screen.
- A file that was saved this way cannot be repaired from itself, because the text and colour are no longer in it. Open it and choose File › Revert To › Browse All Versions… to go back to a version from before the save, or restore the file from Time Machine or another backup.
- In the E-ink appearance, the name of the active tool in the mode bar (for example Highlight in Annotate) and the selected row in Tools are readable again. They were black on black.
- The floating toolbar keeps its shape at the sides of the window. Dragging it to the left or right edge used to turn it into the narrow side bar, which has no labels and, in a short window, moves some tools into More Tools. It now rests against the edge as it is, whole and with its labels. To dock it to the side, keep pushing it past the edge until the side outline lights up, or use View › Mode Palette.
- Edit mode: the card shown for a signed document now says the signature will show as changed after signing, the same words the signature panel uses after the save. It used to say invalid.
- File › Document Properties… › Security showed "Password protected" and every permission as allowed for a file that opens without a password but restricts printing, copying or editing. It now says "Restricted by its author" and shows the permissions the file really has.
- Saving a PDF no longer removes its custom properties, the extra details some apps store in a file, such as a company name or a document ID. A save, Save As, a saved copy, adding or removing a password and a searchable copy of a scan all keep them, with their values as they were.

## [1.0.1] - 2026-11-11

### Added

- Shapes and lines in Annotate: press R for rectangle, ellipse, line, arrow, polygon, polyline and cloud, with stroke, dash, fill, opacity and line ends. They are saved as standard PDF annotations. Pro.
- Stamps: press K for standard stamps, dynamic stamps with your name and the date, and your own stamps made from an image or a PDF page (Tools › Create Stamp… and Manage Stamps…). Pro.
- Shapes and stamps are listed in the Comments tab and in Copy All Notes as Markdown.
- Rulers: View › Show Rulers (⌥⌘R) in points, pixels at a chosen pixels per inch, millimetres, centimetres or inches, with pointer markers and the pointer position in the status bar. In Read, Annotate, Edit and Fill & Sign. Free.
- Tools opens as a tab in the main window, with a File pop-up for open tabs, recent files or Choose file… (⌘O).
- Home has a Start row (Scan, Convert a PDF, Images to PDF, All tools) and a Create section in the sidebar. A scan started from Home saves as a new PDF.
- A new About window shows the version, build and edition (Direct download or Mac App Store). Credits… there, or Help › Credits…, lists the software Better PDF uses with its licences, and Copy All copies them.
- The Better PDF mark in signature styles is the new mark, in the theme's accent colour. Styles that use the old mark are updated and keep their opacity, size and position.

### Fixed

- Scan no longer quits when the camera starts, and finds page edges more often.
- Narrow windows no longer cut off the inspector or the tool palette. Side panels step aside when space is tight, the palette shows icons only and puts what does not fit under More Tools, and the status bar hides less important details first.
- The pointer position in the status bar keeps a clear gap between the x and y values in every unit.
- Editing a signed document now offers Edit This File as well as Edit a copy. Editing the file itself keeps its signatures, which then show as changed after signing.
- Licence text in every language now says one Mac, one iPhone and one iPad.

## [1.0.0] - 2026-11-06

### Added

- The first release of Better PDF: read, annotate, edit, fill and sign PDFs in a calm, native Mac app.
- Certificate signing with a Watchdata ProxKey token, saved as an incremental update so the original stays intact.
- Signature styles with your logo, name, date and reason, in every viewer.
- Help › Diagnostics… gathers the log, crash reports and token status into a zip you can send. Nothing leaves your Mac on its own.
- Better PDF checks for updates once a day. Turn it off in Settings › General.

[1.0.2]: https://github.com/prashantguleria/betterpdf-releases/releases/tag/v1.0.2
[1.0.1]: https://github.com/prashantguleria/betterpdf-releases/releases/tag/v1.0.1
[1.0.0]: https://github.com/prashantguleria/betterpdf-releases/releases/tag/v1.0.0
