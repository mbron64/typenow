<div align="center">

# typenow

**A black canvas. Type anywhere. Draw anywhere. Let the ideas flow**

[![Live Demo](https://img.shields.io/badge/demo-typenow.web.app-000000?style=for-the-badge&logoColor=white)](https://typenow.web.app)

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](LICENSE)
[![Zero Dependencies](https://img.shields.io/badge/dependencies-0-brightgreen?style=flat-square)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/mbron64/typenow/pulls)

<br />

<img width="600" alt="typenow demo" src="typenowgif.gif">

*No accounts. No toolbars. No distractions. Just you and your thoughts.*

</div>

---

## What is this?

typenow is a deliberately minimal creative canvas. Click to type. Drag to draw. Move and resize anything. There are no toolbars, no menus, no save buttons, no settings. The constraint is the feature.

### Use it for

- Braindumps and stream-of-consciousness writing
- Freehand sketching and visual thinking
- Spatial note-taking and mind mapping
- Poetry and creative layout experiments
- Whiteboarding without the clutter

## Try it

**[typenow.web.app](https://typenow.web.app)** -- open it and start creating.

Or run it locally:

```bash
git clone https://github.com/mbron64/typenow.git
cd typenow
open index.html
```

That's it. No install, no build step, no dependencies.

## How it works

The entire app is a single `index.html` file of vanilla HTML, CSS, and JavaScript.

| Action | What happens |
|---|---|
| Click on empty space | A text block is created -- start typing |
| Click-drag on empty space | Draw a freehand stroke |
| Click on existing text | Resume editing that block |
| Click near caret, then click again | Select the text block (resize/move handles appear) |
| Click on a drawing | Select it (resize/move handles appear) |
| Drag corner handles | Resize drawings or change text font size |
| Cmd+Z / Cmd+Shift+Z | Undo / redo everything |
| Delete / Backspace | Remove selected element |

### Tech stack

```
index.html   ← the entire app
```

No frameworks. No bundlers. No transpilers. No node_modules. Zero dependencies.

## Contributing

Contributions are welcome. typenow's philosophy is radical simplicity -- every feature should feel invisible until you need it.

1. Fork the repo
2. Create your branch (`git checkout -b feature/your-idea`)
3. Commit your changes (`git commit -m 'Add your-idea'`)
4. Push to the branch (`git push origin feature/your-idea`)
5. Open a Pull Request

### Ideas welcome

- Touch/mobile and stylus support
- Persistence via localStorage
- Export to image/PDF
- Customizable colors/fonts via URL params
- Collaboration via WebRTC

Open an [issue](https://github.com/mbron64/typenow/issues) to discuss before building anything large.

## License

MIT -- do whatever you want with it. See [LICENSE](LICENSE) for details.

---

<div align="center">

**[typenow.web.app](https://typenow.web.app)**

</div>
