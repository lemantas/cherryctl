## cherryctl project list

Retrieves list of projects details.

### Synopsis

Retrieves the details of projects.

```
cherryctl project list [-p <project_id>] [flags]
```

### Examples

```
  # List available projects:
  cherryctl project list -t 12345
```

### Options

```
  -h, --help          help for list
  -t, --team-id int   The team's ID.
```

### Options inherited from parent commands

```
      --config string    Path to JSON or YAML configuration file
      --fields strings   Comma separated object field names to output in result. Fields can be used for list and get actions.
  -o, --output string    Output format (*table, json, yaml)
      --token string     API Token (CHERRY_AUTH_TOKEN)
```

### SEE ALSO

* [cherryctl project](cherryctl_project.md)	 - Project operations.

