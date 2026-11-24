# AI Playground

## 📖 项目介绍

AI Playground 是一个用于学习、研究、实践和比较人工智能相关技术的项目，涵盖数学基础、数据科学、机器学习、深度学习、自然语言处理、计算机视觉、大语言模型（LLM）、检索增强生成（RAG）、智能体（Agent）、模型上下文协议（MCP）、模型微调、推理部署以及 AI 工程化等技术领域。

本项目通过最小可运行示例（Minimal Runnable Examples）、独立技术实验、模型训练、技术方案对比和综合项目实践，系统性地积累人工智能知识与工程经验。

项目以 Python 为主要开发语言，同时支持 TypeScript、Java、C#、Go 等语言在 AI 应用开发中的实践，关注不同技术生态下的 AI 集成方式与解决方案。

本项目不仅关注如何使用 AI 模型，也关注模型背后的基本原理、应用架构、工程实践、系统可靠性、性能优化、安全性及部署运维。

希望将本项目逐步建设成为一个可以长期维护、持续扩展、快速查阅的个人人工智能与 AI 工程知识库。

## 🎯 项目目标

- **技术学习（Learning）**：系统学习人工智能基础理论、主流算法、模型及技术框架。
- **代码参考（Reference）**：建立可运行、可复用、易于查阅的个人 AI 代码参考库。
- **技术实验（Experiment）**：通过独立实验验证模型原理、算法行为、技术方案和技术边界。
- **横向对比（Comparison）**：研究不同模型、框架、算法及技术生态之间的差异。
- **模型研究（Modeling）**：理解模型训练、推理、微调、量化和优化的基本原理。
- **应用开发（Application）**：掌握 LLM、RAG、Agent、MCP 和多模态 AI 应用开发。
- **工程实践（Engineering）**：积累 AI 系统开发、部署、评估、监控及维护经验。
- **知识沉淀（Documentation）**：记录技术原理、实验结果、常见问题、踩坑经验和解决方案。
- **综合实践（Integration）**：通过完整 AI 项目整合模型、后端服务、数据处理和前端交互能力。

## 🛠️ 技术栈

以下为项目计划覆盖的技术生态。

### 编程语言

| 语言       | 主要用途                                               |
| ---------- | ------------------------------------------------------ |
| Python     | AI 算法、模型训练、推理、RAG、Agent                    |
| TypeScript | AI 全栈应用、Agent、MCP、前端集成                      |
| Java       | 企业级 AI 应用、Spring AI、LangChain4j                 |
| C#         | .NET AI 应用、Semantic Kernel、Microsoft.Extensions.AI |
| Go         | AI 后端服务、高并发网关、MCP、模型 API 集成            |
| SQL        | 数据处理、数据查询与向量检索                           |

### 数学与数据科学

| 技术             | 用途                 |
| ---------------- | -------------------- |
| NumPy            | 数值计算与矩阵运算   |
| Pandas           | 数据处理与分析       |
| Polars           | 高性能数据处理       |
| SciPy            | 科学计算             |
| SymPy            | 符号计算             |
| Matplotlib       | 数据可视化           |
| Seaborn          | 统计数据可视化       |
| Jupyter Notebook | 交互式实验与数据分析 |

### 机器学习与深度学习

| 技术                      | 用途                     |
| ------------------------- | ------------------------ |
| Scikit-learn              | 传统机器学习             |
| XGBoost                   | 梯度提升算法             |
| LightGBM                  | 高效梯度提升算法         |
| PyTorch                   | 深度学习与模型训练       |
| TensorFlow / Keras        | 深度学习框架             |
| JAX                       | 高性能数值计算与自动微分 |
| Hugging Face Transformers | 预训练模型与 Transformer |
| Hugging Face Datasets     | 数据集加载与处理         |
| Sentence Transformers     | 文本向量化与语义检索     |
| OpenCV                    | 图像处理与计算机视觉     |
| YOLO                      | 目标检测                 |

### 大语言模型与 AI 应用

| 技术领域           | 技术选型                                           |
| ------------------ | -------------------------------------------------- |
| 模型供应商         | OpenAI、Anthropic、Google、DeepSeek、Qwen、Mistral |
| 模型生态           | Hugging Face、ModelScope                           |
| 本地模型           | Ollama、llama.cpp                                  |
| 模型 API           | 官方 SDK、LiteLLM                                  |
| LLM 应用框架       | LangChain、LlamaIndex                              |
| Agent 框架         | LangGraph、OpenAI Agents SDK、Pydantic AI、CrewAI  |
| Java AI 框架       | Spring AI、LangChain4j                             |
| C# AI 框架         | Semantic Kernel、Microsoft.Extensions.AI           |
| TypeScript AI 框架 | Vercel AI SDK、LangChain.js                        |
| Go AI 框架         | Eino                                               |
| 工具集成           | MCP、Function Calling                              |
| AI 后端            | FastAPI                                            |
| AI 前端            | React、Next.js、Vercel AI SDK                      |

### 向量检索与数据存储

| 技术                  | 用途                 |
| --------------------- | -------------------- |
| FAISS                 | 向量索引与相似度检索 |
| Chroma                | 轻量级向量数据库     |
| Qdrant                | 向量数据库与语义检索 |
| Milvus                | 大规模向量检索       |
| Weaviate              | 向量数据库           |
| PostgreSQL / pgvector | 关系型数据与向量存储 |
| Elasticsearch         | 全文检索与混合检索   |
| Redis                 | 缓存、会话与语义缓存 |
| Neo4j                 | 知识图谱与图检索     |
| MinIO                 | 文档与对象存储       |

### 模型训练与推理部署

| 技术                    | 用途                 |
| ----------------------- | -------------------- |
| PEFT                    | 参数高效微调         |
| LoRA / QLoRA            | 低成本模型微调       |
| TRL                     | 模型后训练与对齐     |
| Accelerate              | 分布式训练与设备管理 |
| DeepSpeed               | 大规模模型训练优化   |
| vLLM                    | 高吞吐量模型推理     |
| llama.cpp               | 本地模型推理         |
| ONNX Runtime            | 跨平台模型推理       |
| Triton Inference Server | 模型推理服务         |
| CUDA                    | GPU 并行计算         |
| TensorRT                | GPU 推理优化         |

### AI 工程化与可观测性

| 技术领域      | 技术选型                 |
| ------------- | ------------------------ |
| Python 包管理 | uv                       |
| API 服务      | FastAPI                  |
| 数据验证      | Pydantic                 |
| 异步任务      | Celery、Redis            |
| 自动化测试    | pytest                   |
| AI 评估       | Ragas、DeepEval          |
| 实验管理      | MLflow、Weights & Biases |
| 数据版本管理  | DVC                      |
| LLM 可观测性  | Langfuse、LangSmith      |
| 链路追踪      | OpenTelemetry            |
| 监控          | Prometheus、Grafana      |
| 容器化        | Docker、Docker Compose   |
| 容器编排      | Kubernetes               |
| 持续集成      | GitHub Actions           |

## 📂 项目目录结构

初始版目录：

```
ai-playground/
├── README.md
├── .gitignore
├── .env.example
├── pyproject.toml
│
├── mathematics/
├── data-science/
├── machine-learning/
├── deep-learning/
│
├── llm/
├── prompt-engineering/
├── embeddings/
├── vector-databases/
├── rag/
├── agents/
├── mcp/
├── ai-frameworks/
├── multimodal/
│
├── fine-tuning/
├── model-serving/
├── ai-engineering/
├── ai-security/
├── evaluation/
├── mlops/
├── llmops/
│
├── comparisons/
├── projects/
├── infrastructure/
├── datasets/
├── notebooks/
└── docs/
```

