# Intro

This repo contains scripts that install firefox into `~/.local/share/firefox` with .desktop file intergration and a symlinked executable in `~/.local/bin` This is an alternative to the Flatpak or distro package. It is not sandboxed and it is not mixed with system files. These scripts don't even require root privleges.

## Installation

Pick a version then run it in the terminal

### Regular

```bash
wget https://raw.githubusercontent.com/dnkmmr69420/Firefox-for-Linux-scripts/main/firefox && chmod +x ./firefox && ./firefox ; rm -f ./firefox
```

### Beta

```bash
wget https://raw.githubusercontent.com/dnkmmr69420/Firefox-for-Linux-scripts/main/firefox-beta && chmod +x ./firefox-beta && ./firefox-beta ; rm -f ./firefox-beta
```

### Dev

```bash
wget https://raw.githubusercontent.com/dnkmmr69420/Firefox-for-Linux-scripts/main/firefox-dev && chmod +x ./firefox-dev && ./firefox-dev ; rm -f ./firefox-dev
```

### ESR

```bash
wget https://raw.githubusercontent.com/dnkmmr69420/Firefox-for-Linux-scripts/main/firefox-esr && chmod +x ./firefox-esr && ./firefox-esr ; rm -f ./firefox-esr
```

### Nightly

```bash
wget https://raw.githubusercontent.com/dnkmmr69420/Firefox-for-Linux-scripts/main/firefox-nightly && chmod +x ./firefox-nightly && ./firefox-nightly ; rm -f ./firefox-nightly
```

## Dependencies

- wget (static binary if wget is not preinstalled https://github.com/yunchih/static-binaries/blob/master/wget)

- glibc 2.17 or higher

- GTK+ 3.14 or higher

- libglib 2.42 or higher

- libstdc++ 4.8.1 or higher

- X.Org 1.0 or higher (1.7 or higher is recommended)

