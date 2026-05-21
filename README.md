# edu-neo-candy-arc-mint-grey

Mint-grey variant of the Neo-Candy Arc icon family — colourful icons in a cool grey palette tuned to pair with Mint-style Arc GTK themes. Part of the `~/EDU/` Neo-Candy series.

## What's in this repo

- `usr/share/icons/` — the icon theme assets.
- `setup.sh`, `up.sh` — standard EDU bash scaffold.

## Sibling variants

- [edu-neo-candy-arc](https://github.com/erikdubois/edu-neo-candy-arc)
- [edu-neo-candy-arc-mint-red](https://github.com/erikdubois/edu-neo-candy-arc-mint-red)
- [edu-neo-candy-qogir](https://github.com/erikdubois/edu-neo-candy-qogir)
- [edu-neo-candy-tela](https://github.com/erikdubois/edu-neo-candy-tela)

## Installation

### From `nemesis_repo` (recommended)

```ini
[nemesis_repo]
SigLevel = Never
Server = https://erikdubois.github.io/$repo/$arch
```

```bash
sudo pacman -Syu
sudo pacman -S edu-neo-candy-arc-mint-grey
```

### Manual

```bash
git clone https://github.com/erikdubois/edu-neo-candy-arc-mint-grey.git
cd edu-neo-candy-arc-mint-grey
sudo cp -r usr/share/icons/. /usr/share/icons/
sudo gtk-update-icon-cache -f /usr/share/icons/<theme-folder>
```

### Activate

```bash
gsettings set org.gnome.desktop.interface icon-theme "<theme-folder-name>"
```

## Websites

Information : https://erikdubois.be

## Social Media

Youtube : https://www.youtube.com/erikdubois

## License

See [LICENSE](./LICENSE).