以下为项目的长期参考目录结构，将根据学习进度与实际需求逐步完善。

```text
ai-playground/
├── README.md
├── LICENSE
├── .gitignore
├── .env.example
├── .python-version
├── pyproject.toml
├── uv.lock
│
├── mathematics/
│   ├── README.md
│   ├── linear-algebra/
│   ├── matrix-operations/
│   ├── probability/
│   ├── statistics/
│   ├── calculus/
│   ├── information-theory/
│   ├── optimization/
│   └── gradient-descent/
│
├── data-science/
│   ├── README.md
│   ├── numpy/
│   ├── pandas/
│   ├── polars/
│   ├── scipy/
│   ├── matplotlib/
│   ├── seaborn/
│   ├── data-cleaning/
│   ├── data-preprocessing/
│   ├── data-visualization/
│   └── feature-engineering/
│
├── machine-learning/
│   ├── README.md
│   ├── scikit-learn/
│   ├── linear-regression/
│   ├── logistic-regression/
│   ├── decision-tree/
│   ├── random-forest/
│   ├── svm/
│   ├── knn/
│   ├── naive-bayes/
│   ├── k-means/
│   ├── dbscan/
│   ├── pca/
│   ├── xgboost/
│   ├── lightgbm/
│   ├── cross-validation/
│   ├── hyperparameter-tuning/
│   └── model-evaluation/
│
├── deep-learning/
│   ├── README.md
│   ├── pytorch/
│   ├── tensorflow/
│   ├── jax/
│   ├── tensors/
│   ├── autograd/
│   ├── neural-networks/
│   ├── backpropagation/
│   ├── activation-functions/
│   ├── loss-functions/
│   ├── optimizers/
│   ├── regularization/
│   ├── normalization/
│   ├── cnn/
│   ├── rnn/
│   ├── lstm/
│   ├── attention/
│   ├── transformer/
│   ├── training-loop/
│   └── distributed-training/
│
├── computer-vision/
│   ├── README.md
│   ├── opencv/
│   ├── image-processing/
│   ├── image-classification/
│   ├── object-detection/
│   ├── image-segmentation/
│   ├── object-tracking/
│   ├── vision-transformer/
│   ├── yolo/
│   └── ocr/
│
├── nlp/
│   ├── README.md
│   ├── text-preprocessing/
│   ├── tokenization/
│   ├── word-embedding/
│   ├── sentence-embedding/
│   ├── text-classification/
│   ├── sentiment-analysis/
│   ├── named-entity-recognition/
│   ├── text-summarization/
│   ├── machine-translation/
│   ├── bert/
│   └── huggingface/
│
├── generative-ai/
│   ├── README.md
│   ├── autoencoder/
│   ├── vae/
│   ├── gan/
│   ├── diffusion/
│   ├── stable-diffusion/
│   └── image-generation/
│
├── llm/
│   ├── README.md
│   ├── providers/
│   │   ├── openai/
│   │   ├── anthropic/
│   │   ├── gemini/
│   │   ├── deepseek/
│   │   ├── qwen/
│   │   └── mistral/
│   ├── architecture/
│   ├── tokenization/
│   ├── basic-chat/
│   ├── multi-turn-chat/
│   ├── streaming/
│   ├── structured-output/
│   ├── tool-calling/
│   ├── context-management/
│   ├── token-counting/
│   ├── conversation-history/
│   ├── reasoning-models/
│   └── model-comparison/
│
├── prompt-engineering/
│   ├── README.md
│   ├── zero-shot/
│   ├── few-shot/
│   ├── prompt-templates/
│   ├── role-prompting/
│   ├── task-decomposition/
│   ├── structured-output/
│   ├── context-engineering/
│   ├── prompt-optimization/
│   └── prompt-evaluation/
│
├── embeddings/
│   ├── README.md
│   ├── text-embedding/
│   ├── image-embedding/
│   ├── sentence-transformers/
│   ├── cosine-similarity/
│   ├── distance-metrics/
│   ├── similarity-search/
│   ├── semantic-search/
│   └── embedding-evaluation/
│
├── vector-databases/
│   ├── README.md
│   ├── faiss/
│   ├── chromadb/
│   ├── qdrant/
│   ├── milvus/
│   ├── weaviate/
│   ├── pgvector/
│   ├── elasticsearch/
│   ├── vector-index/
│   ├── hnsw/
│   └── metadata-filtering/
│
├── rag/
│   ├── README.md
│   ├── basic-rag/
│   ├── document-loading/
│   ├── document-parsing/
│   ├── text-chunking/
│   ├── document-indexing/
│   ├── incremental-indexing/
│   ├── metadata-filtering/
│   ├── semantic-retrieval/
│   ├── keyword-retrieval/
│   ├── hybrid-search/
│   ├── reranking/
│   ├── query-rewriting/
│   ├── multi-query/
│   ├── contextual-retrieval/
│   ├── hierarchical-retrieval/
│   ├── graph-rag/
│   ├── agentic-rag/
│   └── citations/
│
├── agents/
│   ├── README.md
│   ├── basic-agent/
│   ├── agent-loop/
│   ├── tool-calling/
│   ├── react-agent/
│   ├── planning/
│   ├── reflection/
│   ├── memory/
│   ├── workflows/
│   ├── routing/
│   ├── multi-agent/
│   ├── human-in-the-loop/
│   ├── structured-state/
│   ├── checkpointing/
│   ├── task-recovery/
│   └── sandbox/
│
├── mcp/
│   ├── README.md
│   ├── basic-server/
│   ├── basic-client/
│   ├── tools/
│   ├── resources/
│   ├── prompts/
│   ├── stdio-transport/
│   ├── streamable-http/
│   ├── authentication/
│   ├── authorization/
│   ├── database-tools/
│   ├── filesystem-tools/
│   ├── rest-api-tools/
│   └── server-integration/
│
├── ai-frameworks/
│   ├── README.md
│   ├── langchain/
│   ├── langgraph/
│   ├── llamaindex/
│   ├── openai-agents-sdk/
│   ├── pydantic-ai/
│   ├── crewai/
│   ├── semantic-kernel/
│   ├── microsoft-extensions-ai/
│   ├── spring-ai/
│   ├── langchain4j/
│   ├── vercel-ai-sdk/
│   ├── langchain-js/
│   └── eino/
│
├── multimodal/
│   ├── README.md
│   ├── image-understanding/
│   ├── image-generation/
│   ├── document-understanding/
│   ├── speech-to-text/
│   ├── text-to-speech/
│   ├── audio-understanding/
│   ├── video-understanding/
│   ├── multimodal-embedding/
│   └── realtime-interaction/
│
├── fine-tuning/
│   ├── README.md
│   ├── dataset-preparation/
│   ├── supervised-fine-tuning/
│   ├── lora/
│   ├── qlora/
│   ├── peft/
│   ├── instruction-tuning/
│   ├── rlhf/
│   ├── dpo/
│   ├── distillation/
│   └── model-export/
│
├── model-serving/
│   ├── README.md
│   ├── ollama/
│   ├── llama-cpp/
│   ├── vllm/
│   ├── onnx-runtime/
│   ├── triton/
│   ├── tensorrt/
│   ├── cuda/
│   ├── quantization/
│   ├── batching/
│   ├── kv-cache/
│   ├── gpu-inference/
│   ├── distributed-inference/
│   └── inference-benchmark/
│
├── ai-engineering/
│   ├── README.md
│   ├── fastapi/
│   ├── llm-gateway/
│   ├── streaming-api/
│   ├── asynchronous-inference/
│   ├── task-queue/
│   ├── semantic-cache/
│   ├── rate-limiting/
│   ├── retry-and-fallback/
│   ├── circuit-breaker/
│   ├── cost-management/
│   ├── model-routing/
│   ├── conversation-management/
│   ├── document-pipeline/
│   ├── multi-tenancy/
│   └── high-availability/
│
├── ai-security/
│   ├── README.md
│   ├── prompt-injection/
│   ├── indirect-prompt-injection/
│   ├── data-leakage/
│   ├── pii-redaction/
│   ├── input-validation/
│   ├── output-validation/
│   ├── tool-permissions/
│   ├── document-access-control/
│   ├── agent-sandbox/
│   ├── guardrails/
│   └── safety-evaluation/
│
├── evaluation/
│   ├── README.md
│   ├── model-evaluation/
│   ├── llm-evaluation/
│   ├── rag-evaluation/
│   ├── agent-evaluation/
│   ├── prompt-evaluation/
│   ├── retrieval-metrics/
│   ├── faithfulness/
│   ├── hallucination-detection/
│   ├── llm-as-a-judge/
│   ├── golden-datasets/
│   ├── human-evaluation/
│   ├── ragas/
│   ├── deepeval/
│   └── regression-testing/
│
├── mlops/
│   ├── README.md
│   ├── mlflow/
│   ├── dvc/
│   ├── experiment-tracking/
│   ├── model-registry/
│   ├── data-versioning/
│   ├── model-versioning/
│   ├── model-monitoring/
│   ├── data-drift/
│   ├── training-pipeline/
│   └── deployment-pipeline/
│
├── llmops/
│   ├── README.md
│   ├── langfuse/
│   ├── langsmith/
│   ├── opentelemetry/
│   ├── prompt-versioning/
│   ├── tracing/
│   ├── token-monitoring/
│   ├── latency-monitoring/
│   ├── cost-monitoring/
│   ├── quality-monitoring/
│   └── feedback-collection/
│
├── comparisons/
│   ├── README.md
│   ├── machine-learning-models/
│   ├── llm-providers/
│   ├── open-source-models/
│   ├── embedding-models/
│   ├── vector-databases/
│   ├── chunking-strategies/
│   ├── retrieval-strategies/
│   ├── rag-strategies/
│   ├── agent-frameworks/
│   ├── inference-engines/
│   ├── programming-languages/
│   └── benchmarks/
│
├── projects/
│   ├── README.md
│   ├── ai-chatbot/
│   ├── pdf-chat/
│   ├── enterprise-knowledge-base/
│   ├── ai-search-engine/
│   ├── ai-code-assistant/
│   ├── document-extraction/
│   ├── resume-analyzer/
│   ├── ai-customer-service/
│   ├── text-to-sql/
│   ├── research-agent/
│   ├── voice-assistant/
│   ├── multi-agent-system/
│   ├── ai-gateway/
│   └── local-ai-platform/
│
├── infrastructure/
│   ├── README.md
│   ├── compose.yaml
│   ├── ollama/
│   ├── qdrant/
│   ├── milvus/
│   ├── postgresql/
│   ├── elasticsearch/
│   ├── neo4j/
│   ├── redis/
│   ├── minio/
│   ├── mlflow/
│   ├── langfuse/
│   ├── prometheus/
│   └── grafana/
│
├── datasets/
│   ├── README.md
│   ├── samples/
│   ├── synthetic/
│   └── evaluation/
│
├── notebooks/
│   ├── README.md
│   ├── mathematics/
│   ├── data-analysis/
│   ├── machine-learning/
│   └── experiments/
│
├── docs/
│   ├── concepts/
│   ├── architecture/
│   ├── best-practices/
│   ├── troubleshooting/
│   ├── interview/
│   ├── research-papers/
│   └── resources/
│
├── scripts/
│   ├── setup/
│   ├── data-preparation/
│   ├── training/
│   ├── evaluation/
│   ├── benchmark/
│   └── deployment/
│
└── .github/
    └── workflows/
        ├── lint.yml
        ├── test.yml
        └── evaluation.yml
```

