# Technical risk prompts — curated, not exhaustive

**Purpose:** A selective reference for the **Risk Profiles** evidence element. These are example failure modes and inquiry questions, **not a formal mapping of NIST or OWASP categories**. Ask which risks actually apply to the proposed architecture; do not mechanically enumerate them all. Consult [primary sources](sources.md) for exact definitions and current categorizations.

| Situation | What to consider | Questions to investigate |
| --- | --- | --- |
| Generated answers and recommendations | Confabulation, unsupported claims, overconfidence, variable outputs | Where is an unsupported claim consequential? How is correctness independently evaluated? |
| Ambiguous requests or long context | Missed instructions, omitted qualifiers, context-window and attention limits | Which critical facts could be ignored, and how would anyone notice? |
| Training and evaluation | Unrepresentative data, learned historical patterns, leakage between tests and development | What groups or conditions are underrepresented? Is the evaluation independent? |
| Prompt and content handling | Prompt injection through direct input or retrieved documents | Can untrusted text manipulate instructions or tool behavior? |
| Retrieval-augmented generation (RAG) | Stale or poisoned documents, failed retrieval, incorrect citations, conflicting policy versions | What makes a source authoritative, current, and correct for this user? |
| System integration | Insecure output handling, weak validation, brittle interfaces, error propagation | What happens if a generated parameter or answer is consumed as trusted input? |
| Tool-enabled or agentic systems | Excessive agency, unauthorized actions, unsafe permissions, loops, cascade failures | What can it do without review? What permissions, budgets, approvals, rollback and logs exist? |
| Confidentiality and privacy | Sensitive data exposure through prompts, logs, outputs, integrations or model misuse | What data enters each component, and who can see or retain it? |
| Abuse and availability | Resource exhaustion, deliberate misuse, third-party service or supply-chain compromise | What happens when the service is attacked, unavailable, or unexpectedly expensive? |
| Monitoring and change | Drift, upstream data changes, inconsistent behavior across updates | Which outcomes matter after launch, and who can pause or roll back? |

## Use with the canvas, not instead of it

For example, an insurance draft can be technically well-formed yet still fail people because photos miss physical evidence, reviewers are under pressure, and appeal mechanisms are weak. **Technical risks and sociotechnical harms are related but distinct.** See [sociotechnical risk library](sociotechnical-risk-library.md).

## Framework links

- [OWASP GenAI LLM Top 10 (2026)](https://genai.owasp.org/resource/owasp-genai-llm-top-10-2026/) — security vulnerabilities associated with LLM applications.
- [OWASP Top 10 for Agentic Applications (2026)](https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/) — autonomy, tool use and agent security; **not all apply to nonagentic decision support**.
- [NIST AI RMF (AI 100-1)](https://doi.org/10.6028/NIST.AI.100-1) — broader risk management and trustworthiness.
- [NIST GenAI Profile (AI 600-1)](https://doi.org/10.6028/NIST.AI.600-1) — generative-AI-specific risks and actions.

**No fixed exhaustive taxonomy is promised.** Framework editions and category labels may change; rely on the linked primary documents when making formal claims.
