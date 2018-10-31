---
date: 2018-10-31T10:49:20Z
title: "jx step helm list"
slug: jx_step_helm_list
url: /commands/jx_step_helm_list/
---
## jx step helm list

List the helm releases

### Synopsis

List the helm releases

```
jx step helm list [flags]
```

### Examples

```
  # list all the helm releases in the current namespace
  jx step helm list
```

### Options

```
      --clone-https git@foo/bar.git   Clone the environment Git repo over https rather than ssh which uses git@foo/bar.git (default true)
  -d, --dir string                    The directory containing the helm chart to apply (default ".")
      --git-provider string           The Git provider for the environment Git repository (default "github.com")
  -h, --help                          help for list
  -n, --namespace string              the namespace to look for the helm releases. Defaults to the current namespace
```

### SEE ALSO

* [jx step helm](/commands/jx_step_helm/)	 - helm [command]

###### Auto generated by spf13/cobra on 31-Oct-2018