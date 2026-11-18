# Projects, research and distinctions

A broader overview of my work in applied AI, model training and software engineering. The [main profile](../README.md) highlights a shorter selection. Public team implementations, independent client deployments and research projects are identified separately below.

## Client systems and product engineering

### Multimodal supplier-order automation · Independent client project · Aug–Oct 2025

Independently built an on-premises workflow from customer text, audio and photographs to structured orders in 1C. Combined BGE retrieval and cross-encoder reranking with a locally deployed, LoRA-adapted DeepSeek model. Worked on catalog matching, packaging, quantity interpretation and integration. By September 2026 the deployed workflow was processing approximately 10,000 orders per day.

[Workflow and contribution](order-automation.md)

### Enterprise agents and technical leadership · OpenCompany / Acta · Oct 2025–Jan 2026

Built enterprise agents with MCP integrations, orchestration and token accounting. Led three AI developers and coordinated a web/backend engineer, including interviewing, code review and work allocation. Used PyRIT and garak for adversarial checks integrated into CI/CD; worked on tool-use controls and runtime monitoring. Also worked on ASR/TTS and language-model adaptation for voice assistants.

[Agent controls and evaluation](enterprise-agents.md)

### Gired · Founder, product development and AI engineering · Feb 2026–present

Evidence-linked profiles and recommendations grounded in work and project experience. My work includes hybrid retrieval, cold-start relevance labels, few-shot matching, source-linked explanations and recommendation updates as profile information changes.

[Retrieval and recommendations](gired.md)

### Legal document intelligence · Independent client project · Oct 2025

Built an on-premises workflow covering OCR, document structuring, key-field extraction and retrieval, document review, amendment suggestions and structured obligation tables.

[Document workflow](legal-document-intelligence.md)

### Generative media · XLabs · Jun 2024–Aug 2025

Worked on FLUX image-model LoRA fine-tuning and LTX video-model adaptation for generative-media workflows and JGGL. Work included DPO, distillation and multi-GPU training, with access to an eight-H100 cluster.

[Model adaptation and speech](generative-models.md)

### Property-selection models · QLAN · Jan 2023–Feb 2024

Developed models for identifying undervalued apartments in Dubai, using gradient boosting, linear regression, feature engineering and selection; explored graph-based methods for property screening.

[Classical ML](classical-ml.md)

### Sellsnap · CTO · Sep–Dec 2025

Served as CTO of a startup with a team of ten developers. This was a concluded engagement; the startup has closed.

## Model research and independent engineering

### NEOAI 2026 · Task ideas and baseline implementations

Contributed ideas and baselines for six main-round tasks across vision, language, audio and tabular ML. Topics included distribution shift, author re-identification with damaged transformers, speech-speed detection with Whisper and extracting predictions from partially removed language models.

### Satellite-derived bathymetry · Applied research

Developed pixel-wise water-depth estimation using a U-Net with Swin Transformer and residual blocks, multiscale supervision and bottom-type-conditioned normalization. Evaluated on held-out water bodies and regions. The project received development-grant support in 2024.

[Architecture and evaluation](geospatial-ml.md)

### Whisper transcription optimization · 2025

Worked on transcription runtime, quantization and streaming. This concerned end-to-end speech transcription; no independently reproducible speedup figure is published here.

[Speech work](generative-models.md)

### Wildlife image retrieval · 2025

Developed an individual metric-learning and image-descriptor approach to grouping photographs of the same animal. This was a competition project; no specific leaderboard rank is claimed here.

### Molecular design with a VAE · 2024

Trained a variational autoencoder for molecular-design research.

### Edge vision and 3D-printer control · Personal project · 2023

Collected approximately 250 hours of printing footage and trained a YOLO-style detector for printing defects. Ran inference on Raspberry Pi, modified Klipper and printer hardware, and connected detected failures to automatic correction or stopping and a remote interface.

### Transformer implementation · Olympiad preparation

Implemented transformer components and training loops from scratch during preparation for international AI competition. This is model implementation and training experience, separate from the commercial systems above.

### Generative-content application · 2026

Developed a hosted media-generation application using FLUX, WAN and the ChatGPT API.

### C++ and systems programming · MIPT coursework · 2025–2026

Implemented containers, smart pointers, callable wrappers and allocator-aware structures. Coursework also included C/POSIX utilities, mmap and x86-64/AArch64 assembly. These are educational implementations, not a claim of professional kernel development.

## Public implementations

| Project | What is available | Context |
| --- | --- | --- |
| [Support-operator retrieval assistant](https://github.com/moti4k/The-Illusion-Of-Security) | BGE/FAISS retrieval, local vLLM inference, FastAPI, operator interface and Telegram integration. | Team challenge project, 2024. |
| [Business-support Q&A](https://github.com/moti4k/TINKOFF_LLM_CP2024) | Local language-model serving, knowledge-base matching, source links, FastAPI and LoRA/PEFT work. | Team challenge project, 2024. |
| [Contractor default-risk modelling](https://github.com/moti4k/aiijc_2024_samolet_scoring) | Financial/temporal features, CatBoost/Random Forest ensembles, validation and SHAP explanations. | First-place AI Challenge Development-track team solution. |
| [Satellite-image segmentation](https://github.com/moti4k/segmentation-TPSH) | PyTorch U-Net, training/inference notebooks, Dice/BCE losses and a Flask interface. | Computer-vision project, 2024–2026. |
| [Implicit-feedback recommendations](https://github.com/moti4k/BDIMO_2024) | RecTools, BM25 item-to-item recommendations and data preparation. | NTO 2023–2024 team work. |

These repositories are separate from the private client deployments. Linked code illustrates the stated implementation; a link does not imply that every historical environment has been freshly reproduced.

## Competition results and distinctions

- **International Olympiad in Artificial Intelligence (IOAI), 2025:** gold medal, fifth worldwide in the individual competition. [Official results](https://ioai-official.org/china-2025/results-2025/).
- **National Technology Olympiad, Big Data and Machine Learning:** winner in 2024 and 2025.
- **AI Challenge 2024, Development track:** first-place team solution with Artyom Goncharov. [Public implementation](https://github.com/moti4k/aiijc_2024_samolet_scoring).
- **Digital Breakthrough, St Petersburg, 2024:** prizewinner.
- **CODE Work Challenge, 2024:** winner among FEFU teams and overall prizewinner.
- **All-Siberian Mathematics Olympiad, 2024:** prizewinner.
- **Verchenko Mathematics Olympiad, 2025:** prizewinner.
- **All-Russian School Olympiad in Informatics:** regional winner in 2023–2025; national-final participant in 2025.
- **Vybirai AI project accelerator, 2024:** winner, with development-grant support for bathymetry research.

## Education and interests

Undergraduate studies at MIPT, FPMI, in Applied Mathematics and Computer Science, September 2025–expected June 2029. Deep Learning School, 2023–2024; Yandex.Lyceum Python programme, completed with honours, 2021–2023.

My interests span applied mathematics, training and understanding models, and connecting them to working products. Personal hardware projects complement my software work: cameras, embedded inference, printer firmware and controls.

[Back to profile](../README.md)