## 📁 目录说明

| 目录                  | 说明                             |
| --------------------- | -------------------------------- |
| `mathematics/`        | 人工智能相关数学基础             |
| `data-science/`       | 数据处理、数据分析与特征工程     |
| `machine-learning/`   | 传统机器学习算法及模型           |
| `deep-learning/`      | 神经网络、深度学习及模型训练     |
| `computer-vision/`    | 计算机视觉与图像处理             |
| `nlp/`                | 自然语言处理                     |
| `generative-ai/`      | 生成式模型与生成式 AI            |
| `llm/`                | 大语言模型原理与 API 应用        |
| `prompt-engineering/` | 提示词与上下文工程               |
| `embeddings/`         | 向量表示、相似度计算与语义检索   |
| `vector-databases/`   | 向量数据库、索引及检索机制       |
| `rag/`                | 检索增强生成及高级检索策略       |
| `agents/`             | 智能体、工作流与多智能体系统     |
| `mcp/`                | 模型上下文协议与工具集成         |
| `ai-frameworks/`      | 主流 AI 应用开发框架             |
| `multimodal/`         | 图像、语音、视频及多模态 AI      |
| `fine-tuning/`        | 模型微调、后训练及模型对齐       |
| `model-serving/`      | 模型推理、量化、优化及部署       |
| `ai-engineering/`     | AI 应用架构与工程实践            |
| `ai-security/`        | AI 安全、隐私保护及权限控制      |
| `evaluation/`         | 模型、RAG、Agent 及应用质量评估  |
| `mlops/`              | 机器学习生命周期管理             |
| `llmops/`             | 大语言模型应用运维与可观测性     |
| `comparisons/`        | 模型、算法、框架及技术方案对比   |
| `projects/`           | 综合 AI 应用实践项目             |
| `infrastructure/`     | 共享基础设施及容器配置           |
| `datasets/`           | 小型示例数据集与评估数据集       |
| `notebooks/`          | 交互式分析与探索性实验           |
| `docs/`               | 技术文档、论文笔记及学习资料     |
| `scripts/`            | 数据处理、训练、评估及自动化脚本 |
| `.github/`            | GitHub Actions 持续集成配置      |

## 🧠 AI 技术知识体系

本项目按照以下六个层次组织人工智能相关知识。

```text
┌──────────────────────────────────────────┐
│ L6 — AI Applications                     │
│ Chatbot / Copilot / AI Search / AI Agent  │
├──────────────────────────────────────────┤
│ L5 — AI Engineering                      │
│ Serving / Evaluation / Security / LLMOps │
├──────────────────────────────────────────┤
│ L4 — AI Orchestration                    │
│ RAG / Agent / MCP / Workflow             │
├──────────────────────────────────────────┤
│ L3 — Foundation Models                   │
│ LLM / Embedding / Multimodal / Tuning     │
├──────────────────────────────────────────┤
│ L2 — Algorithms & Models                 │
│ Machine Learning / Deep Learning / NLP   │
├──────────────────────────────────────────┤
│ L1 — Fundamentals                        │
│ Python / Mathematics / Data Science      │
└──────────────────────────────────────────┘
```

各层之间相互关联，既可以独立学习，也可以通过综合项目进行整合。

## 📚 学习内容

### 1. 数学基础

- 线性代数
- 向量与矩阵
- 矩阵乘法与矩阵分解
- 特征值与特征向量
- 概率论与概率分布
- 贝叶斯定理
- 数理统计
- 微积分与偏导数
- 链式法则
- 梯度下降
- 信息熵与交叉熵
- KL 散度
- 优化理论

### 2. 数据科学与数据处理

- NumPy 数组与矩阵运算
- Pandas 数据处理
- Polars 高性能数据分析
- 数据清洗
- 缺失值处理
- 异常值处理
- 数据标准化与归一化
- 特征提取
- 特征工程
- 探索性数据分析（EDA）
- 数据可视化
- 数据集划分
- 数据泄漏防护

