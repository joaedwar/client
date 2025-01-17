## kn plugin list

List plugins

### Synopsis

List all installed plugins.

Available plugins are those that are:
- executable
- begin with "kn-"
- Kn's plugin directory ~/.kn/plugins
- Anywhere in the execution $PATH (if lookupInPath config variable is enabled)

```
kn plugin list [flags]
```

### Options

```
  -h, --help                     help for list
      --lookup-plugins-in-path   look for kn plugins in $PATH
      --name-only                If true, display only the binary name of each plugin, rather than its full path
      --plugins-dir string       kn plugins directory (default "~/.kn/plugins")
      --verbose                  verbose output
```

### Options inherited from parent commands

```
      --config string       kn config file (default is $HOME/.kn/config.yaml)
      --kubeconfig string   kubectl config file (default is $HOME/.kube/config)
      --log-http            log http traffic
```

### SEE ALSO

* [kn plugin](kn_plugin.md)	 - Plugin command group

