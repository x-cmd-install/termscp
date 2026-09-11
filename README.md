# termscp

[中文版本](./README.cn.md)

🖥  A feature rich terminal UI file transfer and explorer with support for SCP/SFTP/FTP/S3/SMB/WebDAV

![termscp](https://repo.x-cmd.io/termscp.svg)

## Install

```sh
x install termscp
```

## Code insight

Total: **50,045** lines of code across **217** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Rust | 35,467 | 1,516 | 3,194 | 178 |
| Json | 7,978 | 0 | 0 | 5 |
| JavaScript | 5,125 | 49 | 326 | 10 |
| Sh | 623 | 67 | 108 | 5 |
| Toml | 583 | 22 | 34 | 19 |

## OpenSSF Scorecard

Overall score: **5.5 / 10**

Lowest-scoring checks:

- **Code-Review** (0/10) — Found 0/22 approved changesets -- score normalized to 0
- **Security-Policy** (4/10) — security policy file detected
- **Packaging** (-1/10) — packaging workflow not detected

## Source

- **Upstream**: <https://github.com/veeso/termscp>
- **Homepage**: <https://termscp.rs>
- **License**: MIT

## Release

- **Latest**: `v1.2.0` (2026-09-03)
- **Last commit**: 2026-09-03
- **Assets in release**: 9

## Popularity

- **Stars**: 3,076 · **Forks**: 80 · **Open issues**: 254 · **Contributors**: 22

## Totals (cumulative)

- **Releases**: 43 · **Merged PRs**: 169 · **Open PRs**: 0 · **Closed issues**: 252 · **Open issues**: 2 · **Commits**: 1469

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 1 | 7 | 0 | 1 | 0 | 16 |
| last60d | 2026-07-13 | 1 | 7 | 0 | 3 | 1 | 17 |
| 90d | 2026-06-13 | 1 | 8 | 0 | 5 | 1 | 18 |
| last180d | 2026-03-15 | 4 | 24 | 0 | 20 | 1 | 139 |
| 360d | 2025-09-16 | 6 | 41 | 0 | 39 | 2 | 176 |
| last720d | 2024-09-21 | 11 | 60 | 0 | 97 | 2 | 247 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [termscp-v1.2.0-aarch64-apple-darwin.tar.gz](https://github.com/veeso/termscp/releases/download/v1.2.0/termscp-v1.2.0-aarch64-apple-darwin.tar.gz) | 17.8 MiB | `native/darwin/arm64` |
| [termscp-v1.2.0-aarch64-pc-windows-msvc.zip](https://github.com/veeso/termscp/releases/download/v1.2.0/termscp-v1.2.0-aarch64-pc-windows-msvc.zip) | 18.2 MiB | `native/win/arm64` |
| [termscp-v1.2.0-aarch64-unknown-linux-musl.tar.gz](https://github.com/veeso/termscp/releases/download/v1.2.0/termscp-v1.2.0-aarch64-unknown-linux-musl.tar.gz) | 23.9 MiB | `native/linux/arm64/musl` |
| [termscp-v1.2.0-x86_64-apple-darwin.tar.gz](https://github.com/veeso/termscp/releases/download/v1.2.0/termscp-v1.2.0-x86_64-apple-darwin.tar.gz) | 16.9 MiB | `native/darwin/x64` |
| [termscp-v1.2.0-x86_64-pc-windows-msvc.zip](https://github.com/veeso/termscp/releases/download/v1.2.0/termscp-v1.2.0-x86_64-pc-windows-msvc.zip) | 19.2 MiB | `native/win/x64` |
| [termscp-v1.2.0-x86_64-unknown-linux-musl.tar.gz](https://github.com/veeso/termscp/releases/download/v1.2.0/termscp-v1.2.0-x86_64-unknown-linux-musl.tar.gz) | 25.0 MiB | `native/linux/x64/musl` |
| [termscp.1.2.0.nupkg](https://github.com/veeso/termscp/releases/download/v1.2.0/termscp.1.2.0.nupkg) | 4.0 KiB | `other` |
| [termscp_1.2.0-1_amd64.deb](https://github.com/veeso/termscp/releases/download/v1.2.0/termscp_1.2.0-1_amd64.deb) | 16.2 MiB | `runtime/deb/amd64` |
| [termscp_1.2.0-1_arm64.deb](https://github.com/veeso/termscp/releases/download/v1.2.0/termscp_1.2.0-1_arm64.deb) | 15.0 MiB | `runtime/deb/arm64` |

## Distribution status

Reported by **21** distros on [repology.org](https://repology.org/project/termscp). **9** are ✅ on the latest upstream release, **11** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Arch | `1.2.0` | ✅ latest |
| Homebrew | `1.2.0` | ✅ latest |
| Nix unstable | `1.1.1` | ⚠️ outdated |
| openSUSE Tumbleweed | `1.1.1` | ⚠️ outdated |

## Improve this data

Install metadata for termscp lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `termscp` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/termscp.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260911.yml` · 2026-09-11T19:34:05Z._
