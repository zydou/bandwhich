# bandwhich

This repository uses GitHub Actions to build the `bandwhich` tool.

The [official repository](https://github.com/imsnif/bandwhich) includes binary releases for the following architectures:

- x86_64-unknown-linux-musl
- x86_64-unknown-linux-gnu
- x86_64-apple-darwin
- x86_64-pc-windows-msvc

However, it lacks support for other architectures such as `aarch64-apple-darwin`. This repository aims to build these missing architectures. Specifically, it builds the following architectures:

- aarch64-unknown-linux-musl
- aarch64-unknown-linux-gnu
- aarch64-apple-darwin

In addition, it also directly downloads the `bandwhich` binary from the official source and uploads it to GitHub Release of the following architectures for convenience:

- x86_64-unknown-linux-musl
- x86_64-unknown-linux-gnu
- x86_64-apple-darwin
