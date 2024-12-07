---
date: 2024-11-29T16:27:20+01:00
title: "bl apply"
slug: bl_apply
---
## bl apply

Apply a configuration to a resource by file

### Synopsis

Apply a configuration to a resource by file

```
bl apply [flags]
```

### Examples

```

			bl apply -f ./my-deployment.yaml
			# Or using stdin
			cat file.yaml | bl apply -f -

```

### Options

```
  -f, --filename string   The files that contain the configurations to apply.
  -R, --recursive=false   Process the directory used in -f, --filename recursively. Useful when you want to manage related manifests organized within the same directory.
  -h, --help              help for apply
```

### Options inherited from parent commands

```
  -e, --env string         Environment. One of: development,production
  -o, --output string      Output format. One of: pretty,yaml,json,table
  -v, --verbose            Enable verbose output
  -w, --workspace string   Specify the workspace name
```

### SEE ALSO

* [bl](bl.md)	 - Beamlit CLI is a command line tool to interact with Beamlit APIs.

