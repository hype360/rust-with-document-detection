# Rust with Document Detection

This project demonstrates how to use Rust with WebAssembly for document detection.

## Prerequisites

- Rust and Cargo: [Install Rust](https://www.rust-lang.org/tools/install)
- wasm-pack: [Install wasm-pack](https://rustwasm.github.io/wasm-pack/installer/)

## Building the Project

1. Clean the project:
    ```sh
    cargo clean
    ```

2. Build the project:
    ```sh
    cargo build
    ```

3. Install `wasm-pack`:
    ```sh
    cargo install wasm-pack
    ```

4. Build the WebAssembly package:
    ```sh
    wasm-pack build --target web
    ```

## Running the Project

1. Serve the project locally:
    ```sh
    serve -l 5000
    ```

2. Open your browser and navigate to `http://localhost:5000` to see the example in action.

## Running the Project with One Command

```sh
cargo clean
cargo build
cargo install wasm-pack
wasm-pack build --target web
serve -l 5000
```