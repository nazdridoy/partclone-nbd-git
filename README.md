# partclone-nbd-git
An AUR package for [partclone-nbd](https://github.com/allvpv/partclone-nbd) - Export partclone/clonezilla images as block devices without restoring them.


## Description

This package provides a Network Block Device (NBD) server that allows you to mount Partclone/Clonezilla images as block devices without the need to restore them first. This is particularly useful for:

- Quick inspection of image contents
- Mounting images for data recovery
- Testing images without full restoration
- Accessing specific files from backup images

## Installation
### Manual

```bash
git clone https://aur.archlinux.org/partclone-nbd-git.git
cd partclone-nbd-git
makepkg -si
```

### With AUR helper (paru/yay)

#### With yay
```bash
yay -S  partclone-nbd-git
```

#### With paru

```bash
paru -S  partclone-nbd-git
```
### Dependencies

- Required:
  - `glibc`
  - `git` (make)
  - `cmake` (make)

- Optional:
  - `partclone`: for creating compatible disk images
  - `clonezilla`: for creating compatible disk images
