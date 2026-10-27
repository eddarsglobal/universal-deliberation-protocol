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

## Why use UDP? Practical value for real users

AI can draft an answer quickly. UDP is designed to help users **decide whether that answer is justified, sufficiently checked, safe to act on, or still uncertain**. It aims for accountability without turning every simple question into a lengthy debate.

| You want to… | How UDP may help | What still needs verification |
|---|---|---|
| Research a topic | Separate sourced facts from assumptions, outdated claims and questionable citations | Whether sources really support the statements |
| Develop or maintain software | Inspect existing work, challenge failure modes and prevent unsupported "fixed" claims | Actual code, tests, regressions and deployment evidence |
| Make a business decision | Compare alternatives, assumptions, objections and missing information | Actual costs, risks, constraints and outcomes |
| Review an AI answer or report | Extract consequential claims, find errors and produce a corrected assessment | Independent evidence for the corrections |
| Operate an AI agent | Define authority before side effects and make actions auditable | Real permissions, logs and tool outputs |
| Learn or study | Distinguish explanations, uncertainty and ways to check understanding | Course materials and primary sources |

**The potential value is a more controlled process, not guaranteed correctness, savings or financial profit.** UDP v2.1.0 is not yet benchmarked. Measured improvement claims require actual comparative evidence.

## Start using UDP — step by step

The full [canonical UDP v2.1.0 specification](universal_deliberation_protocol_v2.1.0.md) is **the only UDP protocol**. There are no Lite, Core or Full editions. Its internal modes adjust the depth of checking according to task risk, urgency and complexity.

### 1. Give your AI access to the complete protocol

1. Open or download **[universal_deliberation_protocol_v2.1.0.md](universal_deliberation_protocol_v2.1.0.md)**. You can use the GitHub Raw view or download the Markdown.
2. Provide the **complete specification** using a feature your environment supports:
   - **Web/chat assistants** (ChatGPT, Claude, Gemini and similar): attach the Markdown to your conversation, project, or knowledge context, or paste its full text if needed.
   - **Persistent/custom instructions:** when supported, make the complete specification available through the product's instructions or reference files. Check context and file-retrieval limits; merely remembering "use UDP" is not the same as supplying the document.
   - **APIs and local/offline LLMs:** place the complete document in an authorized instruction/context input within the model's actual context budget and instruction hierarchy.
   - **AI agents:** reference or load the canonical document in the agent's supported configuration; tool permissions and approval controls remain external to UDP.
3. Confirm access. Ask the model to identify **Article 11's internal modes** and **Article 33's REVIEW procedure** specifically from the provided document. If it cannot access them, supply the file in a supported form.

**Important:** A GitHub URL alone does not guarantee that an AI can open it. Uploading a file does not prove it was understood or followed. The specification cannot grant tool access or override the host's higher-priority instructions.

### 2. Give the AI a real task

After supplying the full document, try this **ordinary task request**. It is a usage example, **not a replacement protocol or abbreviated edition**:

> Apply the attached Universal Deliberation Protocol v2.1.0 to this task: [describe your task]. Select the appropriate internal mode, distinguish verified facts from assumptions, challenge material weaknesses, and state exactly which checks you actually performed and which remain unverified. Give a clear, useful final answer rather than a theatrical debate transcript.

You do not need to manually appoint five fictional AI characters, buy access to multiple models, install any specific framework or adopt a second UDP version.

### 3. Inspect the result before relying on it

A useful UDP-guided response should demonstrate:

1. **A relevant answer:** the result directly addresses the task.
2. **A traceable basis:** important claims have appropriate evidence or are marked as inferred/unverified.
3. **A meaningful challenge:** serious weaknesses are examined without fabricated objections.
4. **Honest execution reporting:** terms such as tested, fixed, installed, deployed or certified are supported by actual results, not merely asserted.
5. **A scope-bound conclusion:** residual uncertainty and relevant limits are visible; actions with side effects require appropriate authorization.

If these checks fail, request correction or invoke the **REVIEW** procedure described below. An AI saying it followed UDP is not independent evidence of conformity.

## Ready-to-use task examples

These prompts assume the **complete canonical UDP v2.1.0 file is already available** to the AI. They are examples of user requests, not alternative protocol editions.

### Everyday research

> Using UDP, compare the evidence for [claim A] and [claim B]. Separate verified facts from inference, state what would change the conclusion, and cite only sources actually consulted. Mark sources that cannot be accessed.

