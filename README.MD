# Guessing Game

This is a simple command-line number guessing game written in Rust. The application generates a random secret number between 1 and 100 and prompts the user to guess it, providing feedback ("Too small" or "Too big") until the correct number is guessed.

## Project Structure

The project has the following file structure:

```text
guessing_game/
├── Cargo.lock       # Lock file for dependencies
├── Cargo.toml       # Manifest file for Rust package and dependencies
├── notes.md         # Developer notes
├── src/             # Source code directory
│   └── main.rs      # Main application entry point and game logic
└── target/          # Compiled build artifacts (generated)
```

## How to Run

To run the project, you need to have Rust installed. Navigate to the project directory and use `cargo`:

```bash
cargo run
```

This command will compile the project (if necessary) and start the game in your terminal.

## Component Versions

This project uses the following versions:

*   **Rust**: 1.88.0 (Tested on)
*   **Dependencies**:
    *   `rand`: 0.9.1 (For random number generation)
