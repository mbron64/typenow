<div align="center">

# widyo.io

**A black canvas. Type anywhere. Draw anywhere. Let the ideas flow**

[![Live Demo](https://img.shields.io/badge/demo-widyo.io-000000?style=for-the-badge&logoColor=white)](https://widyo.io)

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](LICENSE)
[![Zero Dependencies](https://img.shields.io/badge/dependencies-0-brightgreen?style=flat-square)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/mbron64/widyo/pulls)

<br />

<img width="600" alt="widyo demo" src="typenowgif.gif">

*No accounts. No servers. No tracking. Your work stays on your device.*

</div>

---

## What is this?

widyo (write it down yo) is a deliberately minimal creative canvas. Click to type. Drag to draw. Move and resize anything. There are no toolbars, no menus, no settings. The constraint is the feature.

**Nothing leaves your device.** There are no accounts, no cloud storage, no server-side anything. When you save (Cmd+S), widyo downloads a self-contained HTML file to your machine. That file has everything in it -- your content, the styles, the code -- and it works offline. Open it in any browser to pick up where you left off. This is the most private way to take notes: your data never touches a server.

### Use it for

- Braindumps and stream-of-consciousness writing
- Freehand sketching and visual thinking
- Spatial note-taking and mind mapping
- Poetry and creative layout experiments
- Whiteboarding without the clutter

## Try it

**[widyo.io](https://widyo.io)** -- open it and start creating.

Or run it locally:

```bash
git clone https://github.com/mbron64/widyo.git
cd widyo
open index.html
```

That's it. No install, no build step, no dependencies.

## How it works

The entire app is a single `index.html` file of vanilla HTML, CSS, and JavaScript.

| Action | What happens |
|---|---|
| Click on empty space | A text block is created -- start typing |
| Click-drag on empty space | Draw a freehand stroke |
| Shift+drag | Draw a perfect shape (line, circle, triangle, rectangle) |
| Click on a drawing | Select it (resize/move handles appear) |
| Click on a text block | Select it (resize/move handles appear) |
| Double-click a text block | Enter edit mode (cursor inside text) |
| Right-click drag | Multi-select elements for group move, resize, or delete |
| Drag corner handles | Resize drawings or change text font size |
| Drag mid-edge handles | Resize text block width |
| Type a color name while selected | Change the element's color (e.g. type `red`, `light blue`, `#ff0`) |
| Type `fill` + color on a shape | Fill the shape interior (e.g. `fill red`) |
| Highlight text, then type a color | Change just the highlighted text's color |
| Cmd+S / Ctrl+S | Save and download the canvas as a working HTML file |
| Cmd+O / Ctrl+O | Open a previously saved widyo file |
| Drag and drop a .html file | Load a saved canvas into the current session |
| Cmd+Z / Cmd+Shift+Z | Undo / redo everything |
| Delete / Backspace | Remove selected element |

### Privacy

- No accounts, no sign-ups, no cookies
- No cloud storage -- everything stays on your machine
- Saved files are fully self-contained HTML -- they work offline, forever
- No data is ever sent to a server

### Tech stack

```
index.html   ← the entire app
```

No frameworks. No bundlers. No transpilers. No node_modules. Zero dependencies.

## Contributing

Contributions are welcome. widyo's philosophy is radical simplicity -- every feature should feel invisible until you need it.

1. Fork the repo
2. Create your branch (`git checkout -b feature/your-idea`)
3. Commit your changes (`git commit -m 'Add your-idea'`)
4. Push to the branch (`git push origin feature/your-idea`)
5. Open a Pull Request

### Ideas welcome

- Export to image/PDF
- Collaboration via WebRTC

Open an [issue](https://github.com/mbron64/widyo/issues) to discuss before building anything large.

## License

MIT -- do whatever you want with it. See [LICENSE](LICENSE) for details.

---

<div align="center">

**[widyo.io](https://widyo.io)**

</div>