**Expected value:** more visible uncertainties and clearer reasons for believing a claim.

### Software development and debugging

> Using UDP, inspect the existing code and project resources before proposing new files or functionality. Investigate [bug or feature], locate existing implementations, propose the smallest safe correction, and identify tests and regression risks. Do not modify anything without my authorization; do not claim tests ran unless they actually did.

**Expected value:** fewer needless duplicates and claims of successful fixes unsupported by real tests.

### Business strategy

> Using UDP, evaluate [business decision]. Compare realistic alternatives, expose assumptions, identify the most material failure scenarios, and specify the data required to decide. Do not invent revenue, demand, ROI or regulatory facts. Make a recommendation bounded by available evidence.

**Expected value:** a decision with explicit assumptions and checks instead of a confident but unjustified forecast.

### Audit an existing AI answer — even if the producing AI never used UDP

Give the model the **full UDP specification** and the answer you want checked:

> Apply UDP Article 33 (REVIEW) to the following AI response: [paste response]. Extract material claims, flag unsupported or time-sensitive assertions, check high-risk claims against sources/tools actually available, challenge the strongest weakness, and produce a corrected answer. Separate what is verified, unverified and inconclusive.

**Expected value:** a systematic review process that can be used with output from any model. The reviewer can still be mistaken, so important findings require corroboration.

### Agents performing real-world work

> Using UDP, plan [goal]. First inspect the existing state, actual permissions and available tools. Distinguish intended actions from executed actions, request authorization when necessary, and record outcomes and uncertainties. Do not treat simulated checks as real evidence.

**Expected value:** clearer evidence of what an agent actually did, what it was authorized to do and what it has not proven.

## Applying the same UDP across AI systems

| Environment | How to make the canonical specification available | Limitation |
|---|---|---|
| ChatGPT, Claude, Gemini and similar services | Attach the Markdown to a supported conversation or project; use supported saved instruction/knowledge features | Features, context retrieval and instruction priority vary |
| Local models (including Llama, Qwen and others) | Supply the full specification in the local runtime's authorized prompt/context | Context limits and instruction-following reliability vary |
| Custom apps and APIs | Load the same file through the application's supported instruction mechanism | Applications must provide their own tools, permissions and checks |
| Single- and multi-agent systems | Use the same canonical source in agent configurations and enforce host permissions | Simulated roles are not independent experts |
| Reports or answers generated elsewhere | Give a reviewer the full file and apply Article 33 REVIEW | Review does not by itself establish factual correctness |

**No provider, paid subscription, operating system, agent framework or separate Guardian is required by the UDP specification.** Practical compatibility must be tested in each target environment.

## Prove its usefulness in your workflow

Try representative tasks **with and without UDP** under comparable conditions. Record incorrect claims, unsupported citations, real defects found, false alarms, time, tool use and token costs. Independently verify consequential results. Publish reproducible successes **and** negative findings.

One favorable anecdote is not proof of a general improvement. UDP is a proposed specification: transparent testing is part of the contribution opportunity.


## Status and evidence

UDP v2.1.0 is a **proposed open-source specification**. Its current status is `SPECIFICATION_DRAFT`, `NOT_BENCHMARKED`, and `NOT_CERTIFIED`. Structural review or licensing does **not** establish effectiveness across models, compliance certification, or formal ISO/IETF status. Reproducible benchmarks and independent evaluations are welcome.

## Contributing

We welcome issues, counterexamples, reproductions, translations, tests, evidence-backed corrections, and pull requests from anyone. Please read [CONTRIBUTING.md](CONTRIBUTING.md). Substantive normative changes should explain the problem, proposed amendment, compatibility impact, and how to evaluate the result.

The intention is a **universal public protocol**, not a private extension of ChatGPT, MAESTRO, NANOVERSAI, or any other particular product or project.

## Attribution and license

**Created by Noureddine Eddars · initially published by EddarsGlobal.** This repository is offered under the [Apache License, Version 2.0](LICENSE). Please preserve applicable copyright and attribution notices in source redistributions and the [NOTICE](NOTICE) attribution as required by the license. The license permits use and modification subject to its terms; it does not require permission to contribute ideas or use UDP with a specific provider.

## Citation

Citation metadata is in [`CITATION.cff`](CITATION.cff). For scientific use, distinguish protocol adoption from any yet-to-be-demonstrated effectiveness claims.
