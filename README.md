# CHROMA 3D â€” Paint in Space ðŸŽ¨âœ¨

A **Microsoft Paint 3Dâ€“style 3D painting studio** that runs entirely in your browser. Draw 3D strokes, drop emoji stickers and 3D objects, then grab, spin and resize everything like real scene objects.

**â–¶ Play it live: https://sarveshw195-rgb.github.io/CHROMA3D/**

## Features

- ðŸ–Š **5 pen types** â€” marker, pencil, neon (glows), chalk (fat & rough), metal (reflective)
- ðŸ˜€ **16 emoji stickers** â€” bundled as crisp SVG (Twemoji), fully offline, always render
- ðŸ§Š **3D objects** â€” cube, sphere, cone, cylinder, torus, knot, star & parametric heart
- âœ‹ **Paint-3D-style SELECT mode** â€” click anything â†’ move / rotate (yaw + pitch) / scale with the on-object gizmo
- â†© **Unified undo** (60 steps), including transforms
- ðŸ’¾ **Save / open** your artwork as a .chroma (JSON) file, export **transparent PNG**
- ðŸŒˆ **Right-side rail** â€” pens, colour palette and file actions
- ðŸŒ **100% self-hosted** â€” fonts (Anton, Inter) and emoji ship with the app; zero CDN calls

## Run it

Any static server works:

`ash
npx serve .      # or: python -m http.server
`

## Build a single Windows exe

`ash
npx -y @neutralinojs/neu@11 build --embed-resources
`

The exe is fully self-contained (HTML + fonts + emoji embedded, ~3.3 MB).

## Keyboard

B draw Â· G emoji Â· O objects Â· S select Â· E erase Â· 1â€“8 colours Â· Ctrl+Z undo Â· Del delete selected Â· Esc deselect

## Credits

- Built with [Three.js](https://threejs.org)
- Emoji: [Twemoji](https://github.com/jdecked/twemoji) 15.1.0 â€” CC-BY 4.0
- Fonts: Anton & Inter (OFL) via [Fontsource](https://fontsource.org)
- Light/colour watch inspired by Microsoft Paint 3D UI concepts

## License

MIT â€” see [LICENSE](LICENSE)