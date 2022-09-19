## About

This was made by following the Conway's Game of Life tutorial from the
[`wasm-pack` tutorials][tutorials]. I made this for the purpose of exploring
optimizations that are possible for the [`LifeEngine` project][lifeengine].

[tutorials]: https://rustwasm.github.io/docs/wasm-pack/tutorials/index.html
[lifeengine]: https://github.com/MaxRobinsonTheGreat/LifeEngine

### 🛠️ Build with `wasm-pack build`

```
wasm-pack build
```

### 🔬 Test in Headless Browsers with `wasm-pack test`

```
wasm-pack test --headless --firefox
```

## 🔋 Batteries Included

* [`wasm-bindgen`](https://github.com/rustwasm/wasm-bindgen) for communicating
  between WebAssembly and JavaScript.
* [`console_error_panic_hook`](https://github.com/rustwasm/console_error_panic_hook)
  for logging panic messages to the developer console.
* [`wee_alloc`](https://github.com/rustwasm/wee_alloc), an allocator optimized
  for small code size.
* `LICENSE-APACHE` and `LICENSE-MIT`: most Rust projects are licensed this way, so these are included.

