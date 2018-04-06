## Description

cherry is yet another bitmap font, made for latin 1 

## Screenshots

[10px](https://cdn.rawgit.com/marinhoc/cherry-font/master/img/10.png)

[11px](https://cdn.rawgit.com/marinhoc/cherry-font/master/img/11.png)

[13px](https://cdn.rawgit.com/marinhoc/cherry-font/master/img/13.png)

## Installation

#### Arch

[AUR package](https://aur.archlinux.org/packages/cherry-font/)

#### X11

```shell
$ ./make.sh
$ mv *.pcf /path/to/cherry-font/out # example : ~/.fonts
$ mkfontdir /path/to/cherry-font/out
$ xset +fp /path/to/cherry-font/out # every time X starts
```

#### Fontconfig

```shell
$ ./make.sh
$ mv *.pcf /path/to/cherry-font/out # must be a directory scanned by fontconfig
$ fc-cache -fv
```
