# tf-controller

[中文版本](./README.cn.md)

A GitOps OpenTofu and Terraform controller for Flux

![tf-controller](https://repo.x-cmd.io/tf-controller.svg)

## Install

```sh
x install tf-controller
```

## Code insight

Total: **64,428** lines of code across **306** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 37,266 | 2,368 | 5,585 | 223 |
| Yaml | 25,990 | 130 | 128 | 76 |
| Sh | 340 | 91 | 105 | 5 |
| Protobuf | 276 | 0 | 70 | 1 |
| Makefile | 233 | 33 | 58 | 1 |

## OpenSSF Scorecard

Overall score: **8.7 / 10**

Lowest-scoring checks:

- **Branch-Protection** (-1/10) — internal error: error during branchesHandler.setup: internal error: githubv4.Query: Resource not accessible by integrati…
- **Fuzzing** (0/10) — project is not fuzzed

## Source

- **Upstream**: <https://github.com/weaveworks/tf-controller>
- **Homepage**: <https://flux-iac.github.io/tofu-controller/>
- **License**: Apache-2.0

## Release

- **Latest**: `v0.16.5` (2026-08-06)
- **Last commit**: 2026-09-02
- **Assets in release**: 14

## Popularity

- **Stars**: 1,689 · **Forks**: 195 · **Open issues**: 718 · **Contributors**: 79

## Totals (cumulative)

- **Releases**: 111 · **Merged PRs**: 682 · **Open PRs**: 28 · **Closed issues**: 590 · **Open issues**: 128 · **Commits**: 2078

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 0 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-13 | 1 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-13 | 1 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-03-15 | 4 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-09-16 | 9 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-09-21 | 10 | 0 | 0 | 0 | 0 | 0 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [tfctl_Darwin_amd64.tar.gz](https://github.com/weaveworks/tf-controller/releases/download/v0.16.5/tfctl_Darwin_amd64.tar.gz) | 13.9 MiB | `native/darwin/x64` |
| [tfctl_Darwin_arm64.tar.gz](https://github.com/weaveworks/tf-controller/releases/download/v0.16.5/tfctl_Darwin_arm64.tar.gz) | 12.7 MiB | `native/darwin/arm64` |
| [tfctl_Linux_amd64.tar.gz](https://github.com/weaveworks/tf-controller/releases/download/v0.16.5/tfctl_Linux_amd64.tar.gz) | 13.7 MiB | `native/linux/x64` |
| [tfctl_Linux_arm64.tar.gz](https://github.com/weaveworks/tf-controller/releases/download/v0.16.5/tfctl_Linux_arm64.tar.gz) | 12.2 MiB | `native/linux/arm64` |
| [tfctl_Linux_armv6.tar.gz](https://github.com/weaveworks/tf-controller/releases/download/v0.16.5/tfctl_Linux_armv6.tar.gz) | 12.9 MiB | `native/linux/arm` |
| [tfctl_Linux_armv7.tar.gz](https://github.com/weaveworks/tf-controller/releases/download/v0.16.5/tfctl_Linux_armv7.tar.gz) | 12.9 MiB | `native/linux/arm` |
| [tofu-controller.crds.yaml](https://github.com/weaveworks/tf-controller/releases/download/v0.16.5/tofu-controller.crds.yaml) | 755.8 KiB | `other` |
| [tofu-controller.deployment.yaml](https://github.com/weaveworks/tf-controller/releases/download/v0.16.5/tofu-controller.deployment.yaml) | 2.1 KiB | `other` |
| [tofu-controller.packages.yaml](https://github.com/weaveworks/tf-controller/releases/download/v0.16.5/tofu-controller.packages.yaml) | 226 B | `other` |
| [tofu-controller.rbac.yaml](https://github.com/weaveworks/tf-controller/releases/download/v0.16.5/tofu-controller.rbac.yaml) | 3.2 KiB | `other` |
| [tofu-controller_0.16.5_checksums.txt](https://github.com/weaveworks/tf-controller/releases/download/v0.16.5/tofu-controller_0.16.5_checksums.txt) | 1.1 KiB | `other` |
| [tofu-controller_0.16.5_checksums.txt.sigstore.json](https://github.com/weaveworks/tf-controller/releases/download/v0.16.5/tofu-controller_0.16.5_checksums.txt.sigstore.json) | 10.3 KiB | `other` |
| [tofu-controller_0.16.5_sbom.spdx.json](https://github.com/weaveworks/tf-controller/releases/download/v0.16.5/tofu-controller_0.16.5_sbom.spdx.json) | 1.0 MiB | `other` |
| [tofu-controller_0.16.5_source_code.tar.gz](https://github.com/weaveworks/tf-controller/releases/download/v0.16.5/tofu-controller_0.16.5_source_code.tar.gz) | 1.7 MiB | `native/unknown` |

## Improve this data

Install metadata for tf-controller lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `tf-controller` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/tf-controller.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260911.yml` · 2026-09-11T04:26:55Z._
