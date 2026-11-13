# On-premises legal document intelligence

**Commercial deployment · Legal industry client · October 2025**

I built an on-premises system for working with legal documents, from document ingestion to retrieval, review and structured obligations.

## Delivered workflow

1. Process scanned documents with **DeepSeek OCR**.
2. Structure the text into numbered sections and extract key values.
3. Retrieve relevant passages across the document collection.
4. Identify inconsistencies and propose amendments for review.
5. Produce a table of each party's obligations.

OCR, document structuring, retrieval, review and suggested amendments are used in the client's production deployment.

## Engineering focus

The task combines two problems: preserving document structure through ingestion, and making the relevant text available when reviewing a specific clause or obligation. Keeping these stages connected is more useful than treating OCR and question answering as separate demos.

I implemented the system end to end. The deployment is on-premises; client documents, prompts and source code are not included in the public portfolio.

[Back to profile](../README.md)
