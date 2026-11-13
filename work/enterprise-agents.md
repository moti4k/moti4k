# Enterprise agents and evaluation

**Acta · Applied AI engineering and technical leadership**

I worked on an enterprise-agent system and voice assistants, and led four developers across agent implementation, MCP integrations, token accounting and the product's web/backend work.

## Engineering and leadership

- Conducted technical interviews, reviewed code, delegated work and made architectural decisions.
- Worked on agent orchestration, tool-use controls and adherence to task boundaries.
- Used **PyRIT** for more complex adversarial scenarios and **garak** for baseline checks, integrating tests into CI/CD and maintaining a separate research/verification pipeline.
- Tested document-based prompt injection, data leakage, forbidden tool calls and deviation from the intended task.

## A concrete control boundary

In one case, an agent attempted actions outside its container boundary. The runtime monitoring layer detected dangerous command patterns, terminated processes created by the agent, notified the user and escalated the event for human review. This incident informed subsequent changes to the controls.

I treated runtime controls and adversarial testing as separate layers: defining failure cases, checking regressions and using observed incidents to improve the controls.

## Voice systems

I also worked on ASR, TTS and language-model adaptation for voice assistants, including speech expressiveness and real-time inference concerns.

Implementation details and client material remain private; this page describes my responsibilities and the engineering approach.

[Back to profile](../README.md)
