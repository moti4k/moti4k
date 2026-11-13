# On-premises multimodal order automation

**Commercial deployment · Food Industry Client · 2026**

I independently built a system that turns incoming orders in text, audio and photographs into structured orders in the client's 1C system. The deployment runs locally and processes approximately **10,000 orders per day**.

## Workflow

```mermaid
flowchart LR
    A[Text, audio and images] --> B[Input processing]
    B --> C[Catalog and order-history retrieval]
    C --> D[Structured order interpretation]
    D --> E[1C integration]
```

## My contribution

- Implemented the complete workflow, including retrieval and the 1C integration.
- Used **BGE** for retrieval and a locally deployed **DeepSeek** model, adapted with LoRA.
- Iterated on retriever selection, matching logic and prompts using a client-provided dataset.
- Maintained a separate test set for evaluating the complete order, including product selection, packaging and quantity.

The important engineering boundary is between a plausible interpretation and the correct business action. A product match is only useful when the resulting order preserves the customer's intent through the final integration.

## Public material

Client data, model weights and source code remain private. The daily volume refers to orders processed by the complete deployed workflow.

[Back to profile](../README.md)
