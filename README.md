# wasm test repo

1. run this command on zsh: `docker run --rm -v $(pwd):/src trzeci/emscripten emcc hello.c -s WASM=1 -o hello.html`
