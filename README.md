# rust-wasm-vs-js-bench

# Disclaimer:  Recursive function used, so the results might not be a fair comparison!.

Test in your browser: [Demo](https://hemanth7787.github.io/rust-wasm-vs-js-bench/).


Install rust if you haven't already!

`curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh`

Install wasm-pack

`cargo install wasm-pack`

`wasm-pack build --target web`

Run a test server

`python3 -m http.server 8000`
