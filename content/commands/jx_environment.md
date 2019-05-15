---
date: 2019-05-15T12:55:34Z
title: "jx environment"
slug: jx_environment
url: /commands/jx_environment/
---
## jx environment

View or change the current environment in the current Kubernetes cluster

### Synopsis

Displays or changes the current environment. 

For more documentation on Environments see: https://jenkins-x.io/about/features/#environments

```
jx environment [flags]
```

### Examples

```
  # view the current environment
  jx env -b
  
  # pick which environment to switch to
  jx env
  
  # Change the current environment to 'staging'
  jx env staging
```

### Options

```
  -h, --help   help for environment
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

* [jx](/commands/jx/)	 - jx is a command line tool for working with Jenkins X

###### Auto generated by spf13/cobra on 15-May-2019