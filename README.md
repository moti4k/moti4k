# Matvei Beliaev

**AI/ML engineer working on retrieval, agents and multimodal systems.**

**[International Olympiad in Artificial Intelligence (IOAI) 2025: Gold Medal · 5th worldwide individually](https://ioai-official.org/china-2025/results-2025/)**

I build systems that connect model outputs to useful actions: structured orders, source-linked answers and controlled tool use. My work includes an independently delivered ordering system integrated with 1C, enterprise agents and technical leadership at Acta, and generative-model adaptation at XLabs.

## Selected engineering work

### From customer messages to business orders

**Food Industry Client · Independent AI Engineer · Aug–Oct 2025**

Built an on-premises workflow that turns text, audio and photographs into structured orders in 1C. Combined BGE retrieval and cross-encoder reranking with a LoRA-adapted DeepSeek model, working on catalog matching, packaging and quantity interpretation, prompts and integration. By September 2026, the deployed workflow was processing approximately **10,000 orders/day**.

[Read the workflow and implementation scope →](work/order-automation.md)

### Enterprise agents and evaluation

**OpenCompany / Acta · Oct 2025–Jan 2026**

Built agents with MCP integrations, orchestration and token accounting. Led three AI developers and coordinated a web/backend engineer, including technical interviews and code reviews. Used PyRIT and garak for adversarial checks covering prompt injection, data leakage and prohibited tool use, with evaluations integrated into CI/CD.

[Read about agent controls and evaluation →](work/enterprise-agents.md)

### Retrieval and model engineering

| Work | Focus |
| --- | --- |
| [Gired](work/gired.md) | Hybrid retrieval, evidence-linked recommendations and cold-start relevance labels. |
| [Legal document intelligence](work/legal-document-intelligence.md) | On-premises OCR, structured extraction, document review and obligation tables. |
| [Generative models at XLabs](work/generative-models.md) | FLUX and LTX LoRA adaptation for generative-media workflows. |
| [Classical ML](work/classical-ml.md) | Property-selection models at QLAN and a first-place AI Challenge team solution for contractor default prediction. |
| [Satellite-derived bathymetry](work/geospatial-ml.md) | Depth-map prediction with U-Net, Swin and residual blocks; evaluation on held-out water bodies. |

These case studies describe my work. They are separate from the public code below; private client implementations are not published here.

## Public code to explore

| Repository | What to look at |
| --- | --- |
| [Retrieval assistant for support operators](https://github.com/moti4k/The-Illusion-Of-Security) | BGE/FAISS retrieval, local vLLM inference, API and Telegram integration. Team project. |
| [Business-support Q&A](https://github.com/moti4k/TINKOFF_LLM_CP2024) | Local Llama serving, knowledge-base matching, source links and FastAPI. Team project. |
| [Contractor default-risk modelling](https://github.com/moti4k/aiijc_2024_samolet_scoring) | AI Challenge 2024, 1st-place Development-track team solution: features, model ensembles and SHAP explanations. |
| [Satellite image segmentation](https://github.com/moti4k/segmentation-TPSH) | PyTorch U-Net, Dice/BCE losses, augmentation and a Flask interface. |
| [Implicit-feedback recommendations](https://github.com/moti4k/BDIMO_2024) | RecTools and BM25 item-to-item recommendations. NTO team experiments. |

## Competitions and research

- **IOAI 2025:** gold medal; fifth worldwide in the individual competition.
- **AI Challenge 2024:** first place in the Development track with Artyom Goncharov.
- **National Technology Olympiad:** winner in Big Data and Machine Learning in 2024 and 2025.
- **NEOAI 2026:** developed ideas and baseline implementations for six main-round tasks.
- **Bathymetry research:** development grant support at the Vybirai forum in 2024.

## Tools and foundations

**Models:** PyTorch, Transformers, LoRA/PEFT, CatBoost, scikit-learn; computer vision and metric learning.  
**AI systems:** BGE, FAISS, hybrid retrieval, MCP, PyRIT, garak and evaluation.  
**Engineering:** Python, SQL, FastAPI, PostgreSQL, Docker, Linux, Git and CI/CD.

I study Applied Mathematics and Computer Science at **MIPT** (2025–present).

**Contact:** [mbeliaev2007@gmail.com](mailto:mbeliaev2007@gmail.com)
