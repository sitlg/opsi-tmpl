# OPSi Templates

OPSi templates for usage with IServ

## Usage

Templates do **NOT** contain data files, as these would not make sense to track in version control.

### Quickstart

- (Optional) Clone this repo
- Copy any folder from the `tmpl` directory to make changes
  - Some templates can be used as is, but most require you to add files to the `data` folder (consult the `README.md` of the template) and make edits based on these files
- Copy edited folder to your server in `/srv/deploy/install`
- Run `chkdeploy` to update local package registry and make the server aware of the new package

## Templates

- default-program-registry-patch

## License

None
