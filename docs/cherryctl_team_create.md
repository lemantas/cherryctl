## cherryctl team create

Create a team.

### Synopsis

Create a team.

```
cherryctl team create --name <team_name> --type <team_type> [--currency <currency_code>] [flags]
```

### Examples

```
  # Create business team with USD currency:
  cherryctl team create --name="USD team" --type business --currency USD
```

### Options

```
      --currency string   Team currency, available otions: EUR, USD.
  -h, --help              help for create
      --name string       Team name.
      --type string       Team type, available options: personal, business.
```

### Options inherited from parent commands

```
      --config string    Path to JSON or YAML configuration file
      --fields strings   Comma separated object field names to output in result. Fields can be used for list and get actions.
  -o, --output string    Output format (*table, json, yaml)
      --token string     API Token (CHERRY_AUTH_TOKEN)
```

### SEE ALSO

* [cherryctl team](cherryctl_team.md)	 - Team operations.