### 3. 机器学习

- 监督学习
- 无监督学习
- 半监督学习
- 强化学习基础
- 线性回归
- 逻辑回归
- 决策树
- 随机森林
- 支持向量机
- KNN
- 朴素贝叶斯
- 聚类算法
- 降维算法
- 集成学习
- 梯度提升
- 交叉验证
- 超参数优化
- 过拟合与欠拟合
- 模型评估与选择

### 4. 深度学习

- Tensor 与张量运算
- 自动微分
- 神经网络
- 前向传播
- 反向传播
- 激活函数
- 损失函数
- 优化器
- 正则化
- Batch Normalization
- Layer Normalization
- CNN
- RNN
- LSTM
- Attention
- Self-Attention
- Multi-Head Attention
- Transformer
- 模型训练循环
- GPU 训练
- 分布式训练基础

### 5. 计算机视觉与自然语言处理

- 图像预处理
- 图像分类
- 目标检测
- 图像分割
- OCR
- Vision Transformer
- 文本预处理
- Tokenization
- Word Embedding
- Sentence Embedding
- 文本分类
- 情感分析
- 命名实体识别
- 文本摘要
- 机器翻译
- BERT
- 预训练语言模型

### 6. 大语言模型（LLM）

- 大语言模型基本原理
- Decoder-only Transformer
- Token 与 Tokenizer
- 自回归文本生成
- 模型上下文窗口
- Temperature
- Top-k 与 Top-p
- 多轮对话
- 流式响应
- Structured Output
- Function Calling
- Tool Calling
- 上下文管理
- 推理模型
- 模型能力与局限性
- 多模型接入
- 模型供应商接口差异
- Token 消耗与成本分析

### 7. Prompt Engineering 与 Context Engineering

- Zero-shot Prompting
- Few-shot Prompting
- Prompt Template
- System Prompt
- Role Prompting
- 任务分解
- 输出格式约束
- 上下文构建
- 上下文压缩
- 上下文选择
- Prompt 版本管理
- Prompt 优化
- Prompt 评估

### 8. Embedding 与向量检索

- 文本向量化
- 图像向量化
- 向量空间
- 余弦相似度
- 欧氏距离
- 点积相似度
- 向量索引
- 近似最近邻搜索（ANN）
- HNSW
- IVF
- 语义检索
- 元数据过滤
- 向量数据库
- Embedding 模型评估

### 9. 检索增强生成（RAG）

- 文档加载
- 文档解析
- 文本清洗
- 文档切分（Chunking）
- 文档向量化
- 文档索引
- 增量索引
- 向量检索
- BM25
- 关键词检索
- 混合检索（Hybrid Search）
- Reranking
- Query Rewriting
- Multi-query Retrieval
- Contextual Retrieval
- Hierarchical Retrieval
- Graph RAG
- Agentic RAG
- 引用与来源追踪
- 文档权限管理
- RAG 质量评估

### 10. AI Agent 与工作流

- Agent 基本原理
- Agent Loop
- Tool Calling
- ReAct
- Planning
- Reflection
- Agent Memory
- 状态管理
- 工作流编排
- 条件路由
- 并行任务执行
- 多智能体协作
- Human-in-the-loop
- Checkpointing
- 任务恢复
- 工具权限管理
- 执行环境隔离
- Agent 评估

### 11. Model Context Protocol（MCP）

- MCP 协议基本原理
- Host、Client 与 Server
- Tools
- Resources
- Prompts
- JSON-RPC
- Stdio Transport
- Streamable HTTP
- MCP Server 开发
- MCP Client 开发
- 工具发现与调用
- 数据库工具集成
- 文件系统工具集成
- REST API 工具集成
- 身份认证与授权
- 多语言 MCP 开发
- MCP 安全与权限控制

### 12. 多模态人工智能

- 图像理解
- 图像生成
- 文档理解
- OCR 与结构化信息提取
- Speech-to-Text
- Text-to-Speech
- 音频理解
- 视频理解
- 多模态 Embedding
- 多模态 RAG
- 实时语音交互
- 多模态 Agent

### 13. 模型微调与后训练

- 数据集构建
- 数据质量控制
- Instruction Tuning
- Supervised Fine-tuning（SFT）
- Parameter-Efficient Fine-Tuning（PEFT）
- LoRA
- QLoRA
- RLHF 基础
- Direct Preference Optimization（DPO）
- 知识蒸馏
- 模型评估
- 模型导出
- 微调前后效果对比

### 14. 模型推理与部署

- 本地模型运行
- Ollama
- llama.cpp
- vLLM
- ONNX Runtime
- Triton Inference Server
- TensorRT
- CUDA 基础
- 模型量化
- FP32、FP16、BF16、INT8、INT4
- KV Cache
- Continuous Batching
- GPU 显存管理
- 推理吞吐量优化
- 推理延迟优化
- 分布式推理
- 模型服务化
- 推理性能测试

### 15. AI 应用工程化

- AI API 服务
- LLM Gateway
- 模型路由
- 模型降级与回退
- 请求重试
- 超时控制
- 限流与熔断
- Token 配额管理
- 流式 API
- 异步推理任务
- 消息队列
- 语义缓存
- 会话管理
- 对话历史持久化
- 文档处理流水线
- 多租户架构
- 成本控制
- 高可用 AI 服务
- AI 应用系统设计

### 16. AI 安全

- Prompt Injection
- Indirect Prompt Injection
- 不可信上下文处理
- 敏感信息泄露防护
- PII 检测与脱敏
- 输入验证
- 输出验证
- 模型输出安全处理
- 工具调用权限
- 最小权限原则
- 人工审批机制
- Agent 沙箱
- 文档级访问控制
- 多租户数据隔离
- AI Guardrails
- AI 安全评估
- 数据隐私与 GDPR 基础

### 17. AI Evaluation

- 分类与回归模型评估
- Accuracy、Precision、Recall、F1
- ROC-AUC
- 混淆矩阵
- 检索相关性评估
- Recall@K
- Precision@K
- MRR
- NDCG
- Answer Relevance
- Faithfulness
- Groundedness
- 幻觉检测
- LLM-as-a-Judge
- 人工评估
- Agent 任务成功率
- 工具调用正确性
- Golden Dataset
- 自动化回归评估
- 质量、延迟与成本综合评估

### 18. MLOps 与 LLMOps

- 实验追踪
- 数据版本管理
- 模型版本管理
- 模型注册中心
- 训练流水线
- 模型部署流水线
- 模型监控
- 数据漂移
- Prompt 版本管理
- LLM Tracing
- Token 使用量监控
- 推理延迟监控
- 成本监控
- 输出质量监控
- 用户反馈收集
- 持续评估
- CI/CD
- Docker 与 Kubernetes

## 🔬 Demo 组织规范

每个 Demo 应尽可能独立、简单、可运行，并围绕一个明确的技术知识点展开。

### 示例：机器学习

```text
machine-learning/linear-regression/
├── README.md
├── from-scratch/
│   ├── main.py
│   └── test_model.py
├── scikit-learn/
│   ├── main.py
│   └── test_model.py
└── experiment.ipynb
```

通过原生实现与成熟框架实现的对比，理解算法原理及实际使用方式。

### 示例：深度学习

```text
deep-learning/transformer/
├── README.md
├── self-attention/
├── multi-head-attention/
├── positional-encoding/
├── feed-forward-network/
├── encoder/
├── decoder/
└── minimal-transformer/
    ├── README.md
    ├── model.py
    ├── train.py
    ├── inference.py
    ├── config.yaml
    └── tests/
```

