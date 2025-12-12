# Project Context: Guessing Game

## Project Overview
This is a simple command-line number guessing game written in Rust. The application generates a random secret number between 1 and 100 and prompts the user to guess it, providing feedback ("Too small" or "Too big") until the correct number is guessed.

## Key Technologies
- **Language:** Rust
- **Dependencies:** `rand` (v0.9.1) for random number generation.

## Project Structure
- `src/main.rs`: Contains the entry point and the complete game logic.
- `Cargo.toml`: Defines the project dependencies.
- `notes.md`: Contains developer notes regarding Rust commands and environment setup.

## Building and Running
This project uses standard Cargo commands.

### Run the Game
```bash
cargo run
```

### Build
```bash
cargo build
```

### Check
```bash
cargo check
```

## Development Notes
- Currently, the game prints the secret number to the console at the start for debugging purposes.
