# Plus Editor

一个基于 `MavonEditor` 开发的针对 Plus 程序的 Markdown 编辑器。

## 使用

```bash
## Yarn
yarn add @slimkit/plus-editor

## NPM

npm i @slimkit/plus-editor
```

入口新增 `api-host` 参数，`必须`！设置 Plus 的 API 基本地址。

## 定制内容

针对文件上传功能进行定制！

其他使用方法不变，唯一改变的是 `$img2Url` 的 Hook, 第二个参数由 URL 修改为文件ID

> 使用方法参考 [编辑器文档](README-origin.md)
