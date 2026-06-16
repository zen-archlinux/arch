# Zen Browser Arch Linux Repository

To use this repo, add the following to your `/etc/pacman.conf`:

```
[zen-browser]
SigLevel = Never
Server = https://zen-archlinux.github.io/arch
```
or run this:

```bash
echo -e '[zen-browser]\nSigLevel = Never\nServer = https://zen-archlinux.github.io/arch' | sudo tee -a /etc/pacman.conf
```

## PKGs 
 * `zen-browser-bin` (stable)
 * `zen-browser-twilight-bin` (twilight)

> pacman -Sy zen-browser
