---
title: Mod文件底层方面教程
description: 嗯，就是底层
published: true
date: 2025-06-16T14:13:05.915Z
tags: 
editor: markdown
dateCreated: 2025-06-16T14:11:49.626Z
---

> 该教程适用于 **本体版本 (v1.16.8.38f9)/本体测试版 (v1.16.9)**
{.is-success}

## 第一章：创建你的第一个 Mod

### 步骤 1：打开游戏启动器

打开《钢铁雄心 IV》的游戏启动器。

### 步骤 2：创建 Mod

1. 点击左侧菜单中的【所有已安装 Mod】
2. 选择下方的【上传 Mod】
3. 然后点击【创建 Mod】，进入如下页面：

> **填写信息内容包括：**
> - Mod 名称
> - Mod 文件夹名称（自动生成）
> - 简介与标签（可选）

填写完毕后，点击【创建 Mod】。

### 步骤 3：查看 Mod 路径

系统将为你创建好第一个 Mod（此时 Mod 内容仍为空）
Mod 文件的默认路径如下：`C:\Users\你的用户名\Documents\Paradox Interactive\Hearts of Iron IV\mod\你的MOD
`

你创建的 Mod `.mod` 文件和对应的文件夹都将在这里生成。

---

> 💡 **提示：**  
> 当前 Mod 文件夹中是空的，将在后续内容中介绍 HOI4 的代码文件构成、必要文件目录及其功能。

---

## 第二章：推荐编码工具

现在，你已经拥有了一个崭新的 Mod，下一步就是选择一个好用的代码编辑工具。

### 推荐工具一：Visual Studio Code（VSC）

#### ✅ 安装与配置步骤：

1. 打开浏览器，搜索并下载安装 [Visual Studio Code](https://code.visualstudio.com/)
2. 启动软件后点击左侧【扩展】按钮（或快捷键 `Ctrl+Shift+X`）
3. 搜索并安装以下两个插件：
   - `Chinese (Simplified)`（中文语言包）
   - `CWTools`（适用于 Paradox 游戏的开发插件）
4. 在 **查看** 中（左上角）点击 **控制面板** ，在弹出的框中搜索 **Configure Display Language** 将语言更改为中文即可
5. 配置 `CWTools` 插件路径：
- 点击扩展 → 找到 CWTools → 点击右下齿轮图标 → 选择“扩展设置”
- 设置 HOI4 的本地路径，例如：
  ```
  D:\SteamLibrary\steamapps\common\Hearts of Iron IV
  ```

#### 🔧 插件作用：

| 功能 | 描述 |
|------|------|
| 预览 | 国策、地图、GUI 文件实时预览 |
| 报错提示 | 检查语法和结构（准确性一般） |

---

### 推荐工具二：Notepad++

- 下载安装 [Notepad++](https://notepad-plus-plus.org/)
- 启动后即可使用，无需插件和复杂配置

#### 📌 对比总结：

| 工具 | 优点 | 缺点 |
|------|------|------|
| **VSCode** | 插件丰富、功能强大，适合复杂项目 | 初期配置略复杂 |
| **Notepad++** | 上手快、轻便、小巧 | 功能有限，不适合大型项目开发 |


> ✅ 建议：如果你打算长期开发 HOI4 Mod，**推荐使用 VSCode**。但如果只是尝试或初学，**Notepad++ 会是轻量级的好选择**。

---





