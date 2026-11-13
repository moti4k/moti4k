# Gired: retrieval and recommendations

**Ongoing product development · AI engineering**

Gired matches people with work based on the content of their experience: the tasks they performed, their projects and the evidence behind those claims.

## My work

- Hybrid retrieval and matching between experience and job responsibilities.
- Evidence-linked comparisons, so a recommendation can be traced back to the relevant source material.
- Cold-start work using manually labelled examples and few-shot matching.
- Dynamic updates to recommendations as profiles, source material and user feedback change.
- Evaluation of false support, partial coverage and unknown requirements, rather than relying on technology-keyword overlap alone.

## Evaluation lesson

In an AI-assisted ML workflow, I found that strategy parameters had been selected using test data. I removed the agent's access to the test set to prevent further tuning against it. Once test data has influenced model selection, a fresh held-out evaluation is needed to estimate future performance reliably.

Gired is under active development. Source code and operational data are private; this page summarises the engineering work and evaluation concerns.

[Back to profile](../README.md)
