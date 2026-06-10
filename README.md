# Touch the World, Talk to Code

A 20-minute teaching slideshow about **IoT hardware** for students aged 12-18, with a build-along
demo. Students use a **free AI tool** to vibe-code a fun web toy (a "Banana Piano"), then bring it to
life with a **Makey Makey** board in the hands-on session afterwards.

The whole thing is static HTML/CSS/JS — no build step — and deploys to **GitHub Pages** as-is.
Styled with Chan Meng's "Caldera" personal brand system.

## The core idea

Makey Makey pretends to be a USB keyboard. Touching a banana is the same as pressing `Space`. So a
web page that responds to key presses works **identically** whether the input is your keyboard (during
the talk) or a banana (during the hands-on). The app needs **no hardware to build and play** — the
board only changes *how* the keys get pressed.

## What's inside

| Path | What it is |
| --- | --- |
| `index.html` | The 8-slide deck. Arrow keys / Space to move, `N` for speaker notes. |
| `demo/index.html` | The runnable Banana Piano. Keyboard-playable, Web Audio (no sound files). |
| `handout/index.html` | One-page printable student handout (print to one page). |
| `notes/speaker-notes.md` | Per-slide talking points with minute-by-minute timing. |
| `assets/` | Brand tokens, deck styles, navigation script, logo + halftone art. |

## Present it

1. Open `index.html` in a browser and press `F` (or your browser's full-screen).
2. Navigate: **Arrow keys**, **Space**, or **Page Up/Down**. `Home` / `End` jump to first / last.
3. Press **N** to show speaker notes with the timing for the current slide. `Esc` hides them.
4. On the "Play it" slide, click **Open the working demo** to switch to `demo/index.html` as a
   reliable live example.

The students' build-along prompt (kept short on purpose):

> Make a fun web-page piano. When I press Space, the arrow keys, or W A S D F G, play a different
> musical note and flash a big colourful button for that key on the screen. Make it work with a
> normal keyboard.

## Free AI tools (as of June 2026)

- **In the browser (recommended for classrooms):** a free AI builder you sign into with a Google
  account — nothing to install, works on locked-down school laptops.
- **On your own computer:** [Cursor](https://cursor.com) — a free code editor for students with AI
  built in, no credit card.
- Note: Google's Gemini CLI free tier is being retired on **18 June 2026**, so the deck deliberately
  stays tool-agnostic rather than depending on any one CLI.

## Deploy to GitHub Pages

1. Create a new GitHub repository and push this folder to the `main` branch.
2. In the repo: **Settings -> Pages**.
3. Under **Build and deployment**, set **Source: Deploy from a branch**, **Branch: `main` / `(root)`**,
   then **Save**.
4. After a minute the site is live:
   - Slides: `https://<user>.github.io/<repo>/`
   - Demo: `https://<user>.github.io/<repo>/demo/`
   - Handout: `https://<user>.github.io/<repo>/handout/`

A `.nojekyll` file is included so the `assets/` and `demo/` folders are served unchanged.

## Notes

- Fonts (Anton, DM Sans, JetBrains Mono) load from Google Fonts; everything degrades to system fonts
  offline. To go fully offline, self-host the `woff2` files and swap the `<link>` for a local
  `@font-face` block.
- No emoji, English copy, designed to run under 20 minutes.

---

Built by Chan Meng · [chanmeng.org](https://chanmeng.org) · [github.com/ChanMeng666](https://github.com/ChanMeng666)
