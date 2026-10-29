# tf-controller

[English version](./README.md)

A GitOps OpenTofu and Terraform controller for Flux

[![x-cmd/install — tf-controller Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/tf-controller.svg?lang=zh)](https://x-cmd.com/install/tf-controller)

## 安装

```sh
x install tf-controller
```

## 代码洞察

合计: **100,699** 行代码（覆盖前 5 种语言、共 **405** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Yaml | 53,969 | 161 | 373 | 129 |
| Go | 45,538 | 3,592 | 6,844 | 269 |
| Sh | 354 | 93 | 111 | 5 |
| Protobuf | 276 | 2 | 67 | 1 |
| Makefile | 239 | 33 | 59 | 1 |

## OpenSSF Scorecard 评分

总评分: **8.7 / 10**

评分最低的几项:

- **Branch-Protection** (-1/10) — internal error: error during branchesHandler.setup: internal error: githubv4.Query: Resource not accessible by integrati…
- **Fuzzing** (0/10) — project is not fuzzed

## 源代码

- **上游仓库**: <https://github.com/weaveworks/tf-controller>
- **官网**: <https://flux-iac.github.io/tofu-controller/>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v0.16.6` (2026-10-26)
- **最近提交**: 2026-10-28
- **Release 含资产**: 14 个

## 流行度

- **Star**: 1,719 · **Fork**: 201 · **开放 issue**: 720 · **贡献者**: 83

## 累计统计

- **发布数**: 112 · **已合并 PR**: 698 · **开放 PR**: 26 · **已关闭 issue**: 591 · **开放 issue**: 129 · **提交数**: 2094

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-09-29 | 1 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-08-30 | 1 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-07-31 | 2 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-05-02 | 4 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-11-03 | 10 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-11-08 | 11 | 0 | 0 | 0 | 0 | 0 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
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

## 改进这些数据

tf-controller 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `tf-controller` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/tf-controller.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/261029.yml` · 2026-10-29T05:34:49Z._
