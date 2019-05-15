---
date: 2019-05-15T12:55:34Z
title: "jx create etc-hosts"
slug: jx_create_etc-hosts
url: /commands/jx_create_etc-hosts/
---
## jx create etc-hosts

Creates a new Git server URL

### Synopsis

Creates /etc/hosts entries for all current exposed services

```
jx create etc-hosts kind [url] [flags]
```

### Examples

```
  # Creates /etc/hosts entries for all current exposed services
  sudo jx create etc-hosts
```

### Options

```
  -h, --help          help for etc-hosts
  -i, --ip string     The IP address of the node to point the host entries to
  -n, --name string   The etc hosts file to edit (default "/etc/hosts")
```

### Options inherited from parent commands

```
  -b, --batch-mode                Runs in batch mode without prompting for user input (default true)
      --install-dependencies      Enables automatic dependencies installation when required
      --log-level string          Sets the logging level (panic, fatal, error, warning, info, debug) (default "info")
      --no-brew                   Disables brew package manager on MacOS when installing binary dependencies
      --skip-auth-secrets-merge   Skips merging the secrets from local files with the secrets from Kubernetes cluster
      --verbose                   Enables verbose output
```

### SEE ALSO

* [jx create](/commands/jx_create/)	 - Create a new resource

###### Auto generated by spf13/cobra on 15-May-2019