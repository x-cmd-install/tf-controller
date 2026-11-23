# tf-controller

[中文版本](./README.cn.md)

A GitOps OpenTofu and Terraform controller for Flux

[![x-cmd/install — tf-controller Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/tf-controller.svg)](https://x-cmd.com/install/tf-controller)

## Install

```sh
x install tf-controller
```

## Code insight

Total: **88,533** lines of code across **397** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 44,363 | 3,067 | 6,572 | 261 |
| Yaml | 42,978 | 161 | 321 | 129 |
| Sh | 354 | 93 | 111 | 5 |
| Protobuf | 276 | 2 | 67 | 1 |
| Makefile | 239 | 33 | 59 | 1 |

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

- **Latest**: `v0.17.0` (2026-11-16)
- **Last commit**: 2026-11-18
- **Assets in release**: 14

## Popularity

- **Stars**: 1,730 · **Forks**: 205 · **Open issues**: 727 · **Contributors**: 85

## Totals (cumulative)

- **Releases**: 113 · **Merged PRs**: 710 · **Open PRs**: 27 · **Closed issues**: 595 · **Open issues**: 132 · **Commits**: 2106

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-24 | 2 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-09-24 | 2 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-08-25 | 2 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-05-27 | 4 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-11-28 | 10 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-12-03 | 12 | 0 | 0 | 0 | 0 | 0 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [tfctl_Darwin_amd64.tar.gz](https://github.com/weaveworks/tf-controller/releases/download/v0.17.0/tfctl_Darwin_amd64.tar.gz) | 14.4 MiB | `native/darwin/x64` |
| [tfctl_Darwin_arm64.tar.gz](https://github.com/weaveworks/tf-controller/releases/download/v0.17.0/tfctl_Darwin_arm64.tar.gz) | 13.1 MiB | `native/darwin/arm64` |
| [tfctl_Linux_amd64.tar.gz](https://github.com/weaveworks/tf-controller/releases/download/v0.17.0/tfctl_Linux_amd64.tar.gz) | 14.2 MiB | `native/linux/x64` |
| [tfctl_Linux_arm64.tar.gz](https://github.com/weaveworks/tf-controller/releases/download/v0.17.0/tfctl_Linux_arm64.tar.gz) | 12.5 MiB | `native/linux/arm64` |
| [tfctl_Linux_armv6.tar.gz](https://github.com/weaveworks/tf-controller/releases/download/v0.17.0/tfctl_Linux_armv6.tar.gz) | 13.4 MiB | `native/linux/arm` |
| [tfctl_Linux_armv7.tar.gz](https://github.com/weaveworks/tf-controller/releases/download/v0.17.0/tfctl_Linux_armv7.tar.gz) | 13.4 MiB | `native/linux/arm` |
| [tofu-controller.crds.yaml](https://github.com/weaveworks/tf-controller/releases/download/v0.17.0/tofu-controller.crds.yaml) | 416.1 KiB | `other` |
| [tofu-controller.deployment.yaml](https://github.com/weaveworks/tf-controller/releases/download/v0.17.0/tofu-controller.deployment.yaml) | 2.1 KiB | `other` |
| [tofu-controller.packages.yaml](https://github.com/weaveworks/tf-controller/releases/download/v0.17.0/tofu-controller.packages.yaml) | 226 B | `other` |
| [tofu-controller.rbac.yaml](https://github.com/weaveworks/tf-controller/releases/download/v0.17.0/tofu-controller.rbac.yaml) | 3.2 KiB | `other` |
| [tofu-controller_0.17.0_checksums.txt](https://github.com/weaveworks/tf-controller/releases/download/v0.17.0/tofu-controller_0.17.0_checksums.txt) | 1.1 KiB | `other` |
| [tofu-controller_0.17.0_checksums.txt.sigstore.json](https://github.com/weaveworks/tf-controller/releases/download/v0.17.0/tofu-controller_0.17.0_checksums.txt.sigstore.json) | 10.1 KiB | `other` |
| [tofu-controller_0.17.0_sbom.spdx.json](https://github.com/weaveworks/tf-controller/releases/download/v0.17.0/tofu-controller_0.17.0_sbom.spdx.json) | 1.1 MiB | `other` |
| [tofu-controller_0.17.0_source_code.tar.gz](https://github.com/weaveworks/tf-controller/releases/download/v0.17.0/tofu-controller_0.17.0_source_code.tar.gz) | 1.7 MiB | `native/unknown` |

## Improve this data

Install metadata for tf-controller lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `tf-controller` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/tf-controller.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/261123.yml` · 2026-11-23T07:23:04Z._
