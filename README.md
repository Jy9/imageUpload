# ImageUpload - 图片转 Base64 工具

一个将图片文件转为 Base64 编码的工具函数，监听 input file 控件的 change 事件，读取图片并返回 Base64 字符串。

## 功能特性

- 图片类型校验
- 文件大小限制（4MB）
- FileReader 异步读取
- 回调函数返回 file 对象和 base64 数据

## 技术栈

- 原生 JavaScript
- FileReader API

## 使用方式

```javascript
imageUpload(inputElement, function(file, base64) {
    console.log(file, base64);
});
```
