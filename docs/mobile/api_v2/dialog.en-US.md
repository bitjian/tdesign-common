---
title: Dialog 对话框
description: 一种打断当前操作的模态视图，用于显示重要提示或请求用户进行重要操作
spline: base
isComponent: true
toc: false
---

## 代码演示

按钮的样式，默认使用 `variant = text`，如果任意按钮改变了 `variant`，那么全部按钮都改变成这个。

### 组件类型

#### 反馈类对话框

用于用户进行了一个操作，需传达重要信息，告知用户当前状况的情况。

{{ feedback }}

#### 确认类对话框

用于用户进行了一个操作，后果比较严重，需要用户二次确认的情况。 例如 退出、删除、清空等操作

{{ confirm }}

#### 输入对话框

用于用户进行了一个操作，需输入下一步操作的必要信息。 例如 输入密码

{{ input }}

#### 带图片对话框

对话框中可以插入图片元素，并且自定义位置。

{{ image-dialog }}

### 组件状态

文字按钮、水平基础按钮、垂直基础按钮、多按钮、附带关闭按钮

{{ multi-state }}

### 组件用法

命令行调用

{{ plugin }}