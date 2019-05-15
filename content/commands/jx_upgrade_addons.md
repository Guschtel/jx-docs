---
date: 2019-05-15T12:55:34Z
title: "jx upgrade addons"
slug: jx_upgrade_addons
url: /commands/jx_upgrade_addons/
---
## jx upgrade addons

Upgrades any Addons added to Jenkins X if there are any new releases available

### Synopsis

Upgrades any Addons added to Jenkins X if there are any new releases available

```
jx upgrade addons [flags]
```

### Examples

```
  # Upgrades any Addons added to Jenkins X
  jx upgrade addons
```

### Options

```
      --cloud-environment-repo string   Cloud Environments Git repo (default "https://github.com/jenkins-x/cloud-environments")
  -h, --help                            help for addons
      --local-cloud-environment         Ignores default cloud-environment-repo and uses current directory 
  -n, --namespace string                The Namespace to upgrade
  -s, --set string                      The Helm parameters to pass in while upgrading
      --versions-dir string             The directory containing the versions repo
      --versions-ref string             Jenkins X versions Git repository reference (tag, branch, sha etc)
      --versions-repo string            Jenkins X versions Git repo (default "https://github.com/jenkins-x/jenkins-x-versions.git")
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

* [jx upgrade](/commands/jx_upgrade/)	 - Upgrades a resource
* [jx upgrade addons prow](/commands/jx_upgrade_addons_prow/)	 - Upgrades any AddonProw added to Jenkins X if there are any new releases available

###### Auto generated by spf13/cobra on 15-May-2019