# 🤖 ChatGPT Prompt Manager (CPM)

**[English](#english) | [中文说明](#中文说明)**

> **一句话介绍：** 像写代码自动补全一样，在 ChatGPT 里飞速插入你的常用指令。

---

<a name="english"></a>
## 🇬🇧 English Description

**ChatGPT Prompt Manager** turns your ChatGPT input box into a powerful IDE-like editor. It allows you to manage and autocomplete your frequently used prompts instantly, without switching windows or copying/pasting.

### 🌟 Why do you need this?
* **Tired of copy-pasting?** Stop keeping your prompts in Notion/Notes.
* **Want speed?** Type `trans` and hit `Tab` to insert a complex translation instruction immediately.
* **Hate formatting issues?** No more accidental "double text" or cursor jumping issues common in other plugins.

### ✨ Key Features

* **⚡ Smart Autocomplete**: Just type a keyword (e.g., `polish`), and a menu appears. Press `Tab` to insert.
* **🧠 Hybrid Matching**:
    * **Suffix**: Typing `...translate` triggers the "Translate" prompt.
    * **Fuzzy**: Typing `trans` finds "English Translation".
* **☁️ Cloud Sync**: Sync your prompts across all your computers using GitHub Gist.
* **🎨 Visual Toolbar**: A clean toolbar above the chat box for quick mouse access.

### 🚀 Installation

1.  Install **Tampermonkey** extension for your browser.
2.  **[Click Here to Install Script]** (Replace with your link).
3.  Refresh ChatGPT, and start typing!

---

<a name="中文说明"></a>
## 🇨🇳 中文说明

**ChatGPT Prompt Manager (CPM)** 是一款能让你在 ChatGPT 输入框里享受 **“代码补全级体验”** 的效率工具。

它让你不再需要从备忘录里反复复制粘贴 Prompt。只需输入一个关键词，指令就会自动弹出来。

### 🌟 它是用来干嘛的？

* **自动补全**：输入 `润色`，按下 `Tab`，立刻变成一段 200 字的专业学术润色指令。
* **智能触发**：不需要死记硬背快捷键。输入 `...帮我翻译`，脚本会自动识别出你想用“翻译”指令。
* **云端同步**：在家里电脑存的 Prompt，去实验室电脑上也能用（通过 GitHub Gist 同步）。

### ✨ 核心功能

* **🧠 智能混合匹配**：
    * **后缀触发**：输入“这句话请**翻译**”，自动匹配“翻译”Prompt。
    * **模糊检索**：输入“**润色**”，可以匹配到“学术**润色**”或“英文**润色**”。
    * **原生分词**：内置智能分词引擎，精准识别中文词汇，不会胡乱触发。
* **⚡ 丝滑的交互**：
    * **Tab 上屏**：按 `Tab` 键确认，自动删除触发词并填入内容，杜绝“翻译翻译”这种重复文字的尴尬。
    * **所见即所得**：提供顶部可视化按钮，不想打字时也可以直接点击。
* **☁️ 数据安全**：数据存储在您自己的 GitHub Gist 中，支持私有存储，安全可靠。

### 🚀 快速开始

1.  安装油猴插件 **Tampermonkey** (Chrome/Edge/Firefox)。
2.  安装本脚本。
3.  刷新 [ChatGPT](https://chatgpt.com/) 页面，即可在输入框上方看到工具栏。

### ⌨️ 怎么用？

1.  **打字即触发**：直接在输入框打字。例如你有“润色”这个 Prompt，输入“润色”即可看到弹窗。
2.  **选择**：使用键盘 `↑` / `↓` 键切换候选项。
3.  **上屏**：按下 `Tab` 键插入内容（脚本会自动替换掉你刚才输入的触发词）。
4.  **管理**：在工具栏的按钮上**右键点击**可进行编辑或删除。

### 🔄 同步设置 (Gist)

1.  点击工具栏的 **⚙️ 设置** 按钮。
2.  **Gist ID**：在 GitHub 创建一个 Gist，复制 URL 末尾的 ID 填入。
3.  **Token**：在 GitHub Developer Settings 生成一个 Personal Access Token (Classic)，勾选 `gist` 权限。
4.  点击 **保存** 即可使用上传/下载功能。

### 📄 License

MIT License