对于复杂模型，可以将模型拆分为多个独立模块，逐步理解其组成及运行机制。

### 示例：LLM Streaming

```text
llm/streaming/
├── README.md
├── basic-streaming/
│   └── main.py
├── async-streaming/
│   └── main.py
├── sse-streaming/
│   └── main.py
├── stream-cancellation/
└── error-handling/
```

除了正常的流式输出，还应研究连接中断、请求取消、超时、异常处理和资源释放。

### 示例：Basic RAG

```text
rag/basic-rag/
├── README.md
├── pyproject.toml
├── .env.example
├── config.yaml
├── main.py
├── ingest.py
├── retrieve.py
├── generate.py
├── data/
│   └── sample.md
├── prompts/
│   └── answer.txt
└── tests/
    ├── test_retrieval.py
    └── test_generation.py
```

Basic RAG 应优先实现完整的最小检索增强生成流程，而不是直接引入复杂的框架和架构。

### 示例：Agent

```text
agents/basic-agent/
├── README.md
├── main.py
├── agent.py
├── tools.py
├── state.py
├── prompts/
│   └── system.txt
└── tests/
    ├── test_tools.py
    └── test_agent.py
```

建议首先实现原生 Agent Loop，再学习 LangGraph 等智能体框架。

### 示例：模型微调

```text
fine-tuning/lora/
├── README.md
├── pyproject.toml
├── config.yaml
├── prepare_dataset.py
├── train.py
├── inference.py
├── evaluate.py
└── data/
    └── sample.jsonl
```

模型训练产物、Checkpoint 和大型数据集应存放在 Git 管理范围之外。

### 示例：AI 应用工程

```text
ai-engineering/llm-gateway/
├── README.md
├── pyproject.toml
├── .env.example
├── app/
│   ├── main.py
│   ├── config.py
│   ├── schemas.py
│   ├── providers/
│   ├── routing/
│   ├── middleware/
│   └── services/
├── tests/
├── Dockerfile
└── compose.yaml
```

简单 Demo 优先保持最小实现，只有在需要研究工程架构时才引入分层设计。

## 🌐 多语言开发规范

本项目以技术领域作为一级目录，而不是以编程语言作为一级目录。

Python 是默认的 AI 开发语言。对于模型 API、RAG、Agent、MCP 和 AI 服务集成等应用开发场景，可以使用其他语言进行实现与对比。

例如：

```text
llm/tool-calling/
├── README.md
├── specification.md
├── python/
│   ├── pyproject.toml
│   └── main.py
├── typescript/
│   ├── package.json
│   └── src/
├── java/
│   ├── pom.xml
│   └── src/
├── csharp/
│   ├── ToolCalling.csproj
│   └── Program.cs
└── go/
    ├── go.mod
    └── main.go
```

MCP 多语言示例：

```text
mcp/basic-server/
├── README.md
├── python/
├── typescript/
├── java/
├── csharp/
└── go/
```

各语言使用独立的依赖管理、构建工具和运行环境。

机器学习、深度学习、模型训练及微调等内容主要使用 Python，无须为每种语言重复实现相同算法。

## 📝 Demo 文档规范

建议每个 Demo 包含独立的 README，并根据实际情况记录以下内容：

| 内容                | 说明                     |
| ------------------- | ------------------------ |
| Overview            | 功能介绍与实验背景       |
| Learning Objectives | 学习目标                 |
| Concepts            | 核心技术原理             |
| Architecture        | 系统结构与数据流程       |
| Implementation      | 实现思路与关键代码       |
| Prerequisites       | 环境、依赖与硬件要求     |
| Model Configuration | 模型名称、版本与推理参数 |
| Dataset             | 数据集来源与数据格式     |
| Quick Start         | 安装及运行方式           |
| Expected Results    | 预期运行结果             |
| Evaluation          | 评估方法与实验指标       |
| Benchmark           | 性能与成本测试           |
| Edge Cases          | 异常情况与边界条件       |
| Limitations         | 技术局限性               |
| Security            | 安全与隐私注意事项       |
| Use Cases           | 实际业务应用场景         |
| Best Practices      | 工程实践与注意事项       |
| References          | 官方文档、论文及参考资料 |

对于模型训练与性能实验，建议额外记录：

- 模型名称与版本
- 数据集名称、版本及来源
- 数据集划分方式
- 随机种子
- 超参数
- Python 与框架版本
- CPU、GPU 与内存配置
- 训练时间
- 推理延迟
- 实验成本
- 实验结果与评估指标

简单 Demo 无须包含全部内容，以清晰、实用、可复现为原则。

## ⚖️ 技术对比实验

本项目不仅关注技术的使用方式，也关注不同模型、算法、框架及技术方案之间的差异。

### 对比方向

| 技术领域      | 对比内容                                        |
| ------------- | ----------------------------------------------- |
| 机器学习      | 不同算法的准确率、训练时间及泛化能力            |
| LLM           | 不同模型的质量、延迟、成本及能力                |
| Embedding     | 不同向量模型的检索效果                          |
| 向量数据库    | 索引性能、检索速度、召回率及资源占用            |
| Chunking      | 不同切分策略对 RAG 效果的影响                   |
| RAG           | 向量检索、关键词检索、混合检索                  |
| Agent         | 不同框架的任务完成能力与工程复杂度              |
| Fine-tuning   | 不同微调策略的效果与资源消耗                    |
| Model Serving | 不同推理引擎的吞吐量与延迟                      |
| 编程语言      | Python、TypeScript、Java、C#、Go 的 AI 集成方式 |

### 对比实验目录

```text
comparisons/rag-strategies/
├── README.md
├── specification.md
├── config.yaml
├── datasets/
├── evaluation/
├── benchmark/
└── results/
    └── summary.md
```

具体实现优先复用各技术目录下的 Demo，通过统一数据集、实验配置和评估脚本进行关联，避免重复维护相同代码。

### 对比原则

- 尽可能使用相同的数据集与任务需求。
- 保持一致的模型版本与推理参数。
- 记录硬件环境及软件依赖版本。
- 记录测试样本数量与评估方法。
- 对存在随机性的实验进行多次测试。
- 区分模型质量、系统性能与工程复杂度。
- 同时关注准确性、可靠性、延迟和成本。
- 客观记录实验局限性，不将单次实验结果视为普遍结论。

## 🚀 快速开始

### 1. 克隆项目

```bash
git clone https://github.com/<your-username>/ai-playground.git

cd ai-playground
```

请将 `<your-username>` 替换为实际的 GitHub 用户名。

### 2. 准备开发环境

| 环境              | 用途                       |
| ----------------- | -------------------------- |
| Python            | AI 开发主要语言            |
| uv                | Python 环境及依赖管理      |
| Git               | 版本控制                   |
| Jupyter Notebook  | 交互式实验                 |
| Docker            | 容器化环境                 |
| Docker Compose    | 基础设施管理               |
| Ollama            | 可选的本地模型运行环境     |
| NVIDIA GPU / CUDA | 可选的模型训练与推理环境   |
| Node.js / pnpm    | 可选的 TypeScript 开发环境 |
| JDK / Maven       | 可选的 Java 开发环境       |
| .NET SDK          | 可选的 C# 开发环境         |
| Go SDK            | 可选的 Go 开发环境         |

### 3. 安装 Python 依赖

项目计划使用 uv 管理 Python 环境与依赖。

根目录公共依赖配置完成后，可以执行：

```bash
uv sync
```

检查 Python 环境：

```bash
uv run python --version
```

添加依赖：

```bash
uv add numpy
uv add pandas
uv add scikit-learn
```

对于 PyTorch、CUDA、模型训练和推理服务等存在特殊依赖要求的实验，建议使用独立的 `pyproject.toml` 和虚拟环境，避免依赖冲突。

