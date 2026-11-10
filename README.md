# rust

Rust 1.99.1: rustc, cargo, rustdoc and the standard library

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install rust
```

| | |
|---|---|
| Version | 1.99.1 |
| Licence | MIT OR Apache-2.0 |
| Upstream | https://www.rust-lang.org |
| Needs | [`gcc`](https://github.com/Artfical/tpkg-gcc), [`ca-certificates`](https://github.com/Artfical/tpkg-ca-certificates) |
| Needs tOS build | 620 or newer |
| Size | 205696491 bytes (601871786 unpacked) |
| SHA-256 of the `.tpkg` | `cbb4af399b516b7a069a89a59abfedd7b98af11313055d214520e5911d15016d` |

## Commands it adds

| Command | Runs |
|---|---|
| `rustc` | `bin/rustc-tos` |
| `cargo` | `bin/cargo-tos` |
| `rustdoc` | `bin/rustdoc` |

## Download

The package file (`rust-1.99.1.tpkg`) and the sources it was built from are the assets of the
[v1.99.1 release](https://github.com/Artfical/tpkg-rust/releases/tag/v1.99.1).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- (none: see the upstream page above)

Check a download: `sha256sum rust-1.99.1.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: MIT OR Apache-2.0. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
