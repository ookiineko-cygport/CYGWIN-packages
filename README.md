# CYGWIN-packages

Package scripts for CYGWIN.

To build these, run `makepkg -sCLf` in the package directory from the bash prompt.
Appropriate packages from the Cygwin are implicit build time and runtime dependencies.
Make sure they are installed before attempting to build the corresponding package.

To install the built package(s).

    pacman -U ${package-name}*.pkg.tar.xz

## TODOs

- [ ] Document required Cygwin packages for building/running every pacman package
- [ ] Provide prebuilt packages

## See also

### Wiki

[This page](../../wiki/Getting-started) explains how you can build & install pacman from scratch.

It is useful when you don't have pacman installed on your Cygwin system and you don't know how to get one.

### Special thanks

This repository is based on the [MSYS2-packages][MSYS2-packages].

## License

CYGWIN-packages is licensed under BSD 3-Clause "New" or "Revised" License.
A full copy of the license is provided in [LICENSE](LICENSE).

[MSYS2-packages]:https://github.com/msys2/MSYS2-packages.git

