## cherryctl ip assign

Assign an IP address to a specified server or other IP address.

### Synopsis

Assign an IP address to a specified server or another IP address. IP address assignment to another IP is possible only if routed IP type is floating and target IP is subnet or primary-ip type.

```
cherryctl ip assign ID {--target-hostname <hostname> | --target-id <server_id> | --target-ip-id <ip_id>} [-p <project_id>] [flags]
```

### Examples

```
  # Assign an IP address to a server:
  cherryctl ip assign 30c15082-a06e-4c43-bfc3-252616b46eba --server-id 12345
```

### Options

```
  -h, --help                     help for assign
  -p, --project-id int           The project's ID.
      --target-hostname string   The hostname of the server to assign IP to.
      --target-id int            The ID of the server to assign IP to.
      --target-ip-id string      Subnet or primary-ip type IP ID to route IP to.
```

### Options inherited from parent commands

```
      --config string    Path to JSON or YAML configuration file
      --fields strings   Comma separated object field names to output in result. Fields can be used for list and get actions.
  -o, --output string    Output format (*table, json, yaml)
      --token string     API Token (CHERRY_AUTH_TOKEN)
```

### SEE ALSO

* [cherryctl ip](cherryctl_ip.md)	 - IP address operations.

