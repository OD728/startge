# ~/startpage

A minimal browser startpage with a terminal aesthetic.

![preview](startpage.gif)

## Features

- Categorized bookmarks
- Live clock with date
- Blinking cursor animation
- Custom `> _` favicon
- [Catppuccin Mocha](https://github.com/catppuccin/catppuccin) color scheme

## Fonts

- [Fira Code](https://fonts.google.com/specimen/Fira+Code) — body & clock
- [Share Tech Mono](https://fonts.google.com/specimen/Share+Tech+Mono) — heading

Both loaded via Google Fonts, no install needed.

## Usage

Clone or download the repo, then open `index.html` in your browser. Set it as your browser's homepage or use an extension like [New Tab Redirect](https://chromewebstore.google.com/detail/new-tab-redirect/icpgjfneehieebagbmdbhnlpiopdcmna).

```
git clone https://github.com/yourusername/startpage
```

## Customization

Edit the bookmark links directly in `index.html`. Colors are all CSS variables in `style.css`:

```css
--color-bg:           var(--ctp-base);
--color-fg:           var(--ctp-text);
--color-link:         var(--ctp-subtext0);
--color-link-visited: var(--ctp-lavender);
--color-link-hover:   var(--ctp-mauve);
```

Swap any `--ctp-*` token to change the accent. Available: `--ctp-blue`, `--ctp-teal`, `--ctp-green`, `--ctp-peach`, `--ctp-pink`, `--ctp-mauve`.

## Credits

[Cat GIF artist Avogado6](https://x.com/avogado6/status/1165595520967954432)

[Startpage from kencx](https://github.com/kencx/startpage)