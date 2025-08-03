# Deno Note

## 初始化项目

```sh
my_project
├── deno.json // 来配置你的项目, 主配置文件
├── main_test.ts // main.ts 文件是你编写应用代码的地方, 主入口文件
└── main.ts // main_test.ts 文件是你编写测试的地方, 存放测试用例
```

## 配置 vscode 环境

```sh
在“扩展”选项卡中，搜索“Deno”并安装DenoLand 提供的扩展
接下来，按 Ctrl+Shift+P 打开命令面板，然后输入 Deno: Initialize Workspace Configuration。选择此选项为你的工作区配置 Deno
工作区中将创建一个名为 .vscode/settings.json 的文件，其中包含以下配置
{
  "deno.enable": true
}
```

