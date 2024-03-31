# cargo-make-wix-template

This is a template project for creating a Windows installer using [WiX Toolset](http://wixtoolset.org/).

## Requirements

- [Rust](https://www.rust-lang.org/)
- [cargo-make](https://sagiegurari.github.io/cargo-make/)
- [WiX Toolset](http://wixtoolset.org/)

## Usage

1. Clone this repository.
2. Replace `wix-tutorial` with your project name.
3. Edit the environment variables in `Makefile.toml` to match your project.
4. Edit the `wix\**` files to match your project if necessary.
5. Run `cargo make wix` to build the installer.
6. The installer will be in `target\wix` directory.
