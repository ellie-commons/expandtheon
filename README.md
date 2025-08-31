# Expandtheon 

![Obsidian](./apps/48/obsidian.svg)
![Alacritty](./apps/48/alacritty.svg)
![Discord](./apps/48/discord.svg)
![Slack](./apps/48/slack.svg)
![Zotero](./apps/48/zotero.svg)
![Ghostty](./apps/48/ghostty.svg)
![WezTerm](./apps/48/wezterm.svg)
![Zen Browser](./apps/48/zen-browser.svg)

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
