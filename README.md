<!-- SPDX-License-Identifier: Apache-2.0 -->
# Universal Deliberation Protocol (UDP)

**One universal, evidence-driven protocol for disciplined AI reasoning, criticism, verification, and accountable decisions.**

> **Version:** 2.1.0  
> **Creator:** **Noureddine Eddars**  
> **Initial publisher:** **EddarsGlobal** (GitHub: [@eddarsglobal](https://github.com/eddarsglobal))  
> **License:** **Apache License 2.0** (`LICENSE`, `NOTICE`)  
> **Research status:** `SPECIFICATION_DRAFT` · `NOT_BENCHMARKED` · `NOT_CERTIFIED`

## The protocol

**[Read the full Universal Deliberation Protocol v2.1.0](universal_deliberation_protocol_v2.1.0.md)**

UDP is a provider-neutral specification for forming, challenging, evaluating, correcting, and auditing AI-assisted answers and decisions. It is designed to be adaptable to different languages, domains, LLMs, multimodal models, local or hosted runtimes, assistants, and agent systems **when those systems can observe the relevant obligations**. No particular model, service, vendor, proprietary runtime, or agent framework is required by the specification.

**Foundational rule:**

> **No claim without a basis. No certification without evidence. No execution without authority. No convergence by consensus alone.**

## What makes UDP different?

- **Truth and evidence:** keep observations, hypotheses, calculations, and missing evidence distinct.
- **Substantive criticism:** search for material counterexamples without manufacturing objections.
- **Verification instead of theatrical consensus:** five simulated perspectives in one model do **not** become five independent experts.
- **Authority boundaries:** an instruction file cannot grant its own privileges or claim certification.
- **One protocol:** internal task modes adjust the required effort; there are **no Lite/Core/Full editions**.
- **Audit existing output:** UDP can assess an answer produced by a model that never used UDP.
- **Scoped conclusions:** claims such as `PASS`, `DEPLOYED`, or `CERTIFIED` require matching evidence and authority.

## Using UDP

1. Read the [canonical specification](universal_deliberation_protocol_v2.1.0.md), including its preamble, Articles 1–50, mode selection, and verification rules.
2. Adopt the applicable instructions through the permissions and configuration features of your chosen AI environment. A pasted prompt or Markdown file does not override higher-priority instructions or create tool access.
3. For a consequential answer, establish the request, evidence, counterarguments, checks, uncertainties, and scope-limited result as defined by the protocol.
4. To evaluate existing AI answers, use the **REVIEW** mode and audit procedure described by the same specification.
5. Report honestly which checks actually ran. **No third-party validation or universal performance claim is established by the specification alone.**

## Status and evidence

UDP v2.1.0 is a **proposed open-source specification**. Its current status is `SPECIFICATION_DRAFT`, `NOT_BENCHMARKED`, and `NOT_CERTIFIED`. Structural review or licensing does **not** establish effectiveness across models, compliance certification, or formal ISO/IETF status. Reproducible benchmarks and independent evaluations are welcome.

## Contributing

We welcome issues, counterexamples, reproductions, translations, tests, evidence-backed corrections, and pull requests from anyone. Please read [CONTRIBUTING.md](CONTRIBUTING.md). Substantive normative changes should explain the problem, proposed amendment, compatibility impact, and how to evaluate the result.

The intention is a **universal public protocol**, not a private extension of ChatGPT, MAESTRO, NANOVERSAI, or any other particular product or project.

## Attribution and license

**Created by Noureddine Eddars · initially published by EddarsGlobal.** This repository is offered under the [Apache License, Version 2.0](LICENSE). Please preserve applicable copyright and attribution notices in source redistributions and the [NOTICE](NOTICE) attribution as required by the license. The license permits use and modification subject to its terms; it does not require permission to contribute ideas or use UDP with a specific provider.

## Citation

Citation metadata is in [`CITATION.cff`](CITATION.cff). For scientific use, distinguish protocol adoption from any yet-to-be-demonstrated effectiveness claims.
