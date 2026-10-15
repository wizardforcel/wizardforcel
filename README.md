## 个人项目

长期独立维护 50+ 个开源项目（GitHub@DracoUnion），技术栈覆盖 Python、C#/.NET、PyQt6、FastAPI、React、深度学习与逆向工程。

### 重点项目

**BookerGptTool · AI 命令行工具集（Python）✅️**

基于 OpenAI 兼容 API 构建的 30+ 子命令 CLI 工具，覆盖翻译、代码/文档注释、PDF OCR、EPUB 翻译与小说分析、arXiv 论文总结与 paper2code、财务报告生成、小红书/公众号内容创作、网页 PPT、OpenAI 转发服务，以及基于 Win32 的"大模型玩桌面游戏"等场景；并整合 Agent + Orchestrator 内容管线，一键生成公众号文章、小红书轮播图、播客脚本/音频。负责全局参数体系、子命令注册与多模型编排设计。

**OpenDocCN · 超过百亿字的全栈技术文档库（GitCode@OpenDocCN1）🚧**

使用 BookerGptTool 工具翻译和整理的全栈技术文档库，分为 200 多个仓库，包含数万本技术书和文档，总计数百亿字。内容涵盖编程语言、前后端、数据科学和人工智能、DevOps、
Linux、网络安全等。

**Qwen3.5Sharp · Qwen3.5 纯 C# CPU 推理引擎（C#/.NET 10）🚧**

面向 Qwen3.5 GGUF 模型的从零推理实现：内存映射 GGUF v2/v3 读取器、AVX2/AVX-VNNI 量化 GEMM/GEMV 内核，完整实现混合 Transformer（GQA 全注意力层 + Gated-DeltaNet 线性注意力层 + SiLU-FFN），含 BPE 分词、KV/循环状态缓存与流式 REPL，全程无第三方推理依赖。

**IndexTTSSharp · 纯 C# TTS 语音合成（C#/.NET）🚧**

IndexTTS v2 的非官方纯 C# CPU 实现，不依赖 llama.cpp/ONNX/PyTorch。从单 GGUF 权重实现 GPT 自回归解码器、Perceiver 说话人条件、Conformer 编码、RepCodec 语义编解码、DiT/CFM 声码器与 BigVGAN 全链路，可作为 NuGet 库进程内调用。

**cogalpha-aicode · LLM 驱动的量化因子挖掘（Python）✅️**

论文《Cognitive Alpha Mining via LLM-Driven Code-Based Evolution》完整实现。以 21 个七级 agent 模板进化式生成/变异/交叉因子代码，经静态 AST + LLM 质量门控、横截面收益评估（IC/ICIR/MI），精英跨代携带 + 自适应反馈迭代搜索，支持离线自检与端到端演示。

**tiange · 天格全栈命理 SaaS 复刻（FastAPI + React）✅️**

复刻商业命理平台的完整全栈实现：46 个前端页面、85+ 后端接口、心识豆 + VIP 计价体系、64 卦 / 观音灵签 / 诸葛神算全量数据，及 AI 八字、命书、解卦、AI 道长等生成能力，含概要设计与详细设计文档。

**xhs-workbench · 小红书 AI 工作台（FastAPI + PostgreSQL）🚧**

小红书虚拟产品全自动运营系统：OpenAI Function Calling 驱动的 Agent 编排引擎、任务中心 API 与 WebSocket 实时进度推送、评分服务，集成 xhs-cli 浏览器采集适配器规避接口风控，前后端分离 + Alembic 迁移 + Celery/Redis 可选执行器。

**minimind-custom · 轻量语言模型训练实验（Python）🚧**

在开源 MiniMind 超小语言模型（约 64M 参数，3 元成本/2 小时可复现）基础上做的定制与实验，架构涉及 Engram、QSA、Mamba、VQ、RWKV 和 DiffusionLM，覆盖预训练、SFT、LoRA、RLHF、MoE、Tool Use 等完整训练链路，用于深入理解 LLM 训练原理。

### 其余项目

**Booker 系列内容工具**（Python CLI，pip 可安装）

- **BookerComicTrans🚧**：PyQt6 漫画 OCR 翻译桌面应用，多引擎 OCR/翻译、文本区域编辑、inpaint 回贴、批量导出 PNG/PDF/CBZ

- **BookerYoloTool🚧**：PyQt6 + ultralytics 的 YOLO 训练/推理桌面工具（重写原 MFC 工具）

- **BookerAutoVideo✅️**：文本转视频（TTS 配音 + TTI 配图 + ffmpeg 合成）、音视频转文字（SenseVoice ASR）

- **BookerBV2Tool✅️**：Bert-VITS2 声音克隆数据流水线（切分/转写/BERT 特征/训练全流程）

- **BookerMarkdownTool✅️**：网页抓取转 Markdown 知识库、SUMMARY 生成、中英对照翻译、EPUB 打包

- **BookerDownloadTool✅️**：多源内容下载（GitHub 书、轻小说、知乎、Discuz、语雀、飞书、公众号、arXiv 等）

- **BookerPubTool✅️**：电子书一键发布 Docker Hub/PyPI/npm/Libgen + 多平台内容分发

- **BookerEpubTool✅️**：EPUB 图片压缩、章节/图片导出、段落格式化

- **BookerPdfTool✅️ / BookerProxyTool（代理池扫描转发）✅️ / BookerFinReportTool（财务报告）🚧**

**模型推理与训练**

- **GgmlSharp🚧**：从零 C# 重实现 GGML CPU 计算运行时（ggml-cpu）

**逆向与网络安全工具**

- **nsa-equation-py🚧**：基于 IDA Pro 逆向的安全工具 Python 重实现（SMBGhost 检测、架构探测、RPC 利用）

**智能体与 AI 应用**

- **xingyue-writing-native（星月写作）✅️**：PyQt6 本地 AI 网文/剧本写作助手

- **qimen-dashi-py✅️**：奇门遁甲专业排盘桌面应用（九宫盘、农历四柱、预测知识库）

- **dankoe-skills✅️**：DanKoe 文章蒸馏的 1400+ Claude Skills 索引库

**文档处理与系统工具**

- **pyjbig2enc✅️**：jbig2enc 的 Python 重写（Numba 加速，二值图像压缩编码）

- **imgyaso（仿色/二值化/颜色缩减）✅️ / pycleaner（CCleaner 清理引擎逆向重构）✅️ / pySerUI（Windows DirectUI 框架）🚧 / pyturndown（HTML→Markdown）✅️ / epub-crawler✅️ / gen-epub✅️**

