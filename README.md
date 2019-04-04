# wasm test repo

1. run this command on zsh: `docker run --rm -v $(pwd):/src trzeci/emscripten emcc hello.c -s WASM=1 -o hello.html`

2. launch server: `$ docker run --rm -p 8080:8080 -v $(pwd):/src trzeci/emscripten emrun --no_browser --hostname 0.0.0.0 --port 8080 dist/`
