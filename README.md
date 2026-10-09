# Diagon — Releases

Official release downloads for **[Diagon](https://www.soverain.cz/diagon)** — a
diagrams-as-code desktop app by [Soverain s.r.o.](https://www.soverain.cz)
Write a few objects, watch the diagram lay itself out, drag nodes and the code
updates. Diagon has no AI of its own; the AI assistant you already use can be
connected to draw in it (see
[AI assistants](https://www.soverain.cz/docs/diagon/assistants)).

**Download & install guides: [soverain.cz/diagon/download](https://www.soverain.cz/diagon/download)**

Or grab the latest installer straight from the
[Releases](https://github.com/soverain-cz/diagon-releases/releases) page:

| Platform | File |
|---|---|
| Windows 10/11 (64-bit) | `Diagon-Setup-<version>.exe` |
| Linux (any distro) | `Diagon-<version>.AppImage` |
| Debian / Ubuntu | `diagon_<version>_amd64.deb` |
| macOS | in the works |

Each release ships a `SHA256SUMS` file — verify your download with
`sha256sum -c SHA256SUMS`.

> The installers are about 100 MB (the AppImage about 130 MB). Up to 1.2.1 they
> were about 2 GB, because an AI model was bundled inside; 1.3.0 removed it — see
> the [release notes](https://www.soverain.cz/docs/diagon/release-notes).

## About this repository

This repository hosts **release binaries only**. Diagon is commercial,
proprietary software — see the licence shipped with the installer and
[soverain.cz/legal](https://www.soverain.cz/legal). There is no public source
code. For support: [hello@soverain.cz](mailto:hello@soverain.cz) or
[soverain.cz/support](https://www.soverain.cz/support).
