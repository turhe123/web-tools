# 1 free, private web tools that run in your browser

Single-purpose tools for images, PDFs, developers, text, data, audio and design. Every one is free, open source (MIT), runs entirely in your browser, needs no account, shows no ads and works offline after the first visit. Nothing you drop on a page is ever uploaded. Each tool is a free alternative to a paid or upload-based web tool you may already know.

**Browse the gallery: [turhe123.github.io/web-tools](https://turhe123.github.io/web-tools/)** · Also: [100 free, open-source Mac apps](https://turhe123.github.io/mac-apps/)

## Contents

- [Images](#images) (1)

## Images

Convert, compress, resize and clean up images without uploading them.

| | Tool | What it does | Free alternative to | Links |
|---|---|---|---|---|
| <img src="https://turhe123.github.io/compress-image-to-kb/icon.svg" width="28" alt=""> | **[Compress Image to Exact KB](https://turhe123.github.io/compress-image-to-kb/)** | Shrink a photo to a target size like 50, 100 or 200 KB in your browser, with no upload. | iLoveIMG Compress Image and ReduceImages | [Open](https://turhe123.github.io/compress-image-to-kb/) · [GitHub](https://github.com/turhe123/compress-image-to-kb) |


## How these were built

Every tool was written by [Claude Code](https://claude.com/claude-code) inside an automated pipeline from a plain-English spec, as a clean-room implementation (no code or assets from any commercial product). Each page is vanilla HTML, CSS and JavaScript with no build step; third-party code is limited to a short allowlist of vendored, MIT/Apache-licensed libraries kept in the repo with their licenses. Before a tool is published it must pass a headless Chromium test suite (Playwright): the page loads with zero console errors and zero failed requests, makes no request to any third-party host except an anonymous page-view counter, works at 390 px wide, has a real dark theme, registers a service worker and still works offline, and performs its core job on a bundled sample file. The tools have had less human review than hand-written software, so bug reports and pull requests on each repo are welcome.

## Privacy

Files are read into memory on your device and processed there. No cookies, no accounts, no tracking. Page views are counted with [GoatCounter](https://www.goatcounter.com) (anonymous, cookieless, open source).

## Support ❤️

If one of these saves you a subscription: [Support on Ko-fi](https://ko-fi.com/leodavidai).

## License

MIT © Or Davidai Bachar
