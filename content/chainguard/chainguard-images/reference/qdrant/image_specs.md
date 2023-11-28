---
title: "qdrant Image Variants"
type: "article"
unlisted: true
description: "Detailed information about the public qdrant Chainguard Image variants"
date: 2023-03-07T11:07:52+02:00
lastmod: 2023-03-07T11:07:52+02:00
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
weight: 550
toc: true
---

{{< tabs >}}
{{< tab title="Overview" active=false url="/chainguard/chainguard-images/reference/qdrant/" >}}
{{< tab title="Variants" active=true url="/chainguard/chainguard-images/reference/qdrant/image_specs/" >}}
{{< tab title="Tags History" active=false url="/chainguard/chainguard-images/reference/qdrant/tags_history/" >}}
{{< tab title="Provenance" active=false url="/chainguard/chainguard-images/reference/qdrant/provenance_info/" >}}
{{</ tabs >}}

This page shows detailed information about all public variants of the Chainguard **qdrant** Image.

## Variants Compared
The **qdrant** Chainguard Image currently has 2 public variants: 

- `latest-dev`
- `latest`

The table has detailed information about each of these variants.

|              | latest-dev                      | latest                          |
|--------------|---------------------------------|---------------------------------|
| Default User | `root`                          | `root`                          |
| Entrypoint   | `/usr/lib/qdrant/entrypoint.sh` | `/usr/lib/qdrant/entrypoint.sh` |
| CMD          | not specified                   | not specified                   |
| Workdir      | `/qdrant`                       | `/qdrant`                       |
| Has apk?     | yes                             | no                              |
| Has a shell? | yes                             | yes                             |

Check the [tags history page](/chainguard/chainguard-images/reference/qdrant/tags_history/) for the full list of available tags.

## Packages Included
The table shows package distribution across variants.

|                          | latest-dev | latest |
|--------------------------|------------|--------|
| `apk-tools`              | X          |        |
| `bash`                   | X          | X      |
| `busybox`                | X          | X      |
| `ca-certificates-bundle` | X          | X      |
| `git`                    | X          |        |
| `glibc`                  | X          | X      |
| `glibc-locale-posix`     | X          | X      |
| `ld-linux`               | X          | X      |
| `libbrotlicommon1`       | X          |        |
| `libbrotlidec1`          | X          |        |
| `libcrypt1`              | X          | X      |
| `libcrypto3`             | X          |        |
| `libcurl-openssl4`       | X          |        |
| `libexpat1`              | X          |        |
| `libgcc`                 | X          | X      |
| `libnghttp2-14`          | X          |        |
| `libpcre2-8-0`           | X          |        |
| `libssl3`                | X          |        |
| `libstdc++`              | X          | X      |
| `ncurses`                | X          | X      |
| `ncurses-terminfo-base`  | X          | X      |
| `openssl-config`         | X          |        |
| `qdrant`                 | X          | X      |
| `qdrant-oci-compat`      | X          | X      |
| `qdrant-oci-entrypoint`  | X          | X      |
| `wolfi-baselayout`       | X          | X      |
| `zlib`                   | X          |        |
