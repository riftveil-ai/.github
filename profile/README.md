# AI will never be held accountable. You will.

When a decision prepared with AI is questioned, nobody holds the AI assistant to account. They hold the person who signed. Riftveil is the human oversight layer between an AI output and your signature: an open protocol that challenges the output before you sign, never validates it, and leaves a record you can defend.

## [riftveil-protocol](https://github.com/riftveil-ai/riftveil-protocol) · open, Apache 2.0

The full protocol. Paste it into ChatGPT, Claude or Microsoft 365 Copilot, or run it through an API. No software to install.

- **It never says "looks good".** Four absolute rules: never validate, never rewrite, never conclude, never assume the challenge is complete.
- **Stakes first.** Triage on three criteria (reversibility, impact scope, financial commitment) sets how far the examination goes.
- **Five levels of examination**, from the question actually asked to how the decision plays out on the ground.
- **AI agents too**: a pre-action review, before a plan sends, pays or deletes anything.
- **A report that ends on questions**, each with the role of the person who can answer it, where that role can be inferred.

What a report shows first (the protocol's worked example):

```
Record
- Triage: HIGH · examined: question, answer, reasoning, perspective · not examined: applicability
- Findings: 5, by impact CRITICAL: 0 · HIGH: 2 · MODERATE: 3 · LOW: 0
- Assumptions: 5 with a named verifier · 0 without
- Questions: 5 with an owner · 2 without
- Most useful question: "What is the calculation behind the €2.4M figure: what are the inputs and how sensitive is the output to changes in those inputs?"
- Independence: not stated by the user, to be confirmed by the signer
```

## AttestScope · coming here soon

The open format for the *human accountability record*: what the signer checked, what they left open and to whom, what they decided, and proof that nothing has changed since. Its repository launches with Ed25519 signatures on records: anyone will be able to verify a record on their own, without going through the issuer. The format: [attestscope.ai](https://attestscope.ai)

## Why open

Asking a model "are you sure?" is not a method: without external feedback, a model is poor at correcting its own errors (Huang et al., ICLR 2024). And a tool that cross-examines must itself be open to cross-examination: the protocol is published in full.

## Try it, contribute

Online: [riftveil.ai](https://riftveil.ai) · In your AI assistant: [the protocol file](https://github.com/riftveil-ai/riftveil-protocol/blob/main/protocol/RIFTVEIL_PROTOCOL.md) · [Contributions wanted](https://github.com/riftveil-ai/riftveil-protocol/blob/main/CONTRIBUTING.md): a detection heuristic, a reproducible failure case, a translation or a tested integration.

## The method

Riftveil implements the method set out in *The Rift*, a forthcoming book by Olivier Laurent (2026). The method is built on the Human Frontier model: [humanfrontier.ai](https://humanfrontier.ai) · [hello@riftveil.ai](mailto:hello@riftveil.ai)
