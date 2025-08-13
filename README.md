# Pragmatic Rust

A pragmatic list of Rust code and resources.

## Crates

### Logging, Debugging

- [log](https://docs.rs/log/latest/log/): a lightweight logging facade for Rust, allowing you to use different logging implementations.
- [env_logger](https://docs.rs/env_logger/latest/env_logger/): a simple logger that can be configured via environment variables, for use with the logging facade exposed by the [log](https://docs.rs/log/latest/log/) crate.
- [pretty_env_logger](https://crates.io/crates/pretty_env_logger): a simple logger that is built on top of [env_logger](https://docs.rs/env_logger/latest/env_logger/) to output prettily formatted log messages.

## Emacs for Rust

- Major modes:
  + [rust-mode](https://github.com/rust-lang/rust-mode): The "official" Emacs major mode for editing Rust code.
  + [rustic](https://github.com/emacs-rustic/rustic): The "feature-richer" Emacs major mode for Rust, built on top of [rust-mode](https://github.com/rust-lang/rust-mode).
