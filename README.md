# tf-controller

[中文版本](./README.cn.md)

A GitOps OpenTofu and Terraform controller for Flux

[![x-cmd/install — tf-controller Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/tf-controller.svg)](https://x-cmd.com/install/tf-controller)

## Install

```sh
x install tf-controller
```

## Code insight

Total: **100,699** lines of code across **405** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Yaml | 53,969 | 161 | 373 | 129 |
| Go | 45,538 | 3,592 | 6,844 | 269 |
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

- **Latest**: `v0.16.6` (2026-10-26)
- **Last commit**: 2026-10-28
- **Assets in release**: 14

## Popularity

- **Stars**: 1,720 · **Forks**: 200 · **Open issues**: 720 · **Contributors**: 83

## Totals (cumulative)

- **Releases**: 112 · **Merged PRs**: 697 · **Open PRs**: 26 · **Closed issues**: 591 · **Open issues**: 129 · **Commits**: 2094

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-01 | 1 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-09-01 | 1 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-08-02 | 2 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-05-04 | 4 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-11-05 | 10 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-11-10 | 11 | 0 | 0 | 0 | 0 | 0 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [tfctl_Darwin_amd64.tar.gz](https://github.com/weaveworks/tf-controller/releases/download/v0.16.6/tfctl_Darwin_amd64.tar.gz) | 14.4 MiB | `native/darwin/x64` |
| [tfctl_Darwin_arm64.tar.gz](https://github.com/weaveworks/tf-controller/releases/download/v0.16.6/tfctl_Darwin_arm64.tar.gz) | 13.1 MiB | `native/darwin/arm64` |
| [tfctl_Linux_amd64.tar.gz](https://github.com/weaveworks/tf-controller/releases/download/v0.16.6/tfctl_Linux_amd64.tar.gz) | 14.2 MiB | `native/linux/x64` |
| [tfctl_Linux_arm64.tar.gz](https://github.com/weaveworks/tf-controller/releases/download/v0.16.6/tfctl_Linux_arm64.tar.gz) | 12.5 MiB | `native/linux/arm64` |
| [tfctl_Linux_armv6.tar.gz](https://github.com/weaveworks/tf-controller/releases/download/v0.16.6/tfctl_Linux_armv6.tar.gz) | 13.4 MiB | `native/linux/arm` |
| [tfctl_Linux_armv7.tar.gz](https://github.com/weaveworks/tf-controller/releases/download/v0.16.6/tfctl_Linux_armv7.tar.gz) | 13.4 MiB | `native/linux/arm` |
| [tofu-controller.crds.yaml](https://github.com/weaveworks/tf-controller/releases/download/v0.16.6/tofu-controller.crds.yaml) | 783.1 KiB | `other` |
| [tofu-controller.deployment.yaml](https://github.com/weaveworks/tf-controller/releases/download/v0.16.6/tofu-controller.deployment.yaml) | 2.1 KiB | `other` |
| [tofu-controller.packages.yaml](https://github.com/weaveworks/tf-controller/releases/download/v0.16.6/tofu-controller.packages.yaml) | 226 B | `other` |
| [tofu-controller.rbac.yaml](https://github.com/weaveworks/tf-controller/releases/download/v0.16.6/tofu-controller.rbac.yaml) | 3.2 KiB | `other` |
| [tofu-controller_0.16.6_checksums.txt](https://github.com/weaveworks/tf-controller/releases/download/v0.16.6/tofu-controller_0.16.6_checksums.txt) | 1.1 KiB | `other` |
| [tofu-controller_0.16.6_checksums.txt.sigstore.json](https://github.com/weaveworks/tf-controller/releases/download/v0.16.6/tofu-controller_0.16.6_checksums.txt.sigstore.json) | 10.1 KiB | `other` |
| [tofu-controller_0.16.6_sbom.spdx.json](https://github.com/weaveworks/tf-controller/releases/download/v0.16.6/tofu-controller_0.16.6_sbom.spdx.json) | 1.0 MiB | `other` |
| [tofu-controller_0.16.6_source_code.tar.gz](https://github.com/weaveworks/tf-controller/releases/download/v0.16.6/tofu-controller_0.16.6_source_code.tar.gz) | 1.7 MiB | `native/unknown` |

## Improve this data

Install metadata for tf-controller lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `tf-controller` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/tf-controller.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/261031.yml` · 2026-10-31T05:20:45Z._
