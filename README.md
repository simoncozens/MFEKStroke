# Stroke
A set of utilities for stroking paths in font glyphs written in rust.

It is a part of the MFEQ editor project.

Stroke takes unified font object files and applies path stroking algorithms to them. Currently only pattern along path is provided.

## Pattern Along Path

This was generated with the following command:

```
cargo run -- --pattern simple.glif --path Q_.glif --out output.glif --sx 0.3 --sy 0.1 --stretch true --subdivide 2 --mode repeated
```
