# Default program registry patch

This package allows for setting a key in the registry for the purpose of configuring a default program.
The specific example sets the key for default program that open the file type `.pdf`

## Usage

- Replace the `logo.png.txt` file with an actual image in PNG format with the name `logo.png`
- Research the registry key you want to change and edit the `install.ins` and `remove.ins` files accordingly
  - Keep in mind that this program actually needs to be installed to make this change usable
