---
date: 2019-05-15T12:55:34Z
title: "jx step get"
slug: jx_step_get
url: /commands/jx_step_get/
---
## jx step get

get [command]

### Synopsis

get [command]

```
jx step get [flags]
```

### Options

```
  -h, --help   help for get
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

* [jx step](/commands/jx_step/)	 - pipeline steps
* [jx step get buildnumber](/commands/jx_step_get_buildnumber/)	 - Outputs the current build number from environment variables or using the Downward API inside build pods
* [jx step get version-changeset](/commands/jx_step_get_version-changeset/)	 - Creates environment variables from the differences of versions between jenkins-x-version branches

###### Auto generated by spf13/cobra on 15-May-2019