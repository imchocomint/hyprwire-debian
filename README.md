# hyprwire-debian
Mirror of https://salsa.debian.org/hyprland-team/hyprwire

Used for hyprplus when hyprwire is not available in the repo. Packages to six .deb files.

## Build
`gbp buildpackage -us -uc --git-ignore-new` inside cloned directory.

## Install
`sudo dpkg -i *.deb` inside cloned folder after building.
