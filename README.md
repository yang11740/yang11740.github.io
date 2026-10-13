## 📬 联系方式

- **邮箱**：yy0561764@google.com
- **GitHub**：https://github.com/yang11740
- **个人网站**：https://yang11740.github.io

## 🛠 技能

- **游戏开发**：Unity / C# / WebGL / 动画状态机 / 资源加载优化
- **AI & Agent**：LLM / RAG / 多智能体协作 / 工具调用 / 评测
- **模型微调**：Qwen2.5-VL / LoRA / QLoRA / PEFT / OCR
- **开发工具**：Cursor / Codex / Copilot / Claude Code / Git
- **编程语言**：C# / Python / JavaScript / C++（基础）

## 🚀 项目

### 1. Unity WebGL 3D 虚拟助手

**一句话简介**：在 Web 页面中嵌入 Unity WebGL 3D 虚拟助手，支持文本/语音交互，并与 LLM API 实时通信。

- **技术栈**：Unity, C#, WebGL, JavaScript, WebSocket, LLM API
- **我的贡献**：
  - 独立开发 Unity 端交互逻辑、动画状态机与 UI 系统
  - 实现 WebGL 与前端 JavaScript 的双向通信
  - 优化 WebGL 包体与内存，保证浏览器端流畅运行
  - 接入 LLM API，实现虚拟助手的智能对话
- **技术难点与方案**：
  - **问题**：WebGL 在浏览器中内存受限，加载慢。
  - **方案**：使用 Addressables 按需加载，压缩纹理，减少初始包体。
  - **结果**：首屏加载时间降低约 40%，运行稳定。
- **成果与链接**：
  - 可玩 Demo：https://itch.io/your-demo
  - 源码：https://github.com/yang11740/unity-webgl-3d-assistant
  - 演示视频：https://www.bilibili.com/video/xxxx
  - 架构图：见仓库 `docs/architecture.png`

### 2. 多智能体协作系统 / Agent 工具包

**一句话简介**：基于 LLM 的多智能体协作框架，支持任务分解、工具调用、记忆管理与通信。

- **技术栈**：Python, LangGraph / AutoGen, LLM, RAG, Function Calling
- **我的贡献**：
  - 设计并实现 Agent 工具包，支持动态注册与调用
  - 开发多智能体通信协议与任务分配模块
  - 搭建 RAG 检索增强模块，提升知识问答准确率
  - 设计评测指标与自动化测试流程
- **技术难点与方案**：
  - **问题**：多智能体协作时上下文膨胀、任务重复。
  - **方案**：引入共享记忆池与任务去重机制，限制上下文窗口。
  - **结果**：任务成功率提升 25%，Token 消耗降低 30%。
- **成果与链接**：
  - 源码：https://github.com/yang11740/multi-agent-toolkit
  - 架构图与评测报告：见仓库 `README.md`

### 3. Qwen2.5-VL-7B 微调 OCR

**一句话简介**：微调视觉语言模型 Qwen2.5-VL-7B-Instruct 用于 OCR 识别，提升复杂场景文字提取能力。

- **技术栈**：Qwen2.5-VL-7B-Instruct, LoRA / QLoRA, PEFT, 数据集构建, 评测
- **我的贡献**：
  - 构建 OCR 数据集，包含多场景、多字体、多语言样本
  - 使用 LoRA 进行参数高效微调
  - 设计评测流程，分析错误案例并迭代优化
- **技术难点与方案**：
  - **问题**：小目标文字识别率低。
  - **方案**：数据增强 + 分块推理 + 后处理。
  - **结果**：字符错误率（CER）相对降低 18%。
- **成果与链接**：
  - 源码：https://github.com/yang11740/qwen-vl-ocr-finetune
  - 评测报告：见仓库 `docs/evaluation.md`


## 📌 备注

- 以上项目均可提供更详细的代码讲解与演示。
- 部分项目因保密要求已脱敏，可提供架构图与指标说明。
- 作品集会持续更新，欢迎联系交流。

---

*最后更新：2026-10*
