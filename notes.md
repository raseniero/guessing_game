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

## Recommended VS Code Extensions

### 1. C/C++
Provides IntelliSense, debugging, and code browsing for C and C++.

### 2. C/C++ Extension Pack
A collection of popular C/C++ extensions, including C/C++, CMake Tools, and more, for a complete C/C++ development experience.

### 3. Code Runner
Run code snippets or files for multiple languages (including Rust, C/C++, Python, Java, etc.) directly in VS Code.

### 4. CodeLLDB
A powerful debugger for Rust and C/C++ using LLDB, supporting breakpoints, variable inspection, and more.

### 5. Dependi
Visualizes and manages dependencies in your project, making it easier to understand and maintain complex dependency graphs.

### 6. Error Lens
Highlights errors and warnings inline in your code, making issues more visible and easier to fix.

### 7. Even Better TOML
Provides rich TOML file support with syntax highlighting, validation, and auto-completion (useful for editing Cargo.toml).

### 8. GitHub Copilot
AI-powered code completion and suggestions, helping you write code faster and smarter.

### 9. GitLens
Enhances Git capabilities in VS Code, showing code authorship, history, and powerful Git insights inline.

### 10. Markdown All in One
All-in-one Markdown editing experience with shortcuts, preview, TOC generation, and more.

### 11. Rust Test Explorer
Integrates Rust tests with the Test Explorer UI, allowing you to run and debug tests from a visual interface.

### 12. Test Adapter Converter
Allows adapters for different test frameworks to work with the Test Explorer UI, improving test integration.

### 13. Test Explorer UI
Provides a unified UI for running and managing tests from various languages and frameworks in VS Code.

### 14. Todo Tree
Finds and displays TODO, FIXME, and other comment tags in a tree view, making it easy to track tasks in your codebase.