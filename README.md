# Minippy
A tiny toy linter influenced by Clippy

## Prerequisites
- Cargo
- rustc private crates

```
$ rustup component add rust-src rustc-dev llvm-tools-preview
```

VSCode Setting
```
  "rust-analyzer.rustc.source": "discover",
```

## Usage
```
$ cargo run tests/add_zero.rs
```

## Screenshots
![screenshot1](screenshot1.png)



