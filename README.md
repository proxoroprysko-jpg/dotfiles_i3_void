# .dotfiles | Void Linux + i3wm

My minimal, keyboard-driven setup built around the **KISS principle** (Keep It Simple, Stupid). No digital clutter, no background bloat, and no animation lag. It just gets out of the way and works, using around 8% of RAM on idle.

---

## 🛠️ The Core Stack

* **OS:** [Void Linux](https://voidlinux.org/) (Independent, systemd-free, lightning-fast `xbps`)
* **WM:** `i3wm` (Pure tiling efficiency, fully customized via keyboard shortcuts)
* **Terminal:** `Kitty` (GPU-accelerated, handles graphics natively, very snappy)
* **Shell:** `Zsh` (Enhanced with `zsh-autosuggestions` to save keystrokes)
* **Bar:** `Polybar` (Clean status bar tailored with a subtle purple aesthetic)
* **File Manager:** `Thunar` (Lightweight XFCE file manager, kept purely for convenience)
* **Editor:** `Neovim` (The single tool for everything: configs, code, and quick notes)
* **Font:** `Iosevka NF` (A sharp, condensed font that maximizes screen real estate)

---

## 🎨 Design Philosophy & Quirks

* **Hardware Volume Control:** No audio mixer daemons running in the background. Volume is managed entirely via physical dials on my headphones and speakers.
* **Manual Mounting:** Zero auto-mounting services. It's just a quick `sudo mount` in the terminal when a flash drive is actually needed. 
* **Static Visuals:** Everything is static. Purple mountain wallpaper, standard `xset` display timeouts, and a customized SDDM login screen using the Sugar Candy theme.
* **Zero Waste:** No "rice aesthetic" bloatware or terminal matrices installed just for screenshots. Every single utility here has a daily practical purpose.

---

## 🚀 Quick Replication

A quick reminder for myself (or anyone else) on how to deploy this setup on a fresh machine:

1. Clone the repo:
   ```bash
   git clone [https://github.com/proxoroprysko-jpg/dotfiles_i3_void.git](https://github.com/proxoroprysko-jpg/dotfiles_i3_void.git) ~/dotfiles
