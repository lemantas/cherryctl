## cherryctl storage update

Update storage volume.

### Synopsis

Update storage size or description.

```
cherryctl storage update ID [--size <gigabytes>] [--description <text>] [flags]
```

### Examples

```
  # Update storage size to 1000 gigabyte:
  cherryctl storage update 12345 --size 1000
```

### Options

```
      --description string   Storage description.
  -h, --help                 help for update
      --size int             Storage volume size in gigabytes. Value must be greater than current volume size.
```

### Options inherited from parent commands

```
      --config string    Path to JSON or YAML configuration file
      --fields strings   Comma separated object field names to output in result. Fields can be used for list and get actions.
  -o, --output string    Output format (*table, json, yaml)
      --token string     API Token (CHERRY_AUTH_TOKEN)
```

### SEE ALSO

* [cherryctl storage](cherryctl_storage.md)	 - Storage operations. For more information visit https://docs.cherryservers.com/knowledge/elastic-block-storage/.

