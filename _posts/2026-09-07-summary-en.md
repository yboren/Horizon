---
layout: default
title: "Horizon Summary: 2026-09-07 (EN)"
date: 2026-09-07
lang: en
---

> From 33 items, 10 important content pieces were selected

---

1. [Bryan Cantrill on the Intellectual Risks of Using LLMs for Writing](#item-1) ⭐️ 9.0/10
2. [Asahi Linux Officially Adds Support for Apple M3 Chips](#item-2) ⭐️ 9.0/10
3. [OpenAI Shifts Toward Recursive Self-Improvement and Agentic Engineering](#item-3) ⭐️ 9.0/10
4. [It took a year to ship WebAssembly in Anubis](#item-4) ⭐️ 8.0/10
5. [A/I shuts down](#item-5) ⭐️ 8.0/10
6. [The purpose of DNS is to spread scams](#item-6) ⭐️ 8.0/10
7. [There's No Limit to How Bad Code Can Get](#item-7) ⭐️ 8.0/10
8. [Reproducibility seems to be headed towards irrelevance in ML research. Is it too late? (D)](#item-8) ⭐️ 8.0/10
9. [Proposed architecture for inferencing sparse MOE models increasing Active parameters using layered + linear decay. Succinct reasoning without any model training or fine tune. (p)](#item-9) ⭐️ 8.0/10
10. [Apple Adjusts EU App Store Fees to Comply with Digital Markets Act](#item-10) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Bryan Cantrill on the Intellectual Risks of Using LLMs for Writing](https://bcantrill.dtrace.org/2025/12/05/your-intellectual-fly-is-open/) ⭐️ 9.0/10

Bryan Cantrill argues that using LLMs to author technical content obscures a writer's unique voice and original thought process, characterizing it as a failure of intellectual honesty. He contends that the act of writing is inseparable from the act of thinking. This critique highlights the erosion of personal integrity in professional communication as AI tools become ubiquitous. It challenges creators to consider whether they are outsourcing their cognitive labor rather than just their drafting process. Cantrill emphasizes that LLMs are fundamentally 'lousy writers' that lack the personal quirks and authentic perspective that define a human author. He warns that relying on AI for content creation leaves the reader unable to distinguish between genuine insight and generated filler.

hackernews · cyb0rg0 · Sep 6, 11:56 · [Discussion](https://news.ycombinator.com/item?id=49585644)

**Background**: Bryan Cantrill is a well-known software engineer and systems programmer, recognized for his work on DTrace and his contributions to the tech industry. The discussion reflects a growing tension in the tech community regarding the balance between productivity gains from AI and the preservation of authentic human expression.

**Discussion**: The community largely agrees with Cantrill, emphasizing that writing is a form of thinking that clarifies one's own views. Commenters also expressed concerns about the loss of individual style and the potential for AI-generated content to feel hollow or deceptive.

**Tags**: `#LLM`, `#Writing`, `#Intellectual Integrity`, `#Technical Communication`, `#AI Ethics`

---

<a id="item-2"></a>
## [Asahi Linux Officially Adds Support for Apple M3 Chips](https://asahilinux.org/2026/09/m2-episode-1/) ⭐️ 9.0/10

The Asahi Linux project has officially announced support for Apple M3 silicon, marking a significant milestone in enabling Linux to run on the latest Apple hardware. This update expands the project's compatibility to include the M3 chip architecture. This achievement is critical for hardware freedom, as it allows users to run open-source operating systems on proprietary Apple Silicon. It demonstrates the effectiveness of community-driven reverse engineering in overcoming the lack of official documentation from Apple. The project relies on extensive reverse engineering of Apple's proprietary SoCs to provide Linux support. Users should note that certain features like sleep mode and HDMI output may still face limitations during the ongoing development process.

hackernews · mdp2021 · Sep 6, 14:08 · [Discussion](https://news.ycombinator.com/item?id=49586698)

**Background**: Asahi Linux is an open-source project dedicated to porting the Linux kernel to Apple Silicon Macs. Since Apple does not provide public documentation for its custom chips, the team must reverse-engineer the hardware to enable functionality. This work is essential for users who want to use Linux on modern Apple hardware.

<details><summary>References</summary>
<ul>
<li><a href="https://asahilinux.org/">Asahi Linux</a></li>
<li><a href="https://en.wikipedia.org/wiki/Asahi_linux_project">Asahi linux project</a></li>

</ul>
</details>

**Discussion**: The community is highly impressed by the technical achievement but expresses frustration that such efforts are necessary due to Apple's closed ecosystem. Some users noted that while the project is amazing, missing features like sleep support and performance gaps in specific workloads like llama.cpp remain barriers to daily adoption.

**Tags**: `#Linux`, `#Apple Silicon`, `#Reverse Engineering`, `#Open Source`, `#Hardware`

---

<a id="item-3"></a>
## [OpenAI Shifts Toward Recursive Self-Improvement and Agentic Engineering](https://simonwillison.net/2026/Sep/6/research-acceleration-the-view-inside-openai/) ⭐️ 9.0/10

OpenAI has officially prioritized recursive self-improvement (RSI) as a core research strategy and reported a massive surge in the use of coding agents among its researchers throughout 2026. Data indicates that daily AI compute expenditure per researcher increased significantly by late August 2026, likely driven by access to advanced models like GPT-6 Astra. This shift marks a critical milestone in AI development, as OpenAI moves toward systems capable of autonomously enhancing their own capabilities. The widespread adoption of agentic engineering suggests that the future of AI research will be defined by human-AI collaboration where autonomous agents handle complex coding and iterative development tasks. Internal charts show a steep climb in AI spending per researcher starting in late July 2026, coinciding with the internal deployment of new, more capable models. The term 'RSI' is now being used internally at OpenAI to describe their path toward AGI, emphasizing the role of AI in accelerating its own development cycle.

rss · Simon Willison · Sep 6, 23:57

**Background**: Recursive self-improvement is a theoretical process where an AI system enhances its own code and architecture, potentially leading to an intelligence explosion. Agentic engineering is a software development practice where developers orchestrate autonomous AI agents to plan, execute, and refine code, moving beyond simple code completion to complex, multi-step task automation.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Recursive_self-improvement">Recursive self-improvement</a></li>
<li><a href="https://grokipedia.com/page/Agentic_Engineering">Agentic Engineering</a></li>
<li><a href="https://simonwillison.net/guides/agentic-engineering-patterns/what-is-agentic-engineering/">What is agentic engineering? - Agentic Engineering Patterns - Simon Willison's Weblog</a></li>

</ul>
</details>

**Discussion**: The community is intrigued by the rapid acceleration in AI spend and the explicit mention of RSI, with many speculating that this indicates a major breakthrough in model capabilities. Observers are closely watching how these internal research methodologies might influence the broader industry's approach to AGI development.

**Tags**: `#OpenAI`, `#AGI`, `#Agentic Engineering`, `#AI Research`, `#Recursive Self-Improvement`

---

<a id="item-4"></a>
## [It took a year to ship WebAssembly in Anubis](https://anubis.techaro.lol/blog/2026/anubis-wasm/) ⭐️ 8.0/10

The author details the year-long journey of integrating WebAssembly into the Anubis anti-bot system to improve security and complicate automated solver generation.

hackernews · xena · Sep 6, 20:32 · [Discussion](https://news.ycombinator.com/item?id=49590611)

**Tags**: `#WebAssembly`, `#Cybersecurity`, `#Bot-Detection`, `#Software-Engineering`, `#Systems-Architecture`

---

<a id="item-5"></a>
## [A/I shuts down](https://keepitfree.ai/announcements/a/i-shuts-down-stay-human/) ⭐️ 8.0/10

The A/I collective has announced its shutdown following a US government designation linking its services to international sabotage, raising critical questions about political risk and infrastructure neutrality.

hackernews · captainmuon · Sep 6, 14:34 · [Discussion](https://news.ycombinator.com/item?id=49586898)

**Tags**: `#infrastructure`, `#geopolitics`, `#privacy`, `#censorship`, `#internet-policy`

---

<a id="item-6"></a>
## [The purpose of DNS is to spread scams](https://simonwillison.net/2026/Sep/6/the-purpose-of-dns-is-to-spread-scams/) ⭐️ 8.0/10

A report on the alarming prevalence of cybercriminal activity, revealing that up to 20% of newly registered gTLD domains are used for scams.

rss · Simon Willison · Sep 6, 14:40

**Tags**: `#DNS`, `#Cybersecurity`, `#ICANN`, `#Internet Infrastructure`, `#Domain Abuse`

---

<a id="item-7"></a>
## [There's No Limit to How Bad Code Can Get](https://simonwillison.net/2026/Sep/6/theres-no-limit-to-how-bad-code-can-get/) ⭐️ 8.0/10

The author argues that rewriting legacy systems from scratch rarely succeeds because the original system continues to accumulate technical debt while the new project struggles to keep pace with evolving business requirements.

rss · Simon Willison · Sep 6, 09:08

**Tags**: `#software engineering`, `#technical debt`, `#legacy systems`, `#project management`

---

<a id="item-8"></a>
## [Reproducibility seems to be headed towards irrelevance in ML research. Is it too late? (D)](https://www.reddit.com/r/MachineLearning/comments/1w92eis/reproducibility_seems_to_be_headed_towards/) ⭐️ 8.0/10

The post argues that machine learning research is increasingly irreproducible due to the high cost of specialized hardware and the lack of transparency from large AI companies.

reddit · r/MachineLearning · /u/NeighborhoodFatCat · Sep 6, 17:29

**Tags**: `#machine learning`, `#reproducibility`, `#ai research`, `#transparency`, `#industry trends`

---

<a id="item-9"></a>
## [Proposed architecture for inferencing sparse MOE models increasing Active parameters using layered + linear decay. Succinct reasoning without any model training or fine tune. (p)](https://www.reddit.com/r/MachineLearning/comments/1w94dtn/proposed_architecture_for_inferencing_sparse_moe/) ⭐️ 8.0/10

A new runtime-only architecture for llama.cpp that allows increasing the number of active experts in sparse Mixture-of-Experts models through adaptive thresholding and influence decay.

reddit · r/MachineLearning · /u/Specific-Tax-6700 · Sep 6, 18:41

**Tags**: `#LLM`, `#MoE`, `#llama.cpp`, `#Inference Optimization`, `#Machine Learning`

---

<a id="item-10"></a>
## [Apple Adjusts EU App Store Fees to Comply with Digital Markets Act](https://t.me/zaihuapd/43648) ⭐️ 8.0/10

Starting October 1, Apple is updating its EU developer terms to charge a 5% Core Technology Fee for alternative distribution and a 20% commission for alternative payment systems, while eliminating initial acquisition and store service fees. This adjustment represents a significant shift in Apple's business model to align with the EU's Digital Markets Act, potentially lowering costs for developers and increasing competition in the mobile ecosystem. Under the new structure, the commission for alternative payments can be reduced to 10% for developers participating in the App Store Small Business Program.

telegram · zaihuapd · Sep 7, 02:24

**Background**: The Digital Markets Act (DMA) is a European Union regulation designed to ensure fair competition in the digital sector by limiting the power of 'gatekeeper' companies like Apple. Previously, Apple faced criticism for its high commission rates and strict control over app distribution, leading to these regulatory pressures.

**Tags**: `#Apple`, `#EU`, `#Digital Markets Act`, `#App Store`, `#Mobile Development`

---