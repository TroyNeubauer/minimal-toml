[![Crates.io](https://img.shields.io/crates/v/minimal-toml.svg)](https://crates.io/crates/minimal-toml)
[![Crates.io](https://img.shields.io/docsrs/minimal-toml)](https://docs.rs/minimal-toml)
[![main workflow](https://github.com/TroyNeubauer/minimal-toml/actions/workflows/main.yml/badge.svg)

# minimal-toml

A no_std toml deserializer for embedded systems
Full toml support for deserializing into structs that implement `serde::Deserialize`.

Requires no memory allocations and is likely much faster than toml-rs.
Supports deserialization only


License: MIT
