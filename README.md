# Omni for [Alacritty](https://github.com/alacritty/alacritty)

> 🎨 Omni is everywhere [Alacritty](https://github.com/alacritty/alacritty)

![Screenshot](.github/alacritty.png)

## Installation Instructions

If you've already configured your `~/.config/alacritty/alacritty.yml`:

1. Open the file in a text editor.

```bash
$ code ~/.config/alacritty/alacritty.yml
```

2. Replace the colors sessions of your config with:

```yaml
colors:
  primary:
    background: "0x191622"
    foreground: "0xE1E1E6"

  cursor:
    text: "0x41414D"
    cursor: "0xE1E1E6"

  selection:
    text: "0xE1E1E6"
    background: "0x41414D"

  normal:
    black: "0x000000"
    red: "0xE96379"
    green: "0x67E480"
    yellow: "0xE7DE79"
    blue: "0x988BC7"
    magenta: "0xFF79C6"
    cyan: "0x78D1E1"
    white: "0xbfbfbf"

  bright:
    black: "0x4d4d4d"
    red: "0xff6e67"
    green: "0x5af78e"
    yellow: "0xf4f99d"
    blue: "0xcaa9fa"
    magenta: "0xff92d0"
    cyan: "0x9aedfe"
    white: "0xe6e6e6"

  dim:
    black: "0x14151b"
    red: "0xff2222"
    green: "0x1ef956"
    yellow: "0xebf85b"
    blue: "0x4d5b86"
    magenta: "0xff46b0"
    cyan: "0x59dffc"
    white: "0xe6e6d1"

  indexed_colors: []
```

If you don't have an alacritty config file, then:

1. Clone the repo locally and open it:

```bash
$ git clone https://github.com/librity/omni-alacritty.git
$ cd omni-alacritty
```

1. Create a config directory `~/.config/alacritty/`, then copy the config file into it:

```bash
$ mkdir  ~/.config/alacritty/
$ cp alacritty.yml ~/.config/alacritty/
```
