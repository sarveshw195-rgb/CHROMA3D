# Contributing to CHROMA 3D

Welcome! 🎨 Thanks for thinking about improving CHROMA 3D — every idea, bug report and pull request is appreciated.

## The good news: no build tools needed

CHROMA 3D is **a single HTML file**. You don't need npm, bundlers or a toolchain to contribute:

1. Fork the repo
2. Open `index.html` in your browser (or run `npx serve .` if you prefer a server)
3. Edit, refresh, test

## Ideas welcome via Issues

Not sure where to start? Open an issue and pitch it. Current roadmap ideas that would make great first contributions:

- Paint directly onto object surfaces
- Text tool
- GLB / STL export
- Environment backgrounds
- Camera presets

## Pull request rules

- **Keep the zero-CDN promise.** Only self-hosted assets. Do not add `<script src="https://...">` tags, Google Fonts links, or any resource that needs the network. If it can't live in the repo, it doesn't ship.
- **Test in the browser.** Open the page, try your change with mouse *and* keyboard shortcuts, and check the console for errors before submitting.
- **Keep everything in one file**, unless your PR is specifically a refactor dedicated to splitting the app up.
- **Attribution for new artwork assets.** Any bundled SVG, icon, font or other artwork must be freely licensed (or your own original work), rendered locally, and credited in the README with its license — same as the existing Twemoji / Fontsource / Three.js credits.

## Submitting

Keep PRs focused on one change, describe what you tested, and link the issue it fixes (if any). Small and sharp beats big and vague.

Thanks for helping CHROMA 3D grow! 🚀
