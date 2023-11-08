Rust WASM builder
=================

> WASM builder for rust project using docker

## Use

```
docker run --rm -v `pwd`:/src -w /src rust-wasm-builder cargo build --target wasm32-wasi
```