### 4. 配置环境变量

```bash
cp .env.example .env
```

环境变量参考：

```dotenv
# LLM Providers
OPENAI_API_KEY=
ANTHROPIC_API_KEY=
GOOGLE_API_KEY=
DEEPSEEK_API_KEY=
DASHSCOPE_API_KEY=
MISTRAL_API_KEY=

# Local Models
OLLAMA_BASE_URL=http://localhost:11434

# Vector Database
QDRANT_URL=http://localhost:6333

# PostgreSQL
DATABASE_URL=

# Redis
REDIS_URL=redis://localhost:6379/0

# Observability
LANGFUSE_PUBLIC_KEY=
LANGFUSE_SECRET_KEY=
LANGFUSE_BASE_URL=http://localhost:3000
```

仅配置当前实验所需的环境变量即可。

不得将真实 API Key、密码、访问令牌或其他敏感信息提交至 Git 仓库。

### 5. 启动基础设施

项目计划使用 Docker Compose 统一管理常用基础设施。

对应服务配置完成后，可以按需启动：

```bash
cd infrastructure

docker compose up -d qdrant
```

启动 PostgreSQL 与 Redis：

```bash
docker compose up -d postgres redis
```

查看服务状态：

```bash
docker compose ps
```

停止服务：

```bash
docker compose down
```

不需要同时启动所有基础设施，应根据当前实验选择所需服务。

### 6. 运行本地模型

安装并启动 Ollama 后，可以下载与运行本地模型。

```bash
ollama pull qwen2.5:3b

ollama run qwen2.5:3b
```

查看本地模型：

```bash
ollama list
```

检查模型服务：

```bash
curl http://localhost:11434/api/tags
```

模型名称仅为运行示例，实际模型应根据硬件资源、任务需求及模型许可证进行选择。

### 7. 运行 Demo

以下命令为对应示例完成后的参考运行方式。

**机器学习**

```bash
uv run python machine-learning/linear-regression/scikit-learn/main.py
```

**LLM**

```bash
uv run python llm/basic-chat/main.py
```

**RAG**

```bash
cd rag/basic-rag

uv sync
uv run python ingest.py
uv run python main.py
```

**Agent**

```bash
uv run python agents/basic-agent/main.py
```

**AI API 服务**

```bash
cd ai-engineering/llm-gateway

uv sync
uv run uvicorn app.main:app --reload
```

**Jupyter Notebook**

在安装相应开发依赖后运行：

```bash
uv run jupyter lab
```

具体启动方式、模型配置、环境变量、端口及硬件要求，请参考对应 Demo 的 README。

### 8. 测试与评估

在安装相应开发依赖的项目环境中运行：

```bash
uv run pytest
```

代码检查：

```bash
uv run ruff check .
```

代码格式化：

```bash
uv run ruff format .
```

模型与应用评估示例：

```bash
uv run python evaluation/rag-evaluation/main.py
```

涉及外部模型 API、GPU 或付费服务的测试应单独标记，避免在默认测试流程中产生不必要的费用。

## 🏗️ AI 应用参考架构

### RAG 应用架构

```text
Document Ingestion
        │
        ▼
Document Parsing
        │
        ▼
Text Chunking
        │
        ▼
Embedding Model
        │
        ▼
Vector Database
        │
        │
User Query
        │
        ▼
Query Processing
        │
        ▼
Retrieval ◄──── Vector Database
        │
        ▼
Reranking
        │
        ▼
Context Construction
        │
        ▼
LLM Generation
        │
        ▼
Answer + Citations
```

### Agent 应用架构

```text
User Task
    │
    ▼
Agent / Workflow
    │
    ├── Context Management
    ├── State Management
    ├── Memory
    ├── Planning
    └── Tool Selection
            │
            ▼
       Tool Execution
            │
            ├── Search
            ├── Database
            ├── REST API
            ├── MCP Server
            └── Sandbox
            │
            ▼
       Observe Result
            │
            ▼
       Continue / Finish
            │
            ▼
       Final Response
```

涉及敏感数据、外部写入操作或高风险工具调用时，应加入权限校验与必要的人工审批。

### 企业级 AI 应用参考架构

```text
Frontend Application
React / Vue / Angular
          │
          ▼
API Gateway
          │
          ▼
Business Backend
Go / Java / C# / TypeScript / Python
          │
          ▼
AI Service
Python / FastAPI
          │
          ├── LLM Gateway
          ├── RAG Pipeline
          ├── Agent Workflow
          ├── MCP Client
          ├── Evaluation
          └── Guardrails
          │
          ▼
Infrastructure
          │
          ├── LLM Providers
          ├── Local Model Serving
          ├── Vector Database
          ├── PostgreSQL
          ├── Redis
          ├── Object Storage
          └── Monitoring
```

以上为参考架构，实际项目应根据业务复杂度、性能需求、成本及安全要求选择合适的系统设计，避免过度架构。

## 🧪 综合实践项目

| 项目                      | 核心技术                           | 难度 |
| ------------------------- | ---------------------------------- | ---- |
| AI Chatbot                | LLM API、多轮对话、Streaming       | 入门 |
| PDF Chat                  | 文档解析、Embedding、Basic RAG     | 入门 |
| Document Extraction       | OCR、多模态模型、Structured Output | 入门 |
| Resume Analyzer           | 文档理解、结构化提取、信息匹配     | 入门 |
| Enterprise Knowledge Base | Hybrid Search、Reranking、权限控制 | 进阶 |
| AI Search Engine          | 搜索、检索、总结、来源引用         | 进阶 |
| AI Code Assistant         | 代码索引、代码检索、Tool Calling   | 进阶 |
| Text-to-SQL               | Schema 检索、SQL 生成、安全校验    | 进阶 |
| AI Customer Service       | RAG、Agent、业务工具、人工接管     | 进阶 |
| Voice Assistant           | STT、LLM、TTS、实时交互            | 进阶 |
| Research Agent            | 任务规划、搜索、信息验证、报告生成 | 高级 |
| Multi-Agent System        | 多智能体协作、工作流、状态管理     | 高级 |
| AI Gateway                | 模型路由、限流、缓存、成本管理     | 高级 |
| Local AI Platform         | 本地模型部署、GPU 推理、私有知识库 | 高级 |

综合项目应尽可能整合真实业务场景中的功能需求，并关注系统的可维护性、可靠性、安全性和运行成本。

## 🏗️ 项目设计原则

### Minimal — 最小化

每个 Demo 聚焦一个明确的技术问题，避免引入不必要的业务逻辑、框架和复杂架构。

### Independent — 独立性

各 Demo 尽可能独立运行，减少不同实验之间的耦合。

### Runnable — 可运行

代码不仅用于阅读，也应能够实际运行并验证技术行为。

### Reproducible — 可复现

明确记录模型版本、数据集、依赖版本、实验环境、配置参数和实验步骤。

### Explainable — 可解释

关注算法、模型及系统的基本原理，而不仅仅是框架 API 的使用方式。

### Testable — 可测试

通过测试验证确定性逻辑、工具调用、数据处理、异常处理及边界条件。

### Measurable — 可评估

通过明确的评估数据集、指标和实验方法衡量 AI 应用的质量与性能。

### Secure — 安全性

关注数据隐私、模型输出安全、Prompt Injection、工具权限及敏感信息保护。

### Cost-aware — 成本意识

关注 Token 消耗、模型 API 费用、GPU 资源、存储成本及系统运行成本。

### Documented — 可查阅

记录技术原理、实现方式、实验结果、应用场景、常见问题及参考资料。

### Extensible — 可扩展

支持未来加入新的模型、算法、框架、编程语言及技术领域。

### Practical — 实用性

