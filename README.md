# 서버 측의 Rust 및 WebAssembly
서버 사이드의 rust에서 javascript를 호출하거나 javascript에서 rust를 호출하는 방법을 찾아 보던 중 다음 두 가지의 기사를 찾았다. 
* [Rust and WebAssembly on the server side](https://rust-by-example-ext.com/webassembly/nodejs.html)
* [Call Javascript from Rust](https://rust-by-example-ext.com/webassembly/nodejshelper.html)


둘 다 [wasm-bindgen](https://github.com/rustwasm/wasm-bindgen)을 의존하고 있었다.  이 두가지 예제는 rust 1.50.0 버전과 Nodejs 12.18.3을 필요로 한다. 그리고 다음의 nodejs 모듈을 필요로 한다. 
```shell
npm install wasmedge-core
npm install -g rustwasmc
```

윈도우즈에서는 설치가 되지 않아서 Ubuntu에서 설치를 했다. 그러나 빌드할 때는 실행이 되지 않았다. 

> 2년 전에 업데이트 되고 나서는 지금은 업데이트 되지 않고 있다. 




