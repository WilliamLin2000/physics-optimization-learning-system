# Physics & Optimization Learning System

An interactive, browser-based learning platform covering physics and optimization design, from beginner to expert level. Includes 22 animated visualizations with adjustable parameters, an AI tutor, exercises, and progress tracking.

## How to use

1. **Open** `physics_optimization_learning_system_v4.html` in any modern web browser (Chrome, Firefox, Safari, Edge). Just double-click the file — no installation needed.
2. **Switch subjects** using the pills at the top of the sidebar (Physics / Optimization).
3. **Pick a lesson** from the expandable level groups (Beginner → Expert).
4. **Explore the tabs** for each lesson:
   - *Concept* — the theory and key formulas.
   - *Visualization* — interactive canvas with sliders and parameter explanations.
   - *Exercises* — practice problems with revealable answers.
5. **Mark lessons complete** with the button in the top-right; progress is tracked in the sidebar.

## AI Tutor (optional)

The AI tutor at the bottom can answer any question about the current lesson. To enable it:

1. Get an Anthropic API key at <https://console.anthropic.com>.
2. Click the **⚙ AI key** button in the top-right of the page.
3. Paste your key and click Save. The key is stored only in your browser (localStorage).
4. Type a question or use the quick-chips ("Give a real-world example", etc.) and press Ask.

**Security note:** the key lives in whichever browser you pasted it into. If the file is opened by multiple people on the same computer, all of them can use your key. Click **Clear** in the settings dialog to remove it when you're done.

The platform works fully without a key — the tutor is just an optional add-on. Every visualization, lesson, and exercise works offline.

## Sharing

Because this is a single self-contained HTML file, you can share it the same way you'd share a PDF:

- **Email** — attach the `.html` file. Recipients open it by double-clicking.
- **Cloud drive** — upload to Google Drive, Dropbox, OneDrive, etc. and share the link. Recipients download the file and open it.
- **USB / shared folder** — copy the file over like any document.
- **Web hosting** — if you want a URL, drop the file on any static host (GitHub Pages, Netlify, Cloudflare Pages, Vercel — all free for small projects). The file will be publicly accessible at a URL.

No server, database, or build step is required. The entire platform runs in the browser.

## Browser compatibility

Tested on Chrome, Firefox, Safari, and Edge. Requires a modern browser (released within the last ~3 years) because of ES6 features and the Canvas API. Works on desktop and tablet; the layout adapts to narrower screens.

## Credits

Built with Claude. Feel free to modify the HTML/CSS/JavaScript to customize lessons, add content, or change styling.
