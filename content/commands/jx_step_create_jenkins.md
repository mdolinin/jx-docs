---
date: 2019-06-03T16:28:43Z
title: "jx step create jenkins"
slug: jx_step_create_jenkins
url: /commands/jx_step_create_jenkins/
---
## jx step create jenkins

Creates the Jenkins config.xml file from a number of ConfigMaps for Pod Templates

### Synopsis

Creates the Jenkins config.xml file from a number of ConfigMaps for Pod Templates

```
jx step create jenkins config [flags]
```

### Examples

```
  jx step create jenkins config
```

### Options

```
  -h, --help            help for jenkins
  -o, --output string   the output file generated (default "config.xml")
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

* [jx step create](/commands/jx_step_create/)	 - create [command]

###### Auto generated by spf13/cobra on 3-Jun-2019
