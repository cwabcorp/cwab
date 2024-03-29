# Cwab

<img src="https://user-images.githubusercontent.com/3753178/233761007-ececf241-e084-4627-abf4-0250d55772bb.svg" alt="Adorable 2D cartoon crab fumbling with papers" width="512" height="512" />

Correct, efficient, and simple. Lets process some jobs.

[![Crates.io][crates-badge]][crates-url]
[![MIT licensed][mit-badge]][mit-url]
[![Build Status][actions-badge]][actions-url]

[crates-badge]: https://img.shields.io/crates/v/cwab.svg
[crates-url]: https://crates.io/crates/cwab
[mit-badge]: https://img.shields.io/crates/l/cwab
[mit-url]: https://github.com/cwabcorp/cwab/blob/master/LICENSE
[actions-badge]: https://github.com/cwabcorp/cwab/workflows/Build%20and%20test/badge.svg
[actions-url]: https://github.com/cwabcorp/cwab/actions/workflows/deploy.yml

# Installation

The `cwab` library is installed by adding the following to your `Cargo.toml`

```toml
cwab = "^0.6"
```

You'll also need to run the following to install the CLI

```bash
cargo install cwab
```

# Features

- [x] Reliable job dispatch
- [x] Error handling with retries
- [x] Scheduled jobs
- [x] An easy to use Rust API
- [x] Middleware support
- [x] Batched jobs
- [x] Cron support
- [x] Expiring jobs
- [x] Unique jobs
- [x] Encryption
- [x] Rate limiting
- [x] Parallelism

# Documentation

You can find our documentation [here](https://github.com/cwabcorp/cwab/wiki)

Library documentation can be found on [docs.rs](https://docs.rs/cwab/latest/cwab/)

# Contributing

If you want to contribute, I recommend looking at our [good first issues](https://github.com/cwabcorp/cwab/contribute). Our [contributing file](.github/CONTRIBUTING.md) has some tips for getting started.
