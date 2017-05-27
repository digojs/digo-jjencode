# digo-jjencode
[digo](https://github.com/digojs/digo) 插件：使用 [jjencode](http://utf-8.jp/public/jjencode.html) 加密 JavaScript 文件。

## 安装
```bash
npm install digo-jjencode -g
```

## 使用
```js
digo.src("*.js").pipe("digo-jjencode");
```

### 源映射(Source Map)
本插件不支持生成源映射。

## 用法
```js
digo.src("*.js").pipe("digo-jjencode", {
    char: "$",      // 加密的字符
}
```
