---
type: docs
title: "rad group delete CLI reference"
linkTitle: "rad group delete"
slug: rad_group_delete
url: /reference/cli/rad_group_delete/
description: "Details on the rad group delete Radius CLI command"
---
## rad group delete

Delete a resource group

### Synopsis

Delete a resource group. 
		
		Delete a resource group if it is empty. If not empty, delete the contents and try again

```
rad group delete resourcegroupname [flags]
```

### Examples

```
rad group delete rgprod
```

### Options

```
  -g, --group string       The resource group name
  -h, --help               help for delete
  -w, --workspace string   The workspace name
  -y, --yes                The confirmation flag
```

### Options inherited from parent commands

```
      --config string   config file (default "$HOME/.rad/config.yaml")
  -o, --output string   output format (supported formats are json, table) (default "table")
```

### SEE ALSO

* [rad group]({{< ref rad_group.md >}})	 - Manage resource groups

