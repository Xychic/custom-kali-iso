# Custom Kali ISO

A custom Kali Linux ISO configuration that can be built using [kali-live-build-config](https://gitlab.com/kalilinux/build-scripts/live-build-config)

## What's Included
- `kali-linux-everything` meta-package
- [`PEASS-ng`](https://github.com/carlospolop/PEASS-ng)
- Custom desktop layout & wallpaper
- A bunch of other nice-to-haves (see [package list](package-lists\kali.list.chroot))

## How to Build

### Native Debian

- Clone the [kali-live-build-config](https://gitlab.com/kalilinux/build-scripts/live-build-config) repository.
- Clone this repository into the `kali-config` directory within the cloned repository.
- Run `./build.sh --debug --variant custom` which will create a iso within the `images` directory

### Other Linux Distributions

- Clone [live-build-docker](https://github.com/Xychic/live-build-docker)
- Follow the instructions in the README
