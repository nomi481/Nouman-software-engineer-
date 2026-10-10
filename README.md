# Nouman — Sci-Fi Portfolio

A cinematic, animation-rich portfolio built with plain **HTML, CSS and JavaScript** (no frameworks, no build step).

## ✨ What's inside

- **Boot sequence** intro, then the screen splits open
- **Glowing particle core** in the hero that follows your mouse
- **Scroll-driven skills section** – the page pins, panels cross-fade and the whole interface **re-skins** (cyan → emerald → crimson) as you scroll
- **Page-wipe transitions** with scrambled-text titles when you jump between sections
- **Three colour themes** (switch in the menu, remembered)
- Letter-by-letter headline, typing roles, scroll reveals, counters, 3D-tilt cards, magnetic buttons, cursor ring
- Looping skills strip, testimonials marquee, FAQ accordion, drawing timeline
- Fully responsive with an animated mobile menu; respects "reduce motion"

## ✏️ Add your information (3 ways)

**1. Visual editor (easiest)**
Tap the **✎ Edit site** button at the bottom-right of the page (or add `?edit` to the address, or press `Shift + E`). When your site is finished, set **Show the Edit site button = no** in the Profile section so visitors do not see it.
A panel opens — type your details and the page updates live. You can add, delete and re-order projects, skills, experience, testimonials, FAQ and social links.

Edits are saved **in your browser only**. To show them to everyone:
1. Click **⬇ Download content.js** in the panel.
2. In your GitHub repository, replace `js/content.js` with the downloaded file (Add file → Upload files).
3. Wait a minute — your live site now shows the new content.

**2. Edit the file**
Open `js/content.js` in any text editor and change the text. Keep the quotes `"` and commas `,`.

**3. Images**
Put your photo/screenshots in the `assets/` folder and write the path in the editor, e.g. `assets/me.jpg`.

> Items marked `[SAMPLE]` in `content.js` (some projects, experience, numbers, FAQ) are placeholders — replace them with your real details.

## 🚀 Publish on GitHub Pages (free)

1. Create a repository and upload **all files** from this folder (so `index.html` is at the top level).
2. **Settings → Pages → Build and deployment →** *Deploy from a branch* → `main` and `/ (root)` → **Save**.
3. Your site goes live at `https://YOUR-USERNAME.github.io/YOUR-REPO/` in about a minute.

## 📁 Structure

```
index.html      Page shell
css/style.css   Styles, themes, animations
js/content.js   ← YOUR INFORMATION
js/main.js      Rendering, animations, transitions
js/editor.js    Visual editor (Shift+E or ?edit)
assets/         Favicon and your images
```

## License

MIT
