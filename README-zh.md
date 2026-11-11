# 快速文档 (Quick-Documentation)
编写文档真是一件麻烦事。

本项目借助了人工智能 (AI) 来辅助制作。

[预览](https://emocez.github.io/Quick-Documentation/?README)

[返回 GitHub](https://github.com/EMOCEZ/Quick-Documentation/tree/main)

# 文档示例
[被诅咒的黄金 (cursed gold)](https://emocez.github.io/Quick-Documentation/?cursedgold)

[圆周率 (pi)](https://emocez.github.io/Quick-Documentation/?pi)

# 如何提交新文档？

1. 点击页面顶部的“Issues”选项卡，然后点击“New Issue”（新建议题）。

2. 在标题栏中，输入您想为该文档设定的简短英文名称（例如 `ender-dragon`；仅限使用字母、数字和连字符）。

3. 在正文区域直接粘贴您的 Markdown 内容（支持所有标准的 Markdown 语法）。

提交后，我会将其保存为 `ender-dragon.md` 并进行部署，届时您即可通过 `?ender-dragon` 访问该文档。

注意：为了保持仓库整洁，请勿在文档中包含 `<script>` 标签（虽然技术上可能可以运行，但我会将其移除）。建议仅使用文本、图片和表格。

# 个性化
你可以点击目录标题旁边的日月按钮切换暗色/亮色模式，也可以长按上传背景

# 创作者功能

## 一个卡片
```cards
被诅咒的金锭 | 模组介绍 | ?cursedgold | 🧊
pi | pi介绍 | ?pi | 🧊🧊🧊
```

## 警告

> [!WARNING]
> 棍母来袭

> [!TIP]
> 棍母来袭

> [!NOTE]
> 棍母来袭

> [!DANGER]
> 棍母来袭

> [!INFO]
> 棍母来袭

## 引用
```embed
pi.md
```

## 步骤条
```steps
安装依赖
配置 API Key
运行示例脚本
打开浏览器验证
```

## 行内徽章与键帽
当前版本 {{badge:666}}

保存请按 [[Ctrl+S]]，撤销按 [[Ctrl+Z]]。

## 窗口定义和弹出
```windoww
<!---win-danger--->
# oh no
that bad
```
```windowt
<!---win-ok--->
# oh yes
good job
```
<a href="#" data-window="win-danger">危险弹窗</a>

<a href="#" data-window="win-ok">普通弹窗</a>
