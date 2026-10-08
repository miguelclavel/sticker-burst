# Sticker Burst

A name that bursts into stickers when you click it, from my second portfolio.

<img src="assets/demo.gif" width="720" alt="A name that bursts into stickers when you click it: a screen recording">

**[Try it live](https://miguelclavel.github.io/sticker-burst/)** · one file, `index.html`, no libraries, no build step.

Click my name on my second portfolio and it explodes into stickers.

Every click spawns a handful of small shapes right where you clicked. Each one flies off in its own random direction, spins as it goes, gets pulled down like real gravity, and fades out over about a second. No two clicks throw the pieces the same way.

Here's a prompt that gets you the mechanic:

Small interaction, but it's the kind of thing that makes people click something twice just to watch it happen again.

## Use it on your site

Copy the `.sticker` style and the script from `index.html`, and change `#name` to the element you want to burst. Drop your own images into `IMAGES` (left empty, each sticker is a coloured shape), and tune `COUNT`, `GRAVITY` and `LIFE` at the top. It also bursts on Enter or Space for keyboard users, and calms down to a few stickers for people who prefer reduced motion.

## Or build your own from the prompt

Copy it as it is and paste it into Claude, or any AI coding tool.

```text
When an element is clicked, spawn a handful of small particles at the click position. Give each one a random direction and speed, a random spin, and a downward pull like gravity, so they arc instead of flying in a straight line. Fade each one out over about a second and remove it from the page once it's gone.
```

More like this in [interaction-recipes](https://github.com/miguelclavel/interaction-recipes).

---

MIT licensed. Made by [Miguel Clavel](https://miguelclavel.com/?utm_source=github&utm_medium=sticker-burst) with Claude Code. If you build one of these, send it to me. I'd genuinely like to see it.
