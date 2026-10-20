# 11 free, private web tools that run in your browser

Single-purpose tools for images, PDFs, developers, text, data, audio and design. Every one is free, open source (MIT), runs entirely in your browser, needs no account, shows no ads and works offline after the first visit. Nothing you drop on a page is ever uploaded. Each tool is a free alternative to a paid or upload-based web tool you may already know.

**Browse the gallery: [turhe123.github.io/web-tools](https://turhe123.github.io/web-tools/)** · Also: [100 free, open-source Mac apps](https://turhe123.github.io/mac-apps/)

## Contents

- [Images](#images) (1)
- [PDF](#pdf) (10)

## Images

Convert, compress, resize and clean up images without uploading them.

| | Tool | What it does | Free alternative to | Links |
|---|---|---|---|---|
| <img src="https://turhe123.github.io/compress-image-to-kb/icon.svg" width="28" alt=""> | **[Compress Image to Exact KB](https://turhe123.github.io/compress-image-to-kb/)** | Shrink a photo to a target size like 50, 100 or 200 KB in your browser, with no upload. | iLoveIMG Compress Image and ReduceImages | [Open](https://turhe123.github.io/compress-image-to-kb/) · [GitHub](https://github.com/turhe123/compress-image-to-kb) |

## PDF

Merge, split, compress and rework PDFs on your own device.

| | Tool | What it does | Free alternative to | Links |
|---|---|---|---|---|
| <img src="https://turhe123.github.io/images-to-pdf-local/icon.svg" width="28" alt=""> | **[Images to PDF Converter](https://turhe123.github.io/images-to-pdf-local/)** | Turn photos and screenshots into one PDF in your browser, with page size and order control, no upload. | JPG to PDF at iLovePDF and Smallpdf | [Open](https://turhe123.github.io/images-to-pdf-local/) · [GitHub](https://github.com/turhe123/images-to-pdf-local) |
| <img src="https://turhe123.github.io/pdf-form-flattener/icon.svg" width="28" alt=""> | **[PDF Form Filler and Flattener](https://turhe123.github.io/pdf-form-flattener/)** | Fill in PDF form fields and flatten them into plain pages in your browser, with no upload. | Smallpdf and Sejda Flatten PDF | [Open](https://turhe123.github.io/pdf-form-flattener/) · [GitHub](https://github.com/turhe123/pdf-form-flattener) |
| <img src="https://turhe123.github.io/pdf-page-numbers-adder/icon.svg" width="28" alt=""> | **[PDF Page Number Adder](https://turhe123.github.io/pdf-page-numbers-adder/)** | Stamp page numbers on any PDF in your browser, with position, format and start number, no upload. | Sejda Add Page Numbers and PDF24 | [Open](https://turhe123.github.io/pdf-page-numbers-adder/) · [GitHub](https://github.com/turhe123/pdf-page-numbers-adder) |
| <img src="https://turhe123.github.io/pdf-page-organizer/icon.svg" width="28" alt=""> | **[PDF Page Organizer](https://turhe123.github.io/pdf-page-organizer/)** | Reorder, rotate and delete PDF pages visually in your browser and save the result, with no upload. | Sejda and iLovePDF Organize PDF | [Open](https://turhe123.github.io/pdf-page-organizer/) · [GitHub](https://github.com/turhe123/pdf-page-organizer) |
| <img src="https://turhe123.github.io/pdf-text-extractor/icon.svg" width="28" alt=""> | **[PDF Text Extractor](https://turhe123.github.io/pdf-text-extractor/)** | Copy or save all the text from a PDF as a TXT file in your browser, with nothing uploaded. | Adobe Acrobat online and Smallpdf PDF to Text | [Open](https://turhe123.github.io/pdf-text-extractor/) · [GitHub](https://github.com/turhe123/pdf-text-extractor) |
| <img src="https://turhe123.github.io/pdf-to-images-zip/icon.svg" width="28" alt=""> | **[PDF to Images Converter](https://turhe123.github.io/pdf-to-images-zip/)** | Convert every PDF page to PNG or JPG in your browser and save them as a ZIP, with no upload. | PDF to JPG at iLovePDF and Adobe Acrobat online | [Open](https://turhe123.github.io/pdf-to-images-zip/) · [GitHub](https://github.com/turhe123/pdf-to-images-zip) |
| <img src="https://turhe123.github.io/pdf-watermark-stamper/icon.svg" width="28" alt=""> | **[PDF Watermark Stamper](https://turhe123.github.io/pdf-watermark-stamper/)** | Add a text or image watermark like CONFIDENTIAL to every PDF page in your browser, with no upload. | Smallpdf and iLovePDF Watermark PDF | [Open](https://turhe123.github.io/pdf-watermark-stamper/) · [GitHub](https://github.com/turhe123/pdf-watermark-stamper) |
| <img src="https://turhe123.github.io/pdf-merge-private/icon.svg" width="28" alt=""> | **[Private PDF Merger](https://turhe123.github.io/pdf-merge-private/)** | Combine several PDFs into one file in your browser, with drag to reorder and nothing uploaded. | iLovePDF Merge PDF | [Open](https://turhe123.github.io/pdf-merge-private/) · [GitHub](https://github.com/turhe123/pdf-merge-private) |
| <img src="https://turhe123.github.io/sign-pdf-private/icon.svg" width="28" alt=""> | **[Private PDF Signer](https://turhe123.github.io/sign-pdf-private/)** | Draw or type your signature and place it on a PDF page in your browser, with no account and no upload. | Smallpdf eSign PDF and DocuSign free plan | [Open](https://turhe123.github.io/sign-pdf-private/) · [GitHub](https://github.com/turhe123/sign-pdf-private) |
| <img src="https://turhe123.github.io/split-pdf-pages-local/icon.svg" width="28" alt=""> | **[Split PDF by Pages](https://turhe123.github.io/split-pdf-pages-local/)** | Split a PDF into single pages or custom ranges in your browser and save them as a ZIP, nothing uploaded. | Smallpdf Split PDF | [Open](https://turhe123.github.io/split-pdf-pages-local/) · [GitHub](https://github.com/turhe123/split-pdf-pages-local) |


## How these were built

Every tool was written by [Claude Code](https://claude.com/claude-code) inside an automated pipeline from a plain-English spec, as a clean-room implementation (no code or assets from any commercial product). Each page is vanilla HTML, CSS and JavaScript with no build step; third-party code is limited to a short allowlist of vendored, MIT/Apache-licensed libraries kept in the repo with their licenses. Before a tool is published it must pass a headless Chromium test suite (Playwright): the page loads with zero console errors and zero failed requests, makes no request to any third-party host except an anonymous page-view counter, works at 390 px wide, has a real dark theme, registers a service worker and still works offline, and performs its core job on a bundled sample file. The tools have had less human review than hand-written software, so bug reports and pull requests on each repo are welcome.

## Privacy

Files are read into memory on your device and processed there. No cookies, no accounts, no tracking. Page views are counted with [GoatCounter](https://www.goatcounter.com) (anonymous, cookieless, open source).

## Support ❤️

If one of these saves you a subscription: [Support on Ko-fi](https://ko-fi.com/leodavidai).

## License

MIT © Or Davidai Bachar
