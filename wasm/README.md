# wasm demo

``` bash
yum install git cmake python3
git clone https://github.com/juj/emsdk.git
cd emsdk
./emsdk install latest
./emsdk active latest
source ./emsdk_env.sh
```

把hello.c编译成html
``` bash
emcc hello.c -s WASM=1 -o hello.html
```

创建一个webserver
``` bash
emrun --no_browser --port 8080 .
```
浏览器打开192.168.1.4:8080