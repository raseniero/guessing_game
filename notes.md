# Rust Learning Notes

## Useful Commands

### Generate and Open Documentation

```
cargo doc --open
```
This command builds the documentation for all dependencies and your project, then opens it in your default web browser. 

### Open Rust Local Documentation

```
rustup doc
```
This command opens the local Rust documentation index in your default web browser. It's a quick way to access the official Rust docs offline.

### Open The Rust Programming Language Book

```
rustup doc --book
```
This command opens the official Rust Programming Language book ("The Book") in your default web browser, using the locally installed documentation. 

### Update Dependencies Verbosely

```
cargo update --verbose
```
This command updates dependencies in your Cargo.lock file to the latest allowed versions, providing detailed output about the update process. 

### Invert Dependency Tree for a Specific Package

```
cargo tree --invert --package rand@0.9.1
```
This command shows which packages depend on `rand` version 0.9.1, displaying the reverse dependency tree. It's useful for tracking down why a specific version of a crate is included in your project. 

### Format Rust Code

```
cargo fmt
```
This command formats all Rust source files in your project according to the default style guidelines, helping keep your code clean and consistent. 

### Explain Rust Compiler Errors

```
rustc --explain <ERROR_CODE>
```
This command provides a detailed explanation of a specific Rust compiler error code (e.g., E0382), helping you understand and resolve compiler errors more effectively. 