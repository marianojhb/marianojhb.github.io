# Machine Room visual system

- **World:** A dark industrial observatory: ink-black surfaces, oxidized green linework, and phosphor-acid signals. The machine is authored as SVG rather than a decorative image so its gears can respond to scroll.
- **Typography:** Barlow Condensed carries display headlines and DM Mono carries system labels, metadata, and body copy.
- **Composition:** One continuous vertical experience. The hero establishes the mechanical core; the work section holds one project card at center and swaps its active state as scroll advances; contact is a quiet final chamber.
- **Motion:** Gears rotate continuously, the central core glows, and project cards crossfade/translate as the scroll position changes. `prefers-reduced-motion` disables continuous gear animation and card transitions.
- **Color tokens:** `#060907` black, `#0c110d` panel, `#253129` line, `#edf3e9` text, `#b7ff45` signal, `#ff7a4a` offline/caution.
- **Content rule:** Project cards and contact details use facts and links from `github.com/marianojhb/marianojhb`; update them when that profile changes.
