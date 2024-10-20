---
type: docs
title: "rad workspace create CLI reference"
linkTitle: "rad workspace create"
slug: rad_workspace_create
url: /reference/cli/rad_workspace_create/
description: "Details on the rad workspace create Radius CLI command"
---
## rad workspace create

Create a workspace

### Synopsis

Create a workspace.
		
Available workspaceTypes: kubernetes

Workspaces allow you to manage multiple Radius platforms and environments using a local configuration file. 

You can easily define and switch between workspaces to deploy and manage applications across local, test, and production environments.

```
rad workspace create [workspaceType] [workspaceName] [flags]
```

### Examples

```

# Create a workspace with name 'myworkspace' and kubernetes context 'aks'
rad workspace create kubernetes myworkspace --context aks
# Create a workspace with name of current kubernetes context in current kubernetes context
rad workspace create kubernetes
```

### Options

```
  -c, --context string       the Kubernetes context to use, will use the default if unset
  -e, --environment string   The environment name
  -f, --force                Overwrite existing workspace if present
  -g, --group string         The resource group name
  -h, --help                 help for create
  -w, --workspace string     The workspace name
```

### Options inherited from parent commands

```
      --config string   config file (default "$HOME/.rad/config.yaml")
  -o, --output string   output format (supported formats are json, table) (default "table")
```

### SEE ALSO

* [rad workspace]({{< ref rad_workspace.md >}})	 - Manage workspaces