关注实际 AI 应用中的问题与解决方案，而不仅仅是模型调用和理论学习。

## 🔄 学习与实践流程

```text
Learn       学习理论与技术原理
    ↓
Implement   编写最小可运行示例
    ↓
Experiment  进行技术实验
    ↓
Evaluate    评估模型与应用效果
    ↓
Test        验证功能与边界条件
    ↓
Document    记录知识与实验结果
    ↓
Compare     对比模型与技术方案
    ↓
Apply       应用于实际业务项目
    ↓
Monitor     监控质量、性能与成本
    ↓
Improve     持续优化与完善
```

通过持续实践，将人工智能理论知识转化为可复用的 AI 工程能力。

## 📋 开发与学习路线

以下为初始规划，将根据实际学习进度持续调整。

### Phase 1 — AI Fundamentals

- [ ] Python 科学计算
- [ ] 线性代数
- [ ] 概率论与统计学
- [ ] 梯度下降
- [ ] NumPy
- [ ] Pandas
- [ ] 数据清洗与预处理
- [ ] 数据可视化
- [ ] Jupyter Notebook

### Phase 2 — Machine Learning

- [ ] Scikit-learn
- [ ] 线性回归
- [ ] 逻辑回归
- [ ] 决策树
- [ ] 随机森林
- [ ] SVM
- [ ] 聚类算法
- [ ] 降维算法
- [ ] 特征工程
- [ ] 模型评估
- [ ] 超参数优化

### Phase 3 — Deep Learning

- [ ] PyTorch
- [ ] Tensor 与 Autograd
- [ ] 神经网络
- [ ] 前向传播与反向传播
- [ ] 损失函数与优化器
- [ ] CNN
- [ ] RNN 与 LSTM
- [ ] Attention
- [ ] Transformer
- [ ] Hugging Face Transformers
- [ ] GPU 训练基础

### Phase 4 — LLM Application Development

- [ ] LLM API
- [ ] Tokenization
- [ ] Prompt Engineering
- [ ] Context Engineering
- [ ] 多轮对话
- [ ] Streaming
- [ ] Structured Output
- [ ] Tool Calling
- [ ] 多模型接入
- [ ] 本地模型 Ollama
- [ ] Token 与成本管理

### Phase 5 — RAG

- [ ] Embedding
- [ ] 向量数据库
- [ ] 文档解析
- [ ] Chunking
- [ ] 文档索引
- [ ] Basic RAG
- [ ] BM25
- [ ] Hybrid Search
- [ ] Reranking
- [ ] Query Rewriting
- [ ] Graph RAG
- [ ] Agentic RAG
- [ ] RAG Evaluation

### Phase 6 — Agent & MCP

- [ ] 原生 Agent Loop
- [ ] Tool Calling
- [ ] ReAct
- [ ] Agent Memory
- [ ] Planning
- [ ] Workflow
- [ ] LangGraph
- [ ] OpenAI Agents SDK
- [ ] MCP Server
- [ ] MCP Client
- [ ] 多语言 MCP 开发
- [ ] Human-in-the-loop
- [ ] Checkpointing
- [ ] Multi-Agent
- [ ] Agent Evaluation

### Phase 7 — Multimodal AI

- [ ] 图像理解
- [ ] 文档理解
- [ ] 图像生成
- [ ] OCR
- [ ] Speech-to-Text
- [ ] Text-to-Speech
- [ ] 音频理解
- [ ] 视频理解
- [ ] 多模态 RAG
- [ ] 实时语音交互

### Phase 8 — AI Engineering

- [ ] FastAPI AI 服务
- [ ] LLM Gateway
- [ ] Streaming API
- [ ] 异步推理任务
- [ ] Semantic Cache
- [ ] Rate Limiting
- [ ] Retry & Fallback
- [ ] Model Routing
- [ ] Conversation Management
- [ ] 多租户架构
- [ ] AI Security
- [ ] AI Evaluation
- [ ] Docker 部署

### Phase 9 — Fine-tuning & Model Serving

- [ ] 数据集准备
- [ ] Supervised Fine-tuning
- [ ] PEFT
- [ ] LoRA
- [ ] QLoRA
- [ ] DPO
- [ ] 模型量化
- [ ] 模型导出
- [ ] llama.cpp
- [ ] vLLM
- [ ] ONNX Runtime
- [ ] GPU 推理优化
- [ ] 推理性能测试

### Phase 10 — MLOps & LLMOps

- [ ] MLflow
- [ ] DVC
- [ ] Experiment Tracking
- [ ] Model Registry
- [ ] Model Monitoring
- [ ] Langfuse
- [ ] LangSmith
- [ ] OpenTelemetry
- [ ] Prompt Versioning
- [ ] Token Monitoring
- [ ] Cost Monitoring
- [ ] 持续评估
- [ ] CI/CD
- [ ] Kubernetes

### Phase 11 — Practical Projects

- [ ] AI Chatbot
- [ ] PDF Chat
- [ ] Enterprise Knowledge Base
- [ ] AI Search Engine
- [ ] AI Code Assistant
- [ ] Document Extraction
- [ ] Resume Analyzer
- [ ] Text-to-SQL
- [ ] AI Customer Service
- [ ] Research Agent
- [ ] Voice Assistant
- [ ] Multi-Agent System
- [ ] AI Gateway
- [ ] Local AI Platform

以上阶段并非严格的前置依赖关系，可以根据实际目标并行学习。例如，LLM、RAG 和 Agent 应用开发可以与机器学习、深度学习基础同步开展。

## 📐 代码与提交规范

### 代码规范

- 遵循各编程语言的官方编码规范。
- Python 代码遵循 PEP 8。
- 优先使用清晰的变量、函数、类及目录名称。
- 合理使用 Python Type Hints。
- 使用 Ruff 进行代码检查与格式化。
- 使用 pytest 编写自动化测试。
- 优先保证代码正确性、可读性及可维护性。
- 避免过度设计与不必要的抽象。
- 模型参数、Prompt 和业务配置应尽可能独立管理。
- 对关键算法、技术原理和异常场景添加必要说明。
- 不在代码中硬编码 API Key、密码及敏感配置。
- 不将未经验证的模型输出直接用于数据库写入、命令执行或其他敏感操作。

### Git 提交规范

推荐使用 Conventional Commits 规范。

```text
feat(ml): add linear regression example
feat(dl): implement self attention
feat(llm): add streaming response example
feat(rag): implement hybrid retrieval
feat(agent): add basic agent loop
feat(mcp): add python mcp server
feat(multimodal): add document understanding
feat(serving): add vllm inference example
feat(finetune): add lora training example
feat(eval): add rag evaluation dataset
fix(rag): fix document chunking issue
fix(agent): handle tool execution timeout
docs(llm): explain context window
docs(rag): explain retrieval strategies
test(agent): add tool calling tests
refactor(llm): simplify provider integration
perf(serving): optimize inference batching
chore(infra): update docker compose
```

## 📊 实验与评估规范

AI 系统的输出可能存在随机性，因此传统软件测试与 AI 质量评估应结合使用。

### 确定性测试

主要验证：

- 数据处理逻辑
- 文档解析
- 文本切分
- API 请求与响应
- 工具参数校验
- 权限控制
- 状态管理
- 异常处理
- 重试与超时
- 资源释放

### AI 质量评估

主要验证：

- 回答正确性
- 回答相关性
- 事实一致性
- 引用准确性
- 检索质量
- 任务完成率
- 工具调用正确性
- 输出格式正确性
- 安全性
- 稳定性

### 性能与成本评估

主要记录：

