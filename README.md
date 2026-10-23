# Pi & Qwen

Slides for a workshop on **local, sovereign AI coding agents**: approaches and strategies for agentic coding with the [Pi](https://github.com/earendil-works/pi) coding agent and **Qwen3.8-27B**, running entirely on a laptop.

**▶ View the slides: [billdx.github.io/Pi-Qwen](https://billdx.github.io/Pi-Qwen/)**. Use the arrow keys or click to move through them, G to see every slide, N for the speaker notes, and F for full screen. Add `#5` to the address to open slide 5. On a phone the slides scroll.

The deck is *Pi on a local model: a field guide for Claude Code users* (Bill McIntyre, October 2026). It is written for developers who use Claude Code with a frontier model every day. It covers what it takes to get a 27B open-weight model to work as a coding agent, where the local setup holds up and where it doesn't, and the choices that make it as seamless as it can be.

## What the workshop covers

| # | Section | Slides |
|---|---|---|
| 1 | Before we start | 01 Pi on a local model · 02 Cheat sheet: zero to a local agent · 03 What you keep, and what you trade |
| 2 | The model | 04 Why a 27B when giants are a click away · 05 What makes Qwen3.8-27B stand out |
| 3 | The runtime | 06 Two engines: LM Studio vs MTPLX |
| 4 | Pi as a coding environment | 07 Pi next to Claude Code · 08 What it is like to drive |
| 5 | Making pi safe | 09 Claude Code's safety, in four layers · 10 A host sandbox with pi-sandbox |
| 6 | Utility | 11 Keep the always-on prompt small · 12 What I actually keep in there |
| 7 | Customizing pi | 13 Hotrod mods: eight worth a look · 14 Four neat pi tricks |
| 8 | Prompting smaller models | 15 Red, then green: tests drive the run · 16 Live within a smaller window · 17 Prompt habits that suit a 27B |
| 9 | Getting started | 18 Your first evening · 19 Links worth keeping · 20 My settings and configuration · 21 Take it, change it, pass it on (license) |

New to this? Start with slide 02, the cheat sheet: every install step with its command, plus the three AGENTS.md lines, settings and skills worth having on day one.

## Repository layout

```
index.html       the slide viewer published with GitHub Pages
deck/
  deck.json        slide order, sections and fonts
  slides/<id>.html one file per slide; speaker notes are in each slide's <aside>
  images/          the pi screenshots used on slide 13
```

Each slide is a 1920 × 1080 HTML fragment with inline styles. The deck was built with Claude's Slides artifact and the Formwerk design system: primary inks on cream stock, with geometric shapes and print quirks. Its fonts are Jost, Bitter and Space Mono from Google Fonts.

## About the numbers

- **My measurements:** speeds, task results and timings come from my own runs on a MacBook Pro M3 Max with 96 GB, in September and October 2026. They used pi with MTPLX and LM Studio.
- **Published scores:** benchmark figures come from Artificial Analysis and the Qwen3.8-27B model card.

Each slide's footer gives its source and date.

## License

Copyright © 2026 Bill McIntyre.

This deck and everything in this repository are licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/) (CC BY-SA 4.0). The full text is in [LICENSE](LICENSE).

You are free to share, adapt and present this material, including for commercial workshops, as long as you:

- **Give credit:** name Bill McIntyre as the author, link to this repository and the license, and say if you made changes.
- **Share alike:** release your adapted version under CC BY-SA 4.0 or a compatible license.

Quotations, benchmark figures, product names and screenshots of third-party software belong to their respective owners. They are included here for commentary and are not covered by this license.
