# typescript-react-snippets

为 Typescript 下开发 React 组件打造的 VSCode Snippets 插件

## Features

1. 使用简单的命令自动生成 React 语法（类似于 emmet）
2. 提炼出大型项目中常用的 React 语法，后续不断的更新

## Install

[Install the extension here](https://marketplace.visualstudio.com/items?itemName=xiangjun.typescript-react-snippets)

## Usage

首次使用 VSCode Snippets 功能，请配置`"editor.tabCompletion": "on"`。

像 VSCode 自带的代码补全那样，比如键入`rcc`可以看到对应的 React 模板，使用`tab`键应用。

## Available Snippets

| Trigger | Description                                    |
| ------- | ---------------------------------------------- |
| rcc     | React class component skeleton.                |
| rfc     | React function component skeleton.             |
| rccl    | React class component with lifecycle skeleton. |
| rus     | UseState hooks.                                |
| rue     | UseEffect hooks.                               |
