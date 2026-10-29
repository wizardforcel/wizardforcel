## 个人项目

长期独立维护 50+ 个开源项目（[GitHub@DracoUnion](https://github.com/orgs/DracoUnion/repositories)），技术栈覆盖 Python、C#/.NET、PyQt6、FastAPI、React、深度学习与逆向工程。

### 重点项目

**OpenDocCN · 超过百亿字的全栈技术文档库（[GitCode@OpenDocCN1](https://gitcode.com/org/OpenDocCN1/repos)）🚧**

使用 BookerGptTool 工具翻译和整理的全栈技术文档库，分为 200 多个仓库，包含数万本技术书和文档，总计数百亿字。内容涵盖编程语言、前后端、数据科学和人工智能、DevOps、
Linux、网络安全等。

**[Qwen3.5Sharp](https://github.com/DracoUnion/Qwen3.5Sharp) · Qwen3.5 纯 C# CPU 推理引擎（C#/.NET 10）🚧**

面向 Qwen3.5 GGUF 模型的从零推理实现：内存映射 GGUF v2/v3 读取器、AVX2/AVX-VNNI 量化 GEMM/GEMV 内核，完整实现混合 Transformer（GQA 全注意力层 + Gated-DeltaNet 线性注意力层 + SiLU-FFN），含 BPE 分词、KV/循环状态缓存与流式 REPL，全程无第三方推理依赖。

**[IndexTTSSharp](https://github.com/DracoUnion/IndexTTSSharp) · 纯 C# TTS 语音合成（C#/.NET）🚧**

IndexTTS v2 的非官方纯 C# CPU 实现，不依赖 llama.cpp/ONNX/PyTorch。从单 GGUF 权重实现 GPT 自回归解码器、Perceiver 说话人条件、Conformer 编码、RepCodec 语义编解码、DiT/CFM 声码器与 BigVGAN 全链路，可作为 NuGet 库进程内调用。

**[cogalpha-aicode](https://github.com/DracoUnion/cogalpha-aicode) · LLM 驱动的量化因子挖掘（Python）✅️**

论文《Cognitive Alpha Mining via LLM-Driven Code-Based Evolution》完整实现。以 21 个七级 agent 模板进化式生成/变异/交叉因子代码，经静态 AST + LLM 质量门控、横截面收益评估（IC/ICIR/MI），精英跨代携带 + 自适应反馈迭代搜索，支持离线自检与端到端演示。

**[tiange](https://github.com/DracoUnion/tiange) · 天格全栈命理 SaaS 复刻（FastAPI + React）✅️**

复刻商业命理平台的完整全栈实现：46 个前端页面、85+ 后端接口、心识豆 + VIP 计价体系、64 卦 / 观音灵签 / 诸葛神算全量数据，及 AI 八字、命书、解卦、AI 道长等生成能力，含概要设计与详细设计文档。

**[xhs-workbench](https://github.com/DracoUnion/xhs-workbench) · 小红书 AI 工作台（FastAPI + PostgreSQL）🚧**

小红书虚拟产品全自动运营系统：OpenAI Function Calling 驱动的 Agent 编排引擎、任务中心 API 与 WebSocket 实时进度推送、评分服务，集成 xhs-cli 浏览器采集适配器规避接口风控，前后端分离 + Alembic 迁移 + Celery/Redis 可选执行器。

**[minimind-custom](https://github.com/DracoUnion/minimind-custom) · 轻量语言模型训练实验（Python）🚧**

在开源 MiniMind 超小语言模型（约 64M 参数，3 元成本/2 小时可复现）基础上做的定制与实验，架构涉及 Engram、QSA、Mamba、VQ、RWKV 和 DiffusionLM，覆盖预训练、SFT、LoRA、RLHF、MoE、Tool Use 等完整训练链路，用于深入理解 LLM 训练原理。

### 其余项目

**Booker 系列内容工具**（Python CLI，pip 可安装）
+   [**BookerAutoTool✅️**](http://github.com/DracoUnion/BookerAutoTool)：大模型驱动的桌面/安卓/网页自动化工具

+   [**BookerMediaTool✅️**](http://github.com/DracoUnion/BookerMediaTool)：媒体内容生成工具，涵盖小红书、公众号、即可、小宇宙文案和封面生成，以及社媒展示面生成

+   [**BookerNovelTool🚧**](http://github.com/DracoUnion/BookerNovelTool)：小说全自动化生成流水线，带有计算语言学门控检查，全方位纠正AI味

+   [**BookerPaperTool✅️**](http://github.com/DracoUnion/BookerPaperTool)：科研全自动化流水线，涵盖文献→假设→实验→写作→投稿全流程，另外带有论文到教科书生成工具，全面解决前沿知识沉淀难题

+   [**BookerCodeTool✅️**](http://github.com/DracoUnion/BookerCodeTool)：全流程自动化逆向工程智能体（REA 复刻），同时带有代码转源码解析书籍功能，全面解决代码难以理解的难题

+   [**BookerFinReportTool🚧**](http://github.com/DracoUnion/BookerFinReportTool)：财务报告转行业趋势，基本面量化选股神器

+   [**BookerAutoVideo✅️**](http://github.com/DracoUnion/BookerAutoVideo)：音视频自动处理工具，营销号视频全自动生成，以及基于关键帧提取的视频笔记全自动转写

+   [**BookerBV2Tool✅️**](http://github.com/DracoUnion/BookerBV2Tool)：Bert-VITS2 声音克隆训练辅助工具，完整「视频 → 训练数据 → 模型 → 合成」流水线

+   [**BookerComicTrans🚧**](http://github.com/DracoUnion/BookerComicTrans)：PyQt6 漫画 OCR 翻译桌面应用，多引擎 OCR/翻译、文本区域编辑、inpaint 回贴、批量导出 PNG/PDF/CBZ

+   [**BookerMarkdownTool✅️**](http://github.com/DracoUnion/BookerMarkdownTool)：Markdown 知识库维护加工工具，覆盖完整知识库流水线，包含网页抓取、目录生成、排版、翻译、自动洗稿、LLMWiki 维护，SKILL 提取，知识图谱提取等功能

+   [**BookerEpubTool✅️**](http://github.com/DracoUnion/BookerEpubTool)：知识库 EPUB 前置处理工具，包含 EPUB 翻译、图片压缩、章节/图片导出等功能

+   [**BookerPdfTool✅️**](http://github.com/DracoUnion/BookerPdfTool)：知识库 PDF 前置处理工具，包含 OCR、图片压缩、S-Spline 缩放增强、全自动二值化去噪等功能


+   [**BookerDownloadTool✅️**](http://github.com/DracoUnion/BookerDownloadTool)：面向中文互联网的批量下载工具，站点覆盖：GitHub 电子书、wenku8 轻小说、百度文库、知乎、Discuz 论坛、知识星球、Medium、arXiv、语雀、飞书、小红书、Twitter、Pixabay、Anna's Archive、Wayback Machine 等 20+ 来源

+   [**BookerProxyTool✅️**](http://github.com/DracoUnion/BookerProxyTool)：代理池命令行工具，代理抓取、扫描、验证、转发，爬虫工程师必备


+   [**BookerYoloTool🚧**](http://github.com/DracoUnion/BookerYoloTool)：PyQt6 + ultralytics 的 YOLO 训练/推理桌面工具

**模型推理与训练**

- [**GgmlSharp🚧**](https://github.com/DracoUnion/GgmlSharp)：从零 C# 重实现 GGML CPU 计算运行时（ggml-cpu）

**逆向与网络安全工具**

- [**nsa-equation-py🚧**](https://github.com/DracoUnion/nsa-equation-py)：基于 IDA Pro 逆向的安全工具 Python 重实现（SMBGhost 检测、架构探测、RPC 利用）

**智能体与 AI 应用**

- [**xingyue-writing-native（星月写作）✅️**](https://github.com/DracoUnion/xingyue-writing-native)：PyQt6 本地 AI 网文/剧本写作助手

- [**qimen-dashi-py✅️**](https://github.com/DracoUnion/qimen-dashi-py)：奇门遁甲专业排盘桌面应用（九宫盘、农历四柱、预测知识库）

- [**dankoe-skills✅️**](https://github.com/DracoUnion/dankoe-skills)：DanKoe 文章蒸馏的 1400+ Claude Skills 索引库

**文档处理与系统工具**

- [**pyjbig2enc✅️**](https://github.com/DracoUnion/pyjbig2enc)：jbig2enc 的 Python 重写（Numba 加速，二值图像压缩编码）

- **[imgyaso✅️](https://github.com/DracoUnion/imgyaso)（仿色/二值化/颜色缩减）/ [pycleaner✅️](https://github.com/DracoUnion/pycleaner)（CCleaner 清理引擎逆向重构）/ [pySerUI🚧](https://github.com/DracoUnion/pySerUI)（Windows DirectUI 框架）/ [pyturndown✅️](https://github.com/DracoUnion/pyturndown)（HTML→Markdown）/ [epub-crawler✅️](https://github.com/DracoUnion/epub-crawler)**