- Time to First Token（TTFT）
- Time per Output Token（TPOT）
- Tokens per Second
- End-to-End Latency
- P50 / P95 / P99 Latency
- Requests per Second
- 输入与输出 Token 数量
- 单次请求成本
- CPU 与 GPU 使用率
- 内存与显存占用
- 任务成功率

评估结果应结合具体任务、模型版本、实验环境和数据集进行分析。

LLM-as-a-Judge 等自动化评估方法可能存在偏差，重要实验应结合人工评估或可信的参考答案进行验证。

## 🔐 数据、安全与隐私

本项目应遵循以下基本原则：

- 不提交真实 API Key、密码、Token 或访问凭证。
- 不提交未经授权的个人数据、企业数据及敏感文档。
- 使用公开、合成或经过适当脱敏的数据集进行实验。
- 记录数据集来源、使用许可及适用范围。
- 调用外部模型 API 前确认数据是否允许传输至第三方。
- 对用户输入、外部文档及工具返回结果保持不可信假设。
- 不将 Prompt 视为可靠的安全边界。
- 对 Agent 工具调用实施最小权限控制。
- 对高风险或不可逆操作设置人工审批。
- 对模型生成的 SQL、代码及命令进行验证和必要的隔离。
- 对 RAG 文档检索实施用户权限及数据隔离。
- 避免在日志与链路追踪中记录敏感信息。
- 关注 GDPR 及其他适用的数据保护要求。
- 遵守模型、数据集、第三方代码及服务的使用许可。

## 💾 模型与数据文件管理

Git 仓库主要用于管理源代码、配置文件、文档和小型示例数据。

以下内容不建议直接提交至 Git：

- 大型模型权重
- 模型 Checkpoint
- 大型训练数据集
- 大型向量索引文件
- 虚拟环境
- 模型缓存
- 训练日志
- 推理缓存
- 临时实验文件
- 敏感配置文件

`.gitignore` 参考：

```gitignore
# Python
__pycache__/
*.py[cod]
.venv/
venv/
.pytest_cache/
.ruff_cache/
.mypy_cache/

# Environment
.env
.env.*
!.env.example

# Jupyter
.ipynb_checkpoints/

# Models
*.safetensors
*.gguf
*.ckpt
*.pt
*.pth
*.onnx
checkpoints/
model-weights/

# Experiment outputs
outputs/
artifacts/
runs/
logs/
wandb/
mlruns/
mlartifacts/

# Datasets
datasets/raw/
datasets/private/
datasets/processed/

# Local databases
*.sqlite3
chroma_db/
vector-store/

# JavaScript
node_modules/
dist/

# Java
target/

# .NET
bin/
obj/

# IDE
.idea/
.vscode/

# OS
.DS_Store
Thumbs.db
```

根据实际需求，可以使用以下工具管理大型文件与实验产物：

- Hugging Face Hub
- ModelScope
- DVC
- Git LFS
- MLflow
- MinIO
- S3 兼容对象存储

模型与数据的管理方式应符合其许可证及数据隐私要求。

## 📖 参考资料

### 数学与机器学习

- [Mathematics for Machine Learning](https://mml-book.github.io/)
- [3Blue1Brown](https://www.3blue1brown.com/)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course)
- [Deep Learning Book](https://www.deeplearningbook.org/)
- [Dive into Deep Learning](https://d2l.ai/)

### Python 与数据科学

- [Python Documentation](https://docs.python.org/3/)
- [NumPy](https://numpy.org/doc/)
- [Pandas](https://pandas.pydata.org/docs/)
- [Polars](https://docs.pola.rs/)
- [SciPy](https://docs.scipy.org/)
- [Matplotlib](https://matplotlib.org/stable/)
- [Jupyter](https://docs.jupyter.org/)
- [uv](https://docs.astral.sh/uv/)

### 深度学习与模型生态

- [PyTorch](https://pytorch.org/docs/)
- [TensorFlow](https://www.tensorflow.org/)
- [JAX](https://docs.jax.dev/)
- [Hugging Face](https://huggingface.co/docs)
- [Hugging Face LLM Course](https://huggingface.co/learn/llm-course/)
- [ModelScope](https://modelscope.cn/)
- [OpenCV](https://docs.opencv.org/)

### 大语言模型

- [OpenAI API Documentation](https://platform.openai.com/docs/)
- [Anthropic Documentation](https://docs.anthropic.com/)
- [Google Gemini API](https://ai.google.dev/gemini-api/docs)
- [DeepSeek API](https://api-docs.deepseek.com/)
- [Qwen](https://github.com/QwenLM)
- [Mistral AI](https://docs.mistral.ai/)

### RAG 与向量数据库

- [LangChain](https://docs.langchain.com/)
- [LlamaIndex](https://docs.llamaindex.ai/)
- [Sentence Transformers](https://sbert.net/)
- [FAISS](https://github.com/facebookresearch/faiss)
- [Qdrant](https://qdrant.tech/documentation/)
- [Milvus](https://milvus.io/docs)
- [Weaviate](https://docs.weaviate.io/)
- [pgvector](https://github.com/pgvector/pgvector)
- [Elasticsearch](https://www.elastic.co/docs)

### Agent 与 MCP

- [LangGraph](https://docs.langchain.com/)
- [OpenAI Agents SDK](https://openai.github.io/openai-agents-python/)
- [Pydantic AI](https://ai.pydantic.dev/)
- [CrewAI](https://docs.crewai.com/)
- [Model Context Protocol](https://modelcontextprotocol.io/)

### 多语言 AI 应用开发

- [Spring AI](https://docs.spring.io/spring-ai/reference/)
- [LangChain4j](https://docs.langchain4j.dev/)
- [Semantic Kernel](https://learn.microsoft.com/semantic-kernel/)
- [Microsoft.Extensions.AI](https://learn.microsoft.com/dotnet/ai/)
- [Vercel AI SDK](https://ai-sdk.dev/)
- [Eino](https://github.com/cloudwego/eino)

### 模型微调与推理部署

- [PEFT](https://huggingface.co/docs/peft/)
- [TRL](https://huggingface.co/docs/trl/)
- [Accelerate](https://huggingface.co/docs/accelerate/)
- [DeepSpeed](https://www.deepspeed.ai/)
- [Ollama](https://ollama.com/)
- [llama.cpp](https://github.com/ggml-org/llama.cpp)
- [vLLM](https://docs.vllm.ai/)
- [ONNX Runtime](https://onnxruntime.ai/docs/)
- [NVIDIA CUDA](https://docs.nvidia.com/cuda/)

### AI 工程化与评估

- [FastAPI](https://fastapi.tiangolo.com/)
- [Pydantic](https://docs.pydantic.dev/)
- [Ragas](https://docs.ragas.io/)
- [DeepEval](https://deepeval.com/docs/)
- [MLflow](https://mlflow.org/docs/)
- [DVC](https://dvc.org/doc)
- [Langfuse](https://langfuse.com/docs)
- [LangSmith](https://docs.langchain.com/langsmith/)
- [OpenTelemetry](https://opentelemetry.io/docs/)
- [OWASP GenAI Security Project](https://genai.owasp.org/)

### 经典论文

- [Attention Is All You Need](https://arxiv.org/abs/1706.03762)
- [BERT](https://arxiv.org/abs/1810.04805)
- [Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165)
- [Retrieval-Augmented Generation](https://arxiv.org/abs/2005.11401)
- [LoRA](https://arxiv.org/abs/2106.09685)
- [Training Language Models to Follow Instructions with Human Feedback](https://arxiv.org/abs/2203.02155)
- [ReAct](https://arxiv.org/abs/2210.03629)
- [QLoRA](https://arxiv.org/abs/2305.14314)
- [Direct Preference Optimization](https://arxiv.org/abs/2305.18290)
- [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://arxiv.org/abs/2309.06180)






