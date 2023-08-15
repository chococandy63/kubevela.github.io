---
title: vela def vet
---

Validate X-Definition.

### Synopsis

Validate definition file by checking whether it has the valid cue format with fields set correctly
* Currently, this command only checks the cue format. This function is still working in progress and we will support more functional validation mechanism in the future.

```
vela def vet DEFINITION.cue [flags]
```

### Examples

```
# Command below will validate the my-def.cue file.
> vela def vet my-def.cue
```

### Options

```
  -h, --help   help for vet
```

### Options inherited from parent commands

```
  -y, --yes   Assume yes for all user prompts
```

### SEE ALSO

* [vela def](vela_def.md)	 - Manage Definitions

#### Go Back to [CLI Commands](vela.md) Homepage.


###### Auto generated by [spf13/cobra script in KubeVela](https://github.com/kubevela/kubevela/tree/master/hack/docgen).