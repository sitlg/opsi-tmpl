# Scratch Link

This package installs Scratch Link.

> Scratch Link allows you to connect hardware to interact with your Scratch projects.

## Installer

[Direct download](https://downloads.scratch.mit.edu/link/windows.zip)

Copy extraxted installer into `data` directory of package.
Make sure that the name is `ScratchLinkSetup.msi`.

## Usage

- Replace the `logo.png.txt` file with an actual image in PNG format with the name `logo.png`
- Activate logo in `install.ins` file
- Copy package to server into `/srv/deploy/install`
- Run `chkdeploy` as root

## Notes

Test with `ymdn011793`
Port 20111
