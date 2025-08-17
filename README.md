# Shirewear
## A Hugo theme inspired by Hobbit fashion

**Shirewear** is a warm, earthy, and elegant blog theme for [Hugo](https://gohugo.io/), inspired by the clothing stlye, fashion & general coziness described in J.R.R. Tolkiens novels.

With a palette of soft browns, muted greens, and warm yellows, Shirewear provides a comforting reading experience, just before the second breakfast.

<p align="center">
  <img src="images/shirewear_palette.png" alt="screenshot" width="200">
</p>

## Screenshots

[coming soon]

## Running the example page

```bash
git clone https://github.com/yourname/my-hugo-theme.git
cd my-hugo-theme
hugo server -s exampleSite/ -t ../..
```

## Installation

1. **Adding the theme to a Hugo site**
From the root of the hugo site:
```bash
git submodule add https://github.com/MaxAlex42/shirewear themes/shirewear
```

Or clone the repository directly:
```bash
git clone https://github.com/MaxAlex42/shirewear themes/shirewear
```

2. **Enable the theme in the config.toml**
```toml
theme = "shirewear"
```
## Changing the About page

The about pages live under the localized content folders, if one wants multlingual options:
```bash
content/en/about/about.md
or
content/de/about/about.md
```

About pages need to have the "about" type in their preamble:
```yaml
---
title: "About"
type: "about" # <- this is the important flag that is mandatory for it to be correctly recognised
draft: false
---
```

### About page layout customization

The layout for the About page lives under:
```bash
layouts/about/single.html
```

## License

MIT - Feel free to adapt and modify the theme as you wish.
