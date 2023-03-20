---
date: 2023-03-16T21:11:47Z
title: "chainctl clusters cidrs list"
slug: chainctl_clusters_cidrs_list
url: /chainguard/chainguard-enforce/chainctl-docs/chainctl_clusters_cidrs_list/
draft: false
images: []
type: "article"
toc: true
---
## chainctl clusters cidrs list

List Enforce Egress CIDR ranges.

```
chainctl clusters cidrs list [--output json]
```

### Options

```
  -h, --help   help for list
```

### Options inherited from parent commands

```
      --api string                   The url of the Chainguard platform API. (default "http://api.api-system.svc")
      --audience string              The Chainguard token audience to request. (default "http://api.api-system.svc")
      --config string                A specific chainctl config file.
      --console string               The url of the Chainguard platform Console. (default "http://console-ui.api-system.svc")
      --issuer string                The url of the Chainguard STS endpoint. (default "http://issuer.oidc-system.svc")
  -o, --output string                Output format. One of: ["", "table", "tree", "json", "id", "wide"]
      --timestamp-authority string   The url of the Chainguard Timestamp Authority endpoint. (default "http://tsa.timestamp-authority.svc")
  -v, --v int                        Set the log verbosity level.
```

### SEE ALSO

* [chainctl clusters cidrs](/chainguard/chainguard-enforce/chainctl-docs/chainctl_clusters_cidrs/)	 - Enforce Egress CIDR related commands.
