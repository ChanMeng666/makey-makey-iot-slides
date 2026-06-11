# Touch the World, Talk to Code

A 20-minute teaching slideshow about **IoT hardware** for students aged 12-18, with three build-along
demos that step up in difficulty. Students use **Claude** (free, in the browser) to vibe-code three fun
web toys — an easy **Banana Piano**, a medium **Memory Game** (Simon Says), and a challenge
**Catch & Dodge Game** — then bring them to life with a **Makey Makey** board in the hands-on session
afterwards.

The whole thing is static HTML/CSS/JS — no build step — and deploys to **GitHub Pages** as-is.
Styled with Chan Meng's "Caldera" personal brand system.

Created for the **Youth Tech Series — AI & Electronics Workshop** (SheSharp × Peyvand Academy ×
Ministry of Education), 13 June 2026, Fruitvale Primary School, Auckland.

## The core idea

Makey Makey pretends to be a USB keyboard. Touching a banana is the same as pressing `Space`. So a
web page that responds to key presses works **identically** whether the input is your keyboard (during
the talk) or a banana (during the hands-on). The toys need **no hardware to build and play** — the
board only changes *how* the keys get pressed.

## Why Claude

We build all three toys live with [claude.ai](https://claude.ai): it is free to start, runs in the
browser (nothing to install on locked-down school laptops), and renders each app in its **Artifact**
live-preview panel — so the class sees and plays the toy the moment Claude finishes writing it. Because
it is fast, we can build three toys in 20 minutes and show students more than one "best practice"
(starting from something that works and asking for one small change).

## What's inside

| Path | What it is |
| --- | --- |
| `index.html` | The 9-slide deck. Arrow keys / Space to move, `N` for speaker notes. |
| `demo/index.html` | Gallery hub linking the three finished toys. |
| `demo/piano/index.html` | Banana Piano (easy) — keyboard-playable, Web Audio notes (no sound files). |
| `demo/simon/index.html` | Memory Game (medium) — Simon Says on the four arrow pads, Web Audio tones. |
| `demo/catch/index.html` | Catch & Dodge (challenge) — arrow-key basket catches fruit and dodges bombs, with score and lives. |
| `handout/index.html` | One-page printable student handout with all three prompts. |
| `notes/speaker-notes.md` | Per-slide talking points with minute-by-minute timing. |
| `assets/` | Brand tokens, deck styles, navigation script, logo + halftone art. |

## Present it

1. Open `index.html` in a browser and press `F` (or your browser's full-screen).
2. Navigate: **Arrow keys**, **Space**, or **Page Up/Down**. `Home` / `End` jump to first / last.
3. Press **N** to show speaker notes with the timing for the current slide. `Esc` hides them.
4. On each build slide, the orange button opens the finished toy as a reliable backup if Claude is slow
   or blocked on the school network.

The three build-along prompts (kept short on purpose), rising from easy to challenge:

> **1 · Banana Piano (easy)** — Make a fun web-page piano. When I press Space, the arrow keys, or
> W A S D F G, play a different musical note and flash a big colourful button for that key. Make it
> work with a normal keyboard.

> **2 · Memory Game (medium)** — Make a memory game like Simon Says. Show four big coloured pads for
> the Up, Down, Left and Right arrow keys, each with its own sound. Flash a sequence of pads that gets
> one longer each round, and I repeat it with the arrow keys. Show the round number, and say game over
> if I press the wrong one. Make it work with a normal keyboard.

> **3 · Catch & Dodge (challenge)** — Make a simple web game. Good fruit and bombs fall from the top.
> I move a basket with the Left and Right arrow keys to catch the fruit for points but dodge the bombs.
> Catching a bomb costs a life, and the game speeds up over time. Show the score and lives. Make it
> work with a normal keyboard.

## Deploy to GitHub Pages

1. Create a new GitHub repository and push this folder to the `main` branch.
2. In the repo: **Settings -> Pages**.
3. Under **Build and deployment**, set **Source: Deploy from a branch**, **Branch: `main` / `(root)`**,
   then **Save**.
4. After a minute the site is live:
   - Slides: `https://<user>.github.io/<repo>/`
   - Demos: `https://<user>.github.io/<repo>/demo/`
   - Handout: `https://<user>.github.io/<repo>/handout/`

A `.nojekyll` file is included so the `assets/` and `demo/` folders are served unchanged.

## Notes

- Fonts (Anton, DM Sans, JetBrains Mono) load from Google Fonts; everything degrades to system fonts
  offline. To go fully offline, self-host the `woff2` files and swap the `<link>` for a local
  `@font-face` block.
- No emoji, English copy, designed to run under 20 minutes.

---

Built by Chan Meng · [chanmeng.org](https://chanmeng.org) · [github.com/ChanMeng666](https://github.com/ChanMeng666)
