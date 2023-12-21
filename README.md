# OPSi Templates

OPSi templates for usage with IServ

## Usage

Templates do **NOT** contain data files, as these would not make sense to track in version control.

### Quickstart

- (Optional) Clone this repo
- Copy any folder from the `tmpl` directory to make changes
  - Some templates can be used as is, but most require you to add files to the `data` folder (consult the `README.md` of the template) and make edits based on these files
- Copy edited folder to your server in `/srv/deploy/install`
- Make sure that the name of the package directory and product id in the `control` file are the same. Otherwise the package will be ignored.
- Run `chkdeploy` to update local package registry and make the server aware of the new package

### Troubleshooting

Installation logs can befound in IServ in `Verwaltung > Netzwerk > Geräte > [Gerät] > Programme > Protokolle`.
That's where you can find any errors the OPSi script might have produced.

## Templates

- default-program-registry-patch

## Development

### References

[Cookbook](https://docs.opsi.org/opsi-docs-en/4.3/opsi-script-manual/cook-book.html)

## License

None
