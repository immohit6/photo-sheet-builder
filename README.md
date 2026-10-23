# Photo Sheet Builder

Drop photos into sections, write a caption under each one, and save the sheet as a PDF. Four photos fit on a page, two across. Everything runs in the browser. Your photos never leave your phone or computer.

## Use it

1. Open the page.
2. Fill in the sheet title, subtitle and file name (all optional).
3. Drop photos into a section, or tap the drop area to pick from your files. Give each section a heading.
4. Write a caption under each photo. Use Earlier and Later, or drag a photo, to change the order.
5. Press **Make PDF**. On iPhone this opens the share sheet: choose **Save to Files**.

HEIC photos open in Safari on iPhone and Mac. Chrome on a computer cannot read them, so export those as JPG first.

Photos and captions are not stored. Make the PDF before you close the page.

## Put it on your iPhone

1. In this repo go to **Settings > Pages**, set the source to **Deploy from a branch**, branch **main**, folder **/ (root)**, and save.
2. After a minute the site is live at `https://<your-username>.github.io/photo-sheet-builder/`.
3. Open that link in Safari on your iPhone, tap **Share**, then **Add to Home Screen**.

It then opens full screen like an app and works offline after the first visit.

## Files

- `index.html` is the whole app (HTML, CSS and JavaScript).
- `vendor/jspdf.umd.min.js` is [jsPDF](https://github.com/parallax/jsPDF) 2.5.1 (MIT), kept here so the app works offline.
- `manifest.webmanifest`, `sw.js` and `icons/` make it installable on the Home Screen.
