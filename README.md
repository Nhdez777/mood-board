# moodboard

A browser-based mood board tool. Drag images from the web onto a canvas, resize and arrange them, export as PNG.

Started this as a class project for a UI course and kept going with it because it was fun.

![Moodboard Screenshot](https://via.placeholder.com/700x380/faf5ff/7c3aed?text=moodboard)

## what it does

- **drag & drop** images from your computer or paste image URLs
- **freeform canvas** — move and resize anything
- **sticky notes** — add text blocks in different colors
- **export** the whole board as a PNG
- works entirely in the browser, nothing is uploaded anywhere

## built with

- Vanilla JS (no framework — wanted to practice the fundamentals)
- HTML5 Canvas for rendering
- CSS Grid for the sidebar layout
- `html2canvas` for the PNG export

## run it

No build step. Just open `index.html`.

```bash
git clone https://github.com/Nhdez777/mood-board.git
cd mood-board
open index.html   # or just drag it into a browser
```

## known issues / quirks

- CORS blocks images from some domains when pasting URLs — download and upload directly if that happens
- export quality isn't perfect for very large canvases (html2canvas limitation)
- undo history only goes back 10 steps

## maybe someday

- [ ] save/load boards from localStorage
- [ ] collaborative mode (WebRTC?)
- [ ] better text editing (inline formatting)

---

*this one's just for fun. no roadmap, no issues tracker. just a canvas.*
