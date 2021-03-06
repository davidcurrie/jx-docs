---
date: 2018-10-05T08:42:16Z
title: "jx namespace"
slug: jx_namespace
url: /commands/jx_namespace/
---
## jx namespace

View or change the current namespace context in the current Kubernetes cluster

### Synopsis

Displays or changes the current namespace.

```
jx namespace [flags]
```

### Examples

```
  # view the current namespace
  jx ns -b
  
  # to select the namespace to switch to
  jx ns
  
  # Change the current namespace to 'cheese'
  jx ns cheese
```

### Options

```
  -b, --batch-mode                In batch mode the command never prompts for user input
      --headless                  Enable headless operation if using browser automation
  -h, --help                      help for namespace
      --install-dependencies      Should any required dependencies be installed automatically
      --log-level string          Logging level. Possible values - panic, fatal, error, warning, info, debug. (default "info")
      --no-brew                   Disables the use of brew on MacOS to install or upgrade command line dependencies
      --skip-auth-secrets-merge   Skips merging a local git auth yaml file with any pipeline secrets that are found
      --verbose                   Enable verbose logging
```

### SEE ALSO

* [jx](/commands/jx/)	 - jx is a command line tool for working with Jenkins X

###### Auto generated by spf13/cobra on 5-Oct-2018
