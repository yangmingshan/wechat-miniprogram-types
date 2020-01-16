# wechat-miniprogram-types

微信小程序 TypeScript 类型定义。直接拷贝自[微信开发者工具](https://developers.weixin.qq.com/miniprogram/dev/devtools/devtools.html)生成的 TypeScript 类型定义，未作修改。

## ⚠️ 废弃：请使用官方版本 [miniprogram-api-typings](https://github.com/wechat-miniprogram/api-typings)

## 安装

你可以通过 [yarn](https://yarnpkg.com/) 或 [npm](https://npmjs.com/) 安装

```bash
$ yarn add wechat-miniprogram-types --dev
$ npm install wechat-miniprogram-types --save-dev
```

## 使用

```json
// tsconfig.json
{
  "compilerOptions": {
    "typeRoots" : [
      "./node_modules/@types",
      "./node_modules/wechat-miniprogram-types"
    ]
  }
}
```

## 许可证

见源文件头部。
