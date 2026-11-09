# Stop Subscribing. Start Building. — Educator Edition

A responsive, interactive slide presentation for educators, built with plain HTML, CSS, and JavaScript. **No build tools, accounts, API keys, or package installations required.**

## Publish using GitHub Pages

1. Create a new public GitHub repository, for example `start-building-educators`.
2. Upload `index.html`, `styles.css`, and `app.js` to the repository root (not inside another folder).
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**. Select `main` and `/ (root)` and save.
5. GitHub Pages will show your published site URL, typically `https://YOUR-USERNAME.github.io/start-building-educators/`.

To embed the published presentation in another website or LMS that permits iframes:

```html
<iframe src="https://YOUR-USERNAME.github.io/start-building-educators/" title="Stop Subscribing Start Building — Interactive Presentation" width="100%" height="650" style="border:0; border-radius:12px" loading="lazy" allow="fullscreen"></iframe>
```

**Important:** GitHub hosts the app via GitHub Pages; a GitHub repository README is not itself an interactive app host. Some LMSs and sites restrict iframes. In those cases, share a link to the published site.

## Presentation controls

- Previous/Next buttons or left/right arrow keys
- Slides menu to jump between all 16 slides
- Full-screen mode
- URL slide links such as `#7` or `#9`
- Interactive AI literacy scenario (slide 7)
- Reusable build-prompt generator with copy button (slide 9)
- Interactive build/use/escalate decision guide (slide 12)

## Personalizing the content

Edit `app.js`. Slide content and titles are stored in the `slides` array. Edit `styles.css` for theme colors, typography, and spacing. Edit `index.html` to change the browser title, presenter line in site chrome, or metadata.

## Privacy and accessibility

This app uses **no external libraries or analytics** and sends **no data to a server**. Interactive inputs are used only in the browser and are not saved. Do not add sensitive student data or external collection services without school approval. The interface supports keyboard navigation, labeled inputs, responsive layout, and reduced-motion preferences.

## Attribution

This is an original educator-focused adaptation inspired by [Stop Subscribing, Start Building](https://fcis2026.vercel.app/#25), not a replication of that website.
