---
date: 2019-05-15T12:55:34Z
title: "jx compliance logs"
slug: jx_compliance_logs
url: /commands/jx_compliance_logs/
---
## jx compliance logs

Prints the logs of compliance tests

### Synopsis

Prints the logs of compliance tests

```
jx compliance logs [flags]
```

### Examples

```
  # Print the compliance logs
  jx compliance logs
```

### Options

```
  -f, --follow   Specify if the logs should be streamed.
  -h, --help     help for logs
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

* [jx compliance](/commands/jx_compliance/)	 - Run compliance tests against Kubernetes cluster

###### Auto generated by spf13/cobra on 15-May-2019