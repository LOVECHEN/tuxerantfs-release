# tuxerantfs-release

**Tuxera NTFS for Mac 官方安装包自动镜像 | Automated mirror of official Tuxera NTFS for Mac installers.**

每 6 小时由 GitHub Actions 检查官方更新源，发现新版本即从官方 CDN 下载原版 `.dmg`，计算 SHA-256，发布为一个 GitHub Release。官方原版，未经修改，逐字节镜像，仅作版本归档 / 离线留存。

- 覆盖 `stable`（正式）与 `testing`（预发布）两个通道；`testing` 仅在与 `stable` 版本不同时才单独归档。
- 每个 Release 含官方 `tuxerantfs_<ver>.dmg` + 官方 `.sig` + `SHA256SUMS.txt`。
- 已归档清单见 [`MIRRORED.md`](MIRRORED.md)。

---

> Unaffiliated with Tuxera Oy. Binaries are the unmodified official builds, redistributed for archival / offline use.
