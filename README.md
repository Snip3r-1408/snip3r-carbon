# snip3r.de Carbon

> A dark carbon-fibre cockpit for [YourEliteSystems/WebRadio](https://github.com/YourEliteSystems/WebRadio).

**snip3r.de Carbon** is a high-contrast theme for listeners who prefer their player quiet, technical, and unmistakably theirs. It combines a near-black base with a woven 2×2 twill carbon pattern, restrained ultraviolet highlights, and a single animated spectrum runner that circles the window perimeter.

The design keeps the music at the centre: no glowing panels everywhere, no washed-out greys. Just a dark surface, precise contrast, and a little energy at the edge.

## Highlights

- **Woven carbon fibre** — a bitmap-free 2×2 twill texture across the title bar, sidebar, cards, and player bar.
- **Low-glare midnight palette** — near-black backgrounds designed for long listening sessions.
- **Electric accents** — indigo and violet actions remain easy to spot without overpowering the interface.
- **Rainbow Runner** — a slim, clockwise spectrum flash travels around the edge of the window.
- **Maker's mark** — a subtle `BY SNIP3R` watermark sits behind the content area.
- **Zero extra assets** — the theme is one stylesheet and one manifest; no fonts, images, or dependencies required.

## The story

This theme started with a simple question: *what would a radio player look like if it felt less like a dashboard and more like a machine?*

Carbon fibre became the answer. It is dark, lightweight, technical, and only reveals its character when light catches it at the right angle. The pattern in this theme follows the same principle: present enough to give every surface depth, subtle enough to leave the station artwork and the music in charge.

The violet controls evoke a quiet electrical current through that material. The Rainbow Runner is the one deliberate break from restraint — a pulse circling the enclosure, like a live signal moving through the system. The result is called **snip3r.de Carbon**: dark by default, detailed by design, and built for people who enjoy the atmosphere around their sound as much as the sound itself.

## Installation

1. Download or clone this repository.
2. Copy the complete `snip3r-carbon` folder into WebRadio's user theme directory:

   - **Linux:** `~/.config/webradio/themes/`
   - **Windows:** `%APPDATA%/webradio/themes/`
   - **macOS:** `~/Library/Application Support/webradio/themes/`

3. Restart WebRadio, open the theme selector, and choose **snip3r.de Carbon**.

The final directory must look like this:

```text
themes/
└── snip3r-carbon/
    ├── theme.json
    └── style.css
```

> **Note:** WebRadio builds must load both bundled and user-installed theme directories. If the theme is not listed, update to a release containing user-theme discovery support.

## Compatibility

Designed for the current Electron/React-based WebRadio theme engine. It uses standard CSS, CSS gradients, and inline SVG; no external network request is made.

## Customisation

The top of [`style.css`](style.css) exposes the main colour variables. The fastest personal variations are:

- Change `--accent-color` for a different primary glow.
- Change the Rainbow Runner's SVG gradient stops to use a single colour family.
- Remove the `#app::after` rule for a completely static, stealth look.
- Edit `.content::before` to replace or remove the background watermark.

## Credits

Created by [snip3r.de](https://snip3r.de) for the WebRadio community. WebRadio itself is maintained by [Your Elite Systems](https://github.com/YourEliteSystems/WebRadio).

## License

Released under the [MIT License](LICENSE).
