# Rust Learning Experiments

This directory contains a structured set of Rust experiments organized by application type and complexity. The structure is designed to facilitate a progressive learning journey through different aspects of Rust development.

## Directory Structure

### CLI Applications (`cli-apps/`)
- **01-basic-cli**: Simple command parsing, basic I/O
- **02-interactive-cli**: TUI, user interaction patterns
- **03-file-processing**: Working with files, serialization
- **04-advanced-cli**: Complex args, subcommands, configuration

**Key libraries**: `clap`, `structopt`, `dialoguer`, `indicatif`, `serde`

### Packages & Libraries (`packages-libraries/`)
- **01-basic-library**: Creating a simple library crate
- **02-api-design**: Designing ergonomic APIs
- **03-documentation**: Documentation and examples
- **04-publishing**: Publishing to crates.io
- **05-ffi-bindings**: C/C++ interop and FFI

**Key tools**: `cargo-expand`, `cargo doc`, `cbindgen`, `criterion`, `proptest`

### Web Applications (`web-apps/`)
- **01-basic-server**: HTTP server basics
- **02-rest-api**: REST endpoints, JSON handling
- **03-database-integration**: Working with databases
- **04-full-stack**: Server + client-side rendering

**Key libraries**: `actix-web`, `rocket`, `axum`, `tokio`, `sqlx`, `diesel`, `yew`, `leptos`

### Desktop & Mobile Applications (`desktop-mobile/`)
- **01-basic-gui**: Simple GUI application
- **02-cross-platform**: Cross-platform considerations
- **03-native-integration**: OS-specific features
- **04-mobile-deployment**: Mobile compilation targets

**Key libraries**: `tauri`, `iced`, `egui`, `winit`, `wgpu`

### Shared Components (`shared-components/`)
- **data-models**: Common data structures
- **error-handling**: Error handling patterns
- **testing-patterns**: Testing approaches

## Usage

Each experiment directory is self-contained and can be run independently. Typically, you can navigate to an experiment directory and run:

```bash
cargo run
```

For more complex experiments, refer to the README.md file within each experiment directory for specific instructions.

## Learning Progression

The recommended learning path is:

1. Start with CLI applications to get comfortable with Rust basics
2. Move to packages/libraries to learn about API design and Rust's module system
3. Explore web applications to understand async programming in Rust
4. Finally, tackle desktop/mobile applications for GUI and platform-specific development

The shared-components directory contains patterns and code that can be referenced across different application types.
