tt-rss-feedly-theme
===================

Feedly theme for [Tiny Tiny RSS](https://tt-rss.org) 1.15 – 18.8. This theme will probably not be updated to support newer versions of tt-rss.

The latest fully working tt-rss commit of version 18.8 is [da1a3c2](https://git.tt-rss.org/fox/tt-rss/commit/da1a3c2cc5621bccdb844cfbd03e377ada079fa9). After that, things start to fall apart.

If you are on version 18.12 or newer, this theme will not work. Until tt-rss commit [f679ec2](https://git.tt-rss.org/fox/tt-rss/commit/f679ec2e6e25598c511177d7d160c51d2bdf631e), you can try the [branch v18.12](https://github.com/levito/tt-rss-feedly-theme/tree/v18.12). Later commits include a new dojo base theme and will break badly!

Use the [legacy branch](https://github.com/levito/tt-rss-feedly-theme/tree/legacy) for TT-RSS 1.11 or older.

Use the [branch v1.12](https://github.com/levito/tt-rss-feedly-theme/tree/v1.12) if you use version 1.12 up to 1.14.

For the best experience, use a current browser. IE9 and older versions are not supported.

This theme is tested in Chrome on a regular basis and should work fine in IE10 and recent versions of Safari, Firefox (28+) and Opera (15+) as well.

## Installation

**Prerequisites:** Running instance of TT-RSS

Install steps (If you did not find the description on the [TT-RSS Homepage](https://git.tt-rss.org/git/tt-rss/wiki/Themes)):

1. Download the ZIP-File: `wget https://github.com/levito/tt-rss-feedly-theme/archive/master.zip`
2. Unzip the ZIP-File: `unzip master.zip`
3. Change into the newly created folder: `cd tt-rss-feedly-theme-master`
4. Copy the relevant files into your TT-RSS folder:

    * `cp feedly.css feedly-night.css [TT-RSS_Home]/themes.local`
    * `cp -r feedly/ [TT-RSS_Home]/themes.local`

5. Go into your TT-RSS preferences and select the feedly-theme.

## Screenshots

![expandable](https://raw.github.com/levito/tt-rss-feedly-theme/master/feedly-screenshots/feedly-expandable.png?130826)

![expanded](https://raw.github.com/levito/tt-rss-feedly-theme/master/feedly-screenshots/feedly-expanded.png?130826)

![traditional](https://raw.github.com/levito/tt-rss-feedly-theme/master/feedly-screenshots/feedly-traditional.png?130826)

![traditional, wide, hidden sidebar](https://raw.github.com/levito/tt-rss-feedly-theme/master/feedly-screenshots/feedly-traditional-widescreen.png?130826)

![preferences + layer](https://raw.github.com/levito/tt-rss-feedly-theme/master/feedly-screenshots/feedly-prefs-layer.png?130826)

Licensed under the WTFPL
