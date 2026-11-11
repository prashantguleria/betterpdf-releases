# Changelog

Every release of Better PDF for Mac (direct download), newest first. The format follows
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/) and versions follow
[Semantic Versioning](https://semver.org/spec/v2.0.0.html). The same notes appear in the app's
update window and on [betterpdf.co/changelog](https://betterpdf.co/changelog/).

This file is generated from the release notes of each version. Please do not edit it by hand.

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

[1.0.1]: https://github.com/prashantguleria/betterpdf-releases/releases/tag/v1.0.1
[1.0.0]: https://github.com/prashantguleria/betterpdf-releases/releases/tag/v1.0.0
