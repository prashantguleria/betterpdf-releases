# Changelog

Every release of Better PDF for Mac (direct download), newest first. The format follows
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/) and versions follow
[Semantic Versioning](https://semver.org/spec/v2.0.0.html). The same notes appear in the app's
update window and on [betterpdf.co/changelog](https://betterpdf.co/changelog/).

This file is generated from the release notes of each version. Please do not edit it by hand.

## [1.1.0] - 2026-11-21

### Added

- **Page Size**: change pages to A3, A4, A5, Letter, Legal or Tabloid, to the size of another page in the file, or to a size of your own. Scale the content to fit, keep it at its size, or fill the page. Orientation can match each page. It opens in a bar over the page, which shows the new page over a dashed outline of the old size. If content would be cut off, the bar says so first and names the pages. Text stays text, and comments, links and form fields move with the page. One undo puts it back. Tools › Page Size… (⌥⌘L), the Pages palette or the right-click menu in Pages. Free.
- **Crop Pages**: drag a frame or type the margins, or let Auto trim the empty margins (it leaves out dark scanner edges on scans). Crop odd and even pages with their own frames for book scans. A crop hides what is outside and can be undone. **Remove what is outside** (Pro) really deletes it and saves a new file, "‹name› cropped.pdf"; the original is not changed. Tools › Crop Pages… (⌥⌘K).
- **Clean Up Scanned Pages**: tidy a PDF that is already scanned. Straighten tilted pages, fix pages photographed at an angle, crop to the paper and remove dark edges, remove shadows, turn pages upright, choose a look such as Greyscale or Black and white, and choose a size. The text is read again so the pages stay searchable. The fixes leave pages that are not scans exactly as they are; Greyscale and Black and white in Look change those pages too, and the button counts the pages that will change, such as "Make 6 pages greyscale". It opens in a bar over the page, where Split shows each page before and after; the fixes are checkboxes in a second row. Apply changes the file with one undo, or Save as a new file writes "‹name› cleaned.pdf". Free for 20 pages at a time; Black and white, Whiteboard, Receipt, the smaller sizes and longer runs are Pro. Tools › Clean Up Scanned Pages… (⌥⌘U).
- **Make Greyscale**: turn any PDF grey, scanned or not, in the Clean Up bar set to Greyscale with every fix off. Text stays text and comments keep their colour. One undo puts the colour back, or Save as a new file keeps the original. Tools › Make Greyscale…, the Tools tab or the right-click menu in Pages. Free on any number of pages.
- Dropping a PDF on Scan now offers to clean it up instead, so its digital pages are not turned into pictures.
- **Remove Blank Pages**: finds the empty pages, such as the blank backs of a two-sided scan, with three sensitivity steps. A page with text, a comment or a form field is never offered, and at least one page always stays. One undo brings them back. Tools › Remove Blank Pages… (⌥⌘B). Free.
- **Page Marks**: page numbers, headers and footers, and text watermarks in front of or behind the page, with {page}, {total}, {date} and {file} in the text. Numbering can start at any number and skip a cover. Bates numbers are Pro. It opens in a bar over the page, which shows each mark live in a dashed box before you apply. Marks print and show in every app; Undo removes them. Tools › Page Marks… (⌥⌘N).
- **Compress** (Pro): save a smaller copy for Email (100 dpi), Standard (150 dpi) or Print (300 dpi), in a bar over the page instead of a separate window: it shows the size each choice gives and the page itself, original and compressed side by side (drag the line, or hold ⌥ to see the original), and Esc puts everything back as it was. Only pictures are made smaller; text, fonts and forms are not touched. It saves "‹name› compressed.pdf" and never changes the original. A password-protected file keeps its password. File › Compress… (⌥⌘J).
- **Extract** and **Split** open in a bar in place of the palette, and the page grid previews the result instead of a separate window. Extract rings the pages it takes and labels them "new page 1" and so on; click pages or type "4, 7, 13" to choose them, save one file or a file for each page, and tick **Also delete them from this file** to move them out (one undo puts them back). Split cuts every N pages, after pages you click between, at each bookmark, or by file size, and shows each part with its name, pages, size and file name; this file stays as it is. Both are free.
- **Customise Palettes**: choose which tools the Annotate, Fill & Sign, Pages and Scan palettes show, and drag them into your own order, in Settings › Palettes or by right-clicking a palette › Customise Palette…. Unticked tools move into the palette's More menu, and their shortcuts and menu items keep working; right-click a tool › Hide to move it there in one step. Reset to Default puts a palette back. Your choices apply to every window. Free.
- **What's New**: after updating from 1.0, a card lists the new tools once, each with an **Open** button that opens it on the document in front of you (or asks for a PDF first). **Release Notes** opens the list of changes on betterpdf.co. Help › What's New in Better PDF shows it again any time. It does not show after a new install.
- A small dot on a palette's **More** button says its menu holds a tool you have not used yet; it goes once you open the menu. Inside, each new tool has a **New** tag until you first use it, for 30 days at most.
- The first time a PDF made of scanned pages opens in Pages, a note over the scanned pages button offers **Clean Up…**. It shows once on your Mac, never on a signed document.
- **PDF to Excel**: save the tables in a PDF as an Excel workbook (.xlsx). Each table gets its own sheet, named Table 1, Table 2 and so on, and plain numbers are saved as numbers, so you can add them up. The bar shows the tables before you save. File › Export Tables as Excel…, or File › Export As…. Free.
- Other apps, such as file managers, can open a PDF in Better PDF straight on a tool: Edit, Fill & Sign, Recognise Text, or PDF to Word, Excel or Markdown. The file opens, or comes to the front if it is already open, and the tool is ready.

### Changed

- Recognising text in scans (OCR) and Save Digital Copy are now free, with no licence or trial needed. That includes Recognise text in Convert and Export As, and Make all pages searchable in Clean Up, which no longer counts toward its 20 free pages.
- **Convert in place**: PDF to Word, PDF to Text, PDF to Markdown and PDF to Images open in a bar over the page instead of a separate window, and the page shows the result before you save: the Word page with the fonts Word will use, the plain text, the Markdown source or rendered text, or the image at the type and scale you chose. Split shows the PDF page beside the result. A contact sheet shows the whole sheet, with 4, 5 or 6 columns under More. The save panel opens only when you press Save. File › Export As… opens the same bar, and File › Export Tables as CSV… saves the tables. The open PDF never changes.
- **Images to PDF** opens your images as pages of a new Untitled document in the page grid, with a page size (or the image's own size), Auto, Portrait or Landscape, Fit or Fill, and margins. Drag pages to reorder them, add more with Add Images… or by dropping them, then Create PDF and save it with ⌘S. Nothing is written until you save.
- Menus show icons: every Better PDF item in the menu bar and in the right-click menus has its own small symbol, the same one the toolbar, palette or tool uses, and they stay visible on macOS 27. Clean Up Scanned Pages now uses a wand, so it no longer looks like Scan.
- The Tools menu is grouped into Modes, Tools and Page Tools. Shortcuts show in the right-hand column instead of inside the names, and each item has a short tip. Single-key shortcuts still type normally in text fields.
- Changing pages in a signed document now asks first. **Change a Copy** opens "‹name› copy.pdf" in a new tab and keeps the signed original as it is; **Change This File** goes ahead, and the signatures are no longer valid after you save. In the App Store edition, if the copy cannot be saved beside the original, you are asked where to save it.
- The Tools tab has cards for the new page tools, Clean Up and Compress. The Grayscale card is now Make Greyscale, which changes the pages in place instead of saving a grey copy.
- Crop opens in a bar in place of the palette instead of a popover: margins, Keep margins equal, Auto, Apply to, Odd and Even, and Remove what is outside are all in the bar, the page arrows sit under the page, and holding ⌥ shows the page uncropped.
- Switching to Scan is quicker the first time: the camera list is read in the background, so the window no longer pauses while the cameras are found.
- Take Snapshot copies the pages you see again. It had been copying a blank white picture, because the pages are drawn in a layer the capture could not see; it now draws the visible pages, notes and markup included, at your screen's sharpness.
- A tool's bar can no longer be dragged out of the window: its grip stops at every edge, and making the window smaller brings the bar back inside.

### Fixed

- The tool bars (Compress, Clean Up, Page Size, Page Marks, Crop, Extract and Split) now follow your theme in light, dark and E-ink: choices, pop-up menus and checkboxes use the theme's own colours, and only the main button uses the accent colour.
- Nothing in the app is drawn in the system blue any more. Focus rings, highlighted menu items, checkboxes and selected rows use your theme's colours or a neutral grey, including in Settings, Palettes and the sheets.
- The tool bars always fit the window. In a narrow window, options that do not fit move into a More menu, and Cancel and the main button always stay visible. Page Marks with Watermark chosen no longer runs past the edge of the window.
- **Image watermarks** in Page Marks: choose Text or Image under Watermark, then drop a logo or stamp on the bar or the page, or choose one. PNG, JPEG, HEIC, PDF (first page) and SVG work, transparent parts stay clear, and PDF and SVG stay sharp. Set the opacity, size as a share of the page width, angle, one of nine positions, and in front or behind. The last five pictures are kept under Recent. Text watermarks get an opacity slider beside the number. Free, like text watermarks.
- Crop: dragging a corner or edge of the frame now follows the pointer exactly. A corner could jump the wrong way.
- Typing a page range in a tool bar no longer stops after the first character when the main button's title changes.
- Pages: clicking a page thumbnail now selects it at once. It used to wait for the double-click delay.
- Translations: each tool now has one name per language in the palette, the menus, the tool bar, Edit › Undo and the help pages (for example Crop in German and Japanese, Page Size in Italian and Hindi, Split in Hindi, Remove Blank Pages in French and Chinese). Chinese now says 调板 for palette, as macOS does.

## [1.0.4] - 2026-11-19

### Changed

- PDF to Word now rebuilds the document so it can be edited in Word or Pages: whole paragraphs with their alignment and spacing, headings, columns read in order, real tables (ruled or not, with merged cells), real bulleted and numbered lists, fonts, colours, bold, italic, underline, superscript, links, pictures at their size, footnotes, and repeating headers, footers and page numbers moved into the Word header and footer. Each page keeps its size, so landscape pages stay landscape.
- PDF to Word keeps backgrounds behind the text. A full-page picture under the text, a watermark, a letterhead band or a page border no longer pushes the text around or gets mixed into it; the words stay as normal text in their own colour.
- PDF to Word keeps designed pages together. A page laid out like a statement or a brochure, with pictures on one side and panels and tables on the other, keeps each block at its place in a text box, so the page count stays the same and nothing is stacked or shown twice. Panels with round corners and coloured bands are drawn behind their text, tables inside panels stay tables, small coloured labels become highlighted text, and small icons stay in their table cells. Text on a coloured panel stays on its panel even when Word uses a different font: lines keep the height they had in the PDF. The font is chosen by how wide the PDF set its words: the PDF's own font when Word has it, otherwise the common font that sets the same words closest to the same width, then a slightly smaller size, and letters are narrowed only for what is left. Letters are never stretched or spaced out. A numbered list in a panel starts where it did in the PDF and wraps inside the panel, table rows are never shorter than their text, and words in a small outlined button or a pill stay inside it. A row of pictures that is a little wider than the text is scaled to stay on one line, and each PDF page is fitted to one Word page.
- PDF to Word writes the rupee sign where a PDF draws it with a special font that used to come out as the letter C.
- Signing with a USB token, in the direct download: Better PDF now finds the drivers of more tokens, not only the Watchdata ProxKey. It knows where Feitian ePass2003 and HYP2003, SafeNet eToken, Thales IDPrime and OpenSC put their driver, it uses drivers your token software has already registered on this Mac, and it looks in the usual folders where token software installs a driver, so many other tokens work with no setup. That search covers a short list of system folders only, never your home folder, and you can turn it off with **Find Drivers Automatically** under **Manage**. If your token is still not found, open **Settings › Signing**, then **Manage** in the **Token drivers** row, and choose the driver file or add the folder that holds it. Messages about the token no longer name one brand, and **Help › Diagnostics…** lists the drivers that were found and which one is in use.
- Signing: a certificate that reaches Better PDF both through a token driver and through the Keychain is now listed once.

### Fixed

- Scan: **Capture when steady** now takes the photo when you hold a page under your iPhone. It used to wait for the page to be perfectly still for a full second, which a hand never manages, so the pill stayed on "Page found · hold steady". A page that stays roughly in place for about a second is now captured, a page that is still moving is not, and each page is taken once: the pill reads "Captured · show the next page" until you swap the page or take it away.
- Scan: the list of cameras now keeps itself up to date. Your iPhone's camera returns to the list after you stop the camera or the iPhone reconnects, without leaving Scan and coming back. If the iPhone is not listed, a line under the cameras says what to check.
- Scan: **Scan Documents on iPhone…** now opens its menu under the row, with your iPhone's Take Photo and Scan Documents under Import from iPhone or iPad, and the menu stays open until you choose. It used to open a small menu in the top left corner of the window with only a greyed title. The same list is also in the menu bar, under **File › Import from iPhone or iPad**, while Scan is open.
- Scan: if your iPhone was used as the camera before and is missing now (usually because Disconnect was tapped on it), **Reconnect iPhone camera…** under Cameras shows how to bring it back, with **Check Again**. While the iPhone is the camera, a line under the controls says to finish on the Mac: the camera is let go by itself when you save, press Esc, leave Scan, switch tabs, close the window or quit, so the iPhone goes back to its normal screen with nothing to press on it.

## [1.0.3] - 2026-11-11

### Fixed

- Signing with a certificate from your keychain no longer stops at "The certificate is no longer available. Choose it again." for a certificate that is still there. Sign & Save now finds the certificate again when the keychain's saved reference to it does not lead back to it. If signing still fails, Help › Diagnostics… now records the reason.
- Without a USB token driver installed, the app's log no longer fills with one "driver missing" line every second while Fill & Sign is open. A diagnostics report is smaller and easier to read.

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

[1.1.0]: https://github.com/prashantguleria/betterpdf-releases/releases/tag/v1.1.0
[1.0.4]: https://github.com/prashantguleria/betterpdf-releases/releases/tag/v1.0.4
[1.0.3]: https://github.com/prashantguleria/betterpdf-releases/releases/tag/v1.0.3
[1.0.2]: https://github.com/prashantguleria/betterpdf-releases/releases/tag/v1.0.2
[1.0.1]: https://github.com/prashantguleria/betterpdf-releases/releases/tag/v1.0.1
[1.0.0]: https://github.com/prashantguleria/betterpdf-releases/releases/tag/v1.0.0
