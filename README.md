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

### Source

Get source of specific tag with

```
$ wget https://github.com/sitlg/opsi-tmpl/archive/refs/tags/<tag>.{tar.gz,zip}
```

### Troubleshooting

Installation logs can befound in IServ in `Verwaltung > Netzwerk > Geräte > [Gerät] > Programme > Protokolle`.
That's where you can find any errors the OPSi script might have produced.

## Templates

- sitlg-3d-modellbahn-studio
- sitlg-regpatch-pdf
- sitlg-scratch-link

## Development

### References

- [Packaging Tutorial](https://docs.opsi.org/opsi-docs-en/4.2/getting-started/packaging-tutorial.html)
- [Cookbook](https://docs.opsi.org/opsi-docs-en/4.3/opsi-script-manual/cook-book.html)
- [MSI error codes](https://learn.microsoft.com/en-us/windows/win32/msi/error-codes)
- [How to update a package (forum thread)](https://forum.opsi.org/viewtopic.php?t=4288)

## License

[MIT](https://github.com/sitlg/opsi-tmpl/blob/master/LICENSE) (c) 2023 - 2024 sitlg and contributors
