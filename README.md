# tmatrix

> The Matrix has you.

A cinematic Matrix-style digital rain animation for your terminal, written in Rust. Fast, minimal, and mesmerizing.

![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)
![Built with Rust](https://img.shields.io/badge/built%20with-Rust-orange.svg)

---

## Install

```sh
cargo install tmatrix
```

Or build from source:

```sh
git clone https://github.com/deatherving/tmatrix
cd tmatrix
cargo build --release
./target/release/tmatrix
```

---

## Usage

```sh
tmatrix [OPTIONS]
```

| Option | Description |
|---|---|
| `-l`, `--letters` | Letters mode — A–Z, a–z, 0–9 (default) |
| `-b`, `--binary` | Binary mode — 0 and 1 only |

---

## Controls

| Key | Action |
|---|---|
| `q` / `Esc` / `Enter` | Quit |
| `Ctrl+C` | Quit |

---

## Font

For the closest match to the original Matrix film aesthetic, set your terminal font to **Matrix Code NFI** (available as a free download).

---

## Acknowledgements

Inspired by [unimatrix](https://github.com/will8211/unimatrix) by Will8211.

---

## License

MIT
