# Pi & Qwen

Slides for a workshop on **local, sovereign AI coding agents**: approaches and strategies for agentic coding with the [Pi](https://github.com/earendil-works/pi) coding agent and **Qwen3.8-27B**, running entirely on a laptop.

The deck is *Pi on a local model: a field guide for Claude Code users* (Bill McIntyre, October 2026). It is written for developers who use Claude Code with a frontier model every day. It covers what it takes to get a 27B open-weight model to work as a coding agent, where the local setup holds up and where it doesn't, and the choices that make it as seamless as it can be.

## What the workshop covers

| # | Section | Slides |
|---|---|---|
| 1 | Before we start | 01 Pi on a local model · 02 What you keep, and what you trade |
| 2 | The model | 03 Why a 27B when giants are a click away · 04 What makes Qwen3.8-27B stand out |
| 3 | The runtime | 05 Two engines: LM Studio vs MTPLX |
| 4 | Pi as a coding environment | 06 Pi next to Claude Code · 07 What it is like to drive |
| 5 | Making pi safe | 08 Claude Code's safety, in four layers · 09 A host sandbox with pi-sandbox |
| 6 | Utility | 10 Keep the always-on prompt small · 11 What I actually keep in there |
| 7 | Customizing pi | 12 Hotrod mods: eight worth a look · 13 Four neat pi tricks |
| 8 | Prompting smaller models | 14 Red, then green: tests drive the run · 15 Live within a smaller window · 16 Prompt habits that suit a 27B |
| 9 | Getting started | 17 Your first evening · 18 Links worth keeping · 19 My settings and configuration |

## Repository layout

```
deck/
  deck.json        slide order, sections and fonts
  slides/<id>.html one file per slide; speaker notes are in each slide's <aside>
  images/          the pi screenshots used on slide 13
```

Each slide is a 1920 × 1080 HTML fragment with inline styles. The deck was built with Claude's Slides artifact and the Presswerk design system. Its fonts are Jost, Courier Prime and Libre Caslon Text from Google Fonts.

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
