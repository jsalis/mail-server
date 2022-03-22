# test-rust

## Installation

1. Install the Rust toolchain https://rustup.rs/
2. `cargo install cargo-watch`
3. `cargo install cargo-audit`

## Development

Run `cargo watch -x check` to watch for file changes. This will run `cargo check` after every code change.
Alternatively, run `cargo watch -x check -x test -x run` for a full development loop.

### Testing

Run `cargo test` to run the tests.

### Formatting

Run `cargo fmt` to run the formatter.

### Security Audit

Run `cargo audit` to run an audit.

### Documentation

Run `cargo doc --open` to auto-generate docs.
