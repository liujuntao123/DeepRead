# 📚 DeepRead

<p align="center">
  <strong>用 AI 重塑阅读体验，将任何书籍转化为可交互的知识图谱。</strong>
</p>

<p align="center">
  <a href="[[DeepRead]](https://deepread.aizhi.site/)">访问 DeepRead 网站</a>
</p>

---

## 🚀 项目愿景 (Vision)

传统的线性阅读让我们难以在脑中建立完整的知识体系。我们常常在细节中迷失，忘记了章节与章节、概念与概念之间的联系。

**DeepRead** 致力于通过人工智能彻底改变这一现状。我们相信，最好的阅读方式是将书籍视为一个 interconnected（相互关联）的知识网络，而不是一串孤立的页面。通过将整本书喂给大语言模型，我们能解锁其内在结构，并以一个动态、可探索的 Wiki 知识库形式呈现给读者。

## ✨ 核心特性 (Features)

- **🤖 AI 驱动的知识提取**：自动分析全书内容，识别核心概念、关键人物、重要事件及其相互关系。
- **🌐 全景知识图谱**：生成 Wiki 形式的知识库，让你轻松鸟瞰全书的宏观结构。
- **🔗 强大的双向链接**：借助 Obsidian 的特性，在概念、章节和细节之间自由跳转，构建你的知识网络。
- **💻 易于访问的网站**：通过 Quartz 将知识库发布为精美的静态网站，随时随地在任何设备上阅读和探索。

## 💡 工作流程 (How It Works)

1.  **输入 (Input)**：将一本完整的书籍（如 `.txt` 或 `.epub` 格式）提供给处理脚本。转换成markdown格式。然后进行文本的清洗。
2.  **处理 (Processing)**：利用大语言模型对整本书进行分析和结构化，生成一系列 Markdown 文件。
3.  **组织 (Organization)**：这些 Markdown 文件被精心组织起来，利用 Obsidian 的语法创建双向链接。
4.  **发布 (Publishing)**：使用 [Quartz](https://quartz.jzhao.xyz/) 将 `content` 目录下的所有笔记渲染成一个公开的静态网站。

## 🛠️ 仓库结构 (Repository Structure)

这个仓库是 DeepRead 知识库的发布平台。

```
.
├── content/      # 存放由 AI 生成的、关于书籍的 Markdown 笔记源文件
├── ...           # 其他 Quartz 配置文件
└── README.md     # 你正在阅读的文件
```

## 快速开始 (Getting Started)

**对于读者：**

只需访问我们的在线网站即可开始探索：
- **[书籍 A 的知识库链接]**
- **[书籍 B 的知识库链接]**

**对于开发者/贡献者：**

如果你想在本地运行或贡献内容，请遵循以下步骤：

1.  **克隆仓库**
    ```bash
    git clone https://github.com/your-username/DeepRead.git
    cd DeepRead
    ```
2.  **安装 Quartz**
    (请参考 [Quartz 官方文档](https://quartz.jzhao.xyz/) 进行安装和配置)

3.  **本地预览**
    ```bash
    npx quartz build --serve
    ```

## 未来的路 (Roadmap)

- [ ] 录入更多书籍
