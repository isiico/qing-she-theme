## [1.0.0] - 2025-12-11

### ✨ 核心更新 (Highlights)

* **🤖 AI 聊天面板完美适配 (AI Chat Optimization)**
    * 彻底修复了在 GitHub Copilot、DeepSeek 等 AI 插件中，由于“深色编辑器 + 亮色侧边栏”混合设计导致的**文字看不清**问题。
    * *Fixed text visibility issues in AI Chat panels. Now perfectly compatible with the hybrid theme design.*

* **🌐 国际化支持 (Internationalization)**
    * **README 新增英文翻译**：文档全面升级为**中英双语**，方便全球开发者阅读，让东方美学走向世界。
    * *Added English translation to README. Now fully internationalized to share Oriental aesthetics with the world.*

### 🐛 修复 (Fixes)
* 修复了输入框提示文字（Placeholder）对比度过低的问题。
    * *Fixed low contrast issues for input placeholders.*
* 修正了 Markdown 渲染在非编辑器区域（如 Chat 面板）的颜色继承逻辑。
    * *Resolved Markdown rendering color conflicts in non-editor areas.*

## [1.0.1] - 2025-12-13
### 🔧 🐛 修复 (Fixes)
* 修复侧边栏选中有时背景色会变成粉色的问题
    * *Fixed sidebar selection background color issue.*

## [1.0.2] - 2025-12-14
### ✨ 核心更新 (Highlights)
* **🌍 通用语法高亮支持 (Universal Syntax Support)**
    * **多语言适配**：新增通用语法基础层，彻底解决 Kotlin、Java、Python 等未单独配置语言显示为单色（全黑/全蓝）的问题，现在它们拥有标准的紫/绿/黄配色。
    * *Introduced a universal syntax base layer. Fixed monochrome display issues for languages like Kotlin, Java, and Python. They now feature standard syntax highlighting.*

* **🛡️ TypeScript & Angular 深度优化 (Deep Optimization)**
    * **语义增强**：明确区分了**类型**（淡蓝）与**属性**（明黄），阅读复杂代码更加清晰；修复了 `imports` 数组内组件名的高亮。
    * *Enhanced semantic highlighting. Clearly distinguished Types (light blue) from Properties (bright yellow). Fixed highlighting for component names in import arrays.*
    * **模板修复**：完美修复 Angular 模板中内联 `style="..."` 的颜色解析问题（内容强制变绿，引号保持灰色），不再受 CSS 语法干扰。
    * *Fixed inline style parsing in Angular templates. Style content is now consistently green while keeping quotes grey.*

* **📝 Markdown 体验升级 (Markdown Upgrade)**
    * **编辑器与预览统一**：编辑器内标题变绿加粗、链接变蓝；预览界面优化了引用块（金边）、代码块背景与链接颜色，告别单调。
    * *Upgraded Markdown experience. Headings are now green and bold in the editor. Optimized blockquotes, code backgrounds, and links in the preview pane.*

### 🐛 修复 (Fixes)
* 修复了由于过于激进的全局覆盖规则，导致 **HTML 文件**失去语法高亮的问题。
    * *Fixed an issue where aggressive global override rules stripped syntax highlighting from HTML files.*
* 修正了 VS Code Chat 界面中斜杠命令（如 `/fix`）颜色不跟随主题的问题。
    * *Corrected the color of slash commands (e.g., `/fix`) in the Chat interface.*