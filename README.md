# 1986 Conway's Game of Life with WebAssembly [(DEMO link)](https://conway1986.jeje.work/)

This project is an implementation of [Conway's Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life), a cellular automaton devised by the British mathematician John Horton Conway in 1970. The game is a zero-player game, meaning that its evolution is determined by its initial state, requiring no further input.

## Features

- Implemented in Rust for performance and safety.
- Compiled to WebAssembly for running in the browser at near-native speed.
- Retro 1986-style pixel-art interface and typography for a throwback feel.

## Getting Started

### Prerequisites

To build and run this game locally, you will need:

- Rust programming language: [Installation guide](https://www.rust-lang.org/tools/install)
- `wasm-pack`: [Installation guide](https://rustwasm.github.io/wasm-pack/installer/)
- A modern web browser with JavaScript and WebAssembly support.

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/jjh4450/1986_conwaysGameOfLife_with_wasm.git
   ```
2. Navigate to the project directory:
   ```sh
   cd 1986_conwaysGameOfLife_with_wasm
   ```
3. Build the WebAssembly module:
   ```sh
   wasm-pack build conway-logic
   ```
4. Install JavaScript dependencies:
   ```sh
   npm install
   ```

### Running the Game

To launch the game, use the following command from the project directory:

```sh
npm run dev
```

This will start a local server, and you can play the game by navigating to `http://localhost:8080` in your web browser.

## Contributing

Contributions to improve Conway's Game of Life are welcome. Please feel free to fork the repository, make your changes, and create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE_MIT](./LICENSE)

## Help and Support

If you have any questions or need assistance, please contact us at [jjh4450git@gmail.com](mailto:jjh4450git@gmail.com)