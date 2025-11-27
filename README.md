# Expandtheon 

![Obsidian](./apps/48/obsidian.svg)
![Alacritty](./apps/48/alacritty.svg)
![Discord](./apps/48/discord.svg)
![Slack](./apps/48/slack.svg)
![Zotero](./apps/48/zotero.svg)
![Ghostty](./apps/48/ghostty.svg)
![WezTerm](./apps/48/wezterm.svg)
![Zen Browser](./apps/48/zen-browser.svg)
![LibreOffice Start Center](./apps/48/libreoffice.svg)
![LibreOffice Base](./apps/48/libreoffice-base.svg)
![LibreOffice Calc](./apps/48/libreoffice-calc.svg)
![LibreOffice Draw](./apps/48/libreoffice-draw.svg)
![LibreOffice Impress](./apps/48/libreoffice-impress.svg)
![LibreOffice Math](./apps/48/libreoffice-math.svg)
![LibreOffice Writer](./apps/48/libreoffice-writer.svg)

A vector icon theme that brings third-party support to elementary OS and it's
desktop environment, Pantheon.

This theme is designed to be installed on top of and extend the regular [icons theme](https://github.com/elementary/icons) for elementary OS.

  <a href="https://elementary.io">
    <img src="https://ellie-commons.github.io/community-badge.svg" alt="Made for elementary OS">
  </a>

## Building and Installation

You'll need the following dependencies:

* meson

Run `meson` to configure the build environment and then `ninja` to build

    meson build --prefix=/usr
    cd build
    ninja

To install, use `ninja install`

    sudo ninja install
