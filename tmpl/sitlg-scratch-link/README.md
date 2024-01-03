# Scratch Link

This package installs Scratch Link.

> Scratch Link allows you to connect hardware to interact with your Scratch projects.

| Name             | Scratch Link |
|------------------|--------------|
| Pkg version      | 0.1          |
| Software version | 1.4.3        |

## Installer

[Direct download](https://downloads.scratch.mit.edu/link/windows.zip)

Copy extracted installer into `data` directory of package.
Make sure that the name is `ScratchLinkSetup.msi`.

## Usage

- Replace the `logo.png.txt` file with an actual image in PNG format with the name `logo.png`
- Activate logo in `install.ins` file
- Copy package to server into `/srv/deploy/install`
- Run `chkdeploy` as root

## Notes

Test with `ymdn011793`
TODO: Port 20111
