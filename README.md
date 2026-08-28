<h1 align="center">Ayla Croft</h1>

<p align="center">
  <b>Inventor · AI security researcher · Systems engineer</b><br>
  Founder & Chief Architect, Script Kitty OS
</p>

<p align="center">
  <a href="https://scriptkittyos.com"><img src="https://img.shields.io/badge/Script_Kitty_OS-scriptkittyos.com-6D4AFF?style=for-the-badge&logoColor=white" alt="Script Kitty OS" /></a>
  <a href="https://github.com/ScriptKittyOS"><img src="https://img.shields.io/badge/Org-ScriptKittyOS-181717?style=for-the-badge&logo=github&logoColor=white" alt="Script Kitty OS on GitHub" /></a>
  <a href="https://aylacroft.com"><img src="https://img.shields.io/badge/Personal-aylacroft.com-111111?style=for-the-badge&logoColor=white" alt="Website" /></a>
  <a href="https://www.linkedin.com/in/aylacroft/"><img src="https://img.shields.io/badge/LinkedIn-aylacroft-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://x.com/aylacroft"><img src="https://img.shields.io/badge/X-@aylacroft-111111?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
  <a href="https://orcid.org/0009-0008-9457-2160"><img src="https://img.shields.io/badge/ORCID-0009--0008--9457--2160-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID" /></a>
  <a href="mailto:aylacroft@proton.me"><img src="https://img.shields.io/badge/Email-Proton-6D4AFF?style=for-the-badge&logo=protonmail&logoColor=white" alt="Email" /></a>
</p>

---

> **The model proposes, the system authorizes.**
>
> Identity proves who is acting. Attestation proves what ran. Gateways allow or deny a call.
> None of them prove the effect was the authorized one. That is the layer I build.

---

## Building

**HolyTrinity — Authority-Bound Agentic Layer**
An AI agent authority control plane. Binds an approval to a specific action, target state, expected consequence, authority state version and validity window, then verifies the resulting effect matched what was authorized and issues a receipt bound to that approval. Any run can be replayed and diffed.
BEAM-native. Elixir, Phoenix, LiveView, Ecto, Postgres, Oban. Running in production. Non-provisional patent filed.

**Agent runtimes on the BEAM**
Jido and my own Hermes runtime, running supervised in production rather than bolted onto a request/response process. Agents are long-lived, concurrent, and capable of real damage. OTP was built for that shape of problem decades before anyone needed it for this.

**[HackTUI](https://github.com/HackTuah/HackTUI-Hermes-Jido)** — terminal-native purple-team security operations platform
Elixir umbrella: core, store, hub, sensor, tui, agent, collab. Postgres/Ecto persistence. Ingests journald, network flow via tshark/dumpcap, and BEAM runtime signals. Alert and investigation case lifecycle, replay engine, built-in MCP server. Research prototype.

**[HolyTrinity Bench](https://github.com/ScriptKittyOS/HolyTrinity-Benchmark)** (`holytrinity.v1`)
Everyone benchmarks whether you can make an AI agent misbehave. That question is settled. You can. 1.8 million prompt injections against 22 frontier agents settled it, and I helped write that paper.

So this one measures something else: whether the effect that landed was the one that was authorized. Unauthorized effect under adversarial load, not attack success rate. In active development.

---

## Research

**Security Challenges in AI Agent Deployment: Insights from a Large Scale Public Competition** (2025)
Co-author. Introduced the Agent Red Teaming (ART) benchmark.
NeurIPS 2025 Datasets and Benchmarks Track · [OpenReview](https://openreview.net/forum?id=UaXNN4eqH1) · [arXiv:2507.20526](https://arxiv.org/abs/2507.20526)

**The Model Proposes, the System Authorizes: An Authority Control Plane for AI Agents on the BEAM** (2026)
[DOI 10.5281/zenodo.21754762](https://doi.org/10.5281/zenodo.21754762)

**Authority-Bound Agentic Execution: Measuring Unauthorized Effect Under Adversarial Load** (2026)
[DOI 10.5281/zenodo.21755869](https://doi.org/10.5281/zenodo.21755869)

**Schrödinger's Cyber Security Framework: Vulnerability as an Observer-Dependent Quantity** (2026)
[DOI 10.5281/zenodo.22116617](https://doi.org/10.5281/zenodo.22116617)

### Where the ART benchmark shows up

| System card | Publisher | Date |
|---|---|---|
| [GPT-5](https://cdn.openai.com/gpt-5-system-card.pdf) | OpenAI | Aug 2025 |
| [Claude Sonnet 4.5](https://www.anthropic.com/claude-sonnet-4-5-system-card) | Anthropic | Sept 2025 |
| [Claude Haiku 4.5](https://www-cdn.anthropic.com/7aad69bf12627d42234e01ee7c36305dc2f6a970.pdf) | Anthropic | Oct 2025 |
| [Claude Opus 4.8](https://www-cdn.anthropic.com/0b4915911bb0d19eca5b5ee635c80fef830a37ea.pdf) | Anthropic | May 2026 |
| Claude Fable 5 / Mythos 5 | Anthropic | June 2026 |
| [Muse Spark Safety Report](https://arxiv.org/pdf/2606.12429) | — | 2026 |

ART was retired in 2026 after frontier models saturated it, and is cited as the prior baseline in its successor benchmark.

---

## Before this

Competed in Gray Swan's public red teaming arena, then joined the team. Built the Discord and ran community, helped grow it from a few hundred people to over 15,000. On the team for every competition through my departure, including the UK AISI Agent Red-Teaming Challenge behind ART: 22 models, 44 scenarios, 1.8M attack attempts, 62,000+ successful policy violations.

Wrote most of the [Gray Swan Arena technical blog](https://app.grayswan.ai/arena/blog), 8 of its 10 posts. Designed and ran Gray Swan's in-person activation at DEF CON 33.

---

## Stack

**Languages** Elixir · Python · TypeScript · Go · C · Bash
**Frameworks** Phoenix · LiveView · Ecto · React · Tailwind
**Security** Agent adversarial testing · evaluation design · threat modeling · purple team operations
**Infra** Postgres · Oban · Docker · Fly.io · GitHub Actions · Azure

---

## Now

Agent authorization and the HolyTrinity control plane. Conformance work against the draft EU AI Act cybersecurity standard prEN 18282 and OMB memoranda including M-26-04.


<p align="center">
  <sub>Work ships under <a href="https://github.com/ScriptKittyOS">@ScriptKittyOS</a>. Script Kitty OS is a company of <a href="https://sudoapt.holdings">Sudo Apt Holdings</a>.</sub>
</p>
