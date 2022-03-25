# mail-server

## Installation

- [Rust](https://rustup.rs/)
- [Docker](https://docs.docker.com/engine/install/)

## Development

Install crate with `cargo install cargo-watch`.

Run `cargo watch -x check` to watch for file changes. This will run `cargo check` after every code change.

Alternatively, run `cargo watch -x check -x test -x run` for a full development loop.

### Testing

Run `cargo test` to run the tests.

### Formatting

Run `cargo fmt` to run the formatter.

### Documentation

Run `cargo doc --open` to auto-generate docs.

### Security Audit

Install crate with `cargo install cargo-audit`.

Run `cargo audit` to run an audit.

### Expand Macros

Install the nightly compiler with `rustup toolchain install nightly --allow-downgrade`.

Install crate with `cargo install cargo-expand`.

Run `cargo +nightly expand` to expand macros.
