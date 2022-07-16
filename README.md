
# wasm-game-of-life

This project is meant to just test out how WASM works with Rust. 🎉

## ⚒ Development

1. Start by making changes to the `./src` folder.
2. This next step is easiest with two terminals:
   1. First terminal: Run `yarn start` in the root directory of this project
   2. Second terminal: Run `yarn refresh` whenever changes are made to the `./src` folder. This will rebuild the package that is used in `./client`, then upgrade the wasm package. The webpack dev server should automatically pick up these changes in the first terminal window and automatically refresh the browser.
   
## 🔋 Batteries Included

* [`wasm-bindgen`](https://github.com/rustwasm/wasm-bindgen) for communicating
  between WebAssembly and JavaScript.
* [`console_error_panic_hook`](https://github.com/rustwasm/console_error_panic_hook)
  for logging panic messages to the developer console.
* [`wee_alloc`](https://github.com/rustwasm/wee_alloc), an allocator optimized
  for small code size.