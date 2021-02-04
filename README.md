# webAssembly
安装cmake: `brew install cmake`<br />
安装emsdk: https://emscripten.org/docs/getting_started/downloads.html <br />
由于环境变量问题，变更文件夹后执行`source "/Users/chenpeng/emsdk/emsdk_env.sh"` 以临时变更可用的环境变量 <br />
C转webAssembly: `emcc math.c -Os -s WASM=1 -s SIDE_MODULE=1 -o math.wasm`
