# ark-xjsnark

A small Rust adapter that parses xJsnark arithmetic circuits and input assignments into arkworks R1CS constraints and matrices.

## Requirements

- Rust 1.85 or newer and Cargo (required by the Rust 2024 edition)
- An xJsnark-generated arithmetic circuit and its input assignment

## Configuration

Add the crate to your existing project's `Cargo.toml`:

```toml
[dependencies]
parser = { git = "https://github.com/Ottimot/ark-xjsnark.git" }
```

Then import the parser with `use parser::Parser;`.
