# melikechan's Setup

The repository is about my computer setup. I decided to create a repository about my setup because I usually get confused about what to install/what to use after a clear installation, so better to create a list about it.

## My OS/Distro

- I use Linux as my primary and only OS.
- My distro is Arch Linux. _Sometimes I think about building my custom one Linux From Scratch but I don't have time for now. (as 21.04.2023, I still don't have time)_

### Bootloader

- I use [GRUB](https://wiki.archlinux.org/title/GRUB) as my bootloader.

### GRUB Config

When I fresh setup Arch Linux in need, I just follow the instructions on [Arch Wiki](https://wiki.archlinux.org/title/GRUB) and generate [grub.cfg](https://wiki.archlinux.org/title/GRUB#Generated_grub.cfg) following the instructions there.

**NOTE: As the only OS is Arch Linux on my machine, I just generate the main configuration file.**

### Shell

- I use zsh with [powerlevel-10k](https://github.com/romkatv/powerlevel10k).

My dotfiles can be found [here](https://github.com/melikechan/dotfiles/zsh) (not uploaded yet)

### DE/WM

#### My Previous Setup (GNOME)

- I used GNOME as my DE and its built-in WM, Mutter.
- I sometimes use i3-gaps + GNOME too. _(i3-gaps is now merged with i3, thus it is deprecated)_

You can find more information about my old GNOME setup in [gnome-setup.md](gnome-setup.md)

#### My Current Setup (i3)

- I use Polybar as my status bar.
  - I tried to create my own status bar theme from scratch but it was a bit hard for me. Instead, I decided to use [polybar-themes](https://github.com/adi1090x/polybar-themes) and customized a theme to use in my daily setup. You can find my customized theme in [dotfiles](#my-current-setup-i3).
- I use rofi or dmenu as my application launcher. _(but I use dmenu more than rofi.)_
- I use feh as my wallpaper setter.
- I use Thunar as my file manager.
- I use Alacritty as my terminal emulator.

## TODO

- [ ] Add dotfiles to the dotfiles repository.
- [ ] Add screenshots of my setup.
- [ ] Add more information about my setup and how to install/use them.
