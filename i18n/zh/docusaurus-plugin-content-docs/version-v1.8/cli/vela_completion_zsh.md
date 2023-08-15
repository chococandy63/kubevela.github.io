---
title: vela completion zsh
---

generate autocompletions script for zsh

### Synopsis

Generate the autocompletion script for Vela for the zsh shell.

To load completions in your current shell session:
$ source <(vela completion zsh)

To load completions for every new session, execute once:
$ vela completion zsh > "${fpath[1]}/_vela"


```
vela completion zsh
```

### Options

```
  -h, --help   help for zsh
```

### Options inherited from parent commands

```
  -y, --yes   Assume yes for all user prompts
```

### SEE ALSO

* [vela completion](vela_completion.md)	 - Output shell completion code for the specified shell (bash or zsh)

#### Go Back to [CLI Commands](vela.md) Homepage.


###### Auto generated by [spf13/cobra script in KubeVela](https://github.com/kubevela/kubevela/tree/master/hack/docgen).