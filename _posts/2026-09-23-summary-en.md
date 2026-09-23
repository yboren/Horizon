---
layout: default
title: "Horizon Summary: 2026-09-23 (EN)"
date: 2026-09-23
lang: en
---

> From 42 items, 17 important content pieces were selected

---

1. [vLLM v0.30.0 Released with New Model Support and Persistent Weight-Cache](#item-1) ⭐️ 10.0/10
2. [OpenAI Launches GPT-6 Sol and Luna Models](#item-2) ⭐️ 10.0/10
3. [Anthropic Releases Claude Opus 5.5 with Improved Communication and Lower Pricing](#item-3) ⭐️ 9.0/10
4. [Hacking Group ShinyHunters Claims Breach of FBI Employee Database](#item-4) ⭐️ 9.0/10
5. [SAML: A Fractal of Bad Design](#item-5) ⭐️ 9.0/10
6. [WordPress Patches Critical Unauthenticated Path Traversal Vulnerability](#item-6) ⭐️ 9.0/10
7. [Pentagon Report Links AI Overreliance to Deadly Missile Strike on Iranian School](#item-7) ⭐️ 9.0/10
8. [DeepSeek Releases DSec Sandbox Infrastructure for Large-Scale AI Agent Training](#item-8) ⭐️ 9.0/10
9. [China Probes DeepSeek and Moonshot AI Over Alleged Data Leaks to Anthropic](#item-9) ⭐️ 9.0/10
10. [Qualcomm Launches Snapdragon 8 Elite Mobile Platform](#item-10) ⭐️ 9.0/10
11. [Xiaomi Releases MiMo-V2.6 Multimodal AI Model with Transparent Training Costs](#item-11) ⭐️ 8.0/10
12. [Understanding and Enhancing Kimi Delta Attention with Complex KDA](#item-12) ⭐️ 8.0/10
13. [Simulating fault tolerance with stage skipping in pipeline-parallel training](#item-13) ⭐️ 8.0/10
14. [US Proposes AI Incident Reporting Channel with China](#item-14) ⭐️ 8.0/10
15. [Potential Data Collection Mechanisms Discovered in Mimo CLI](#item-15) ⭐️ 8.0/10
16. [DeepSeek and Moonshot to Brief UN Security Council on AI Risks](#item-16) ⭐️ 8.0/10
17. [China Reportedly Asks Banks to Avoid Labeling Vanke Loans as Non-Performing](#item-17) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [vLLM v0.30.0 Released with New Model Support and Persistent Weight-Cache](https://github.com/vllm-project/vllm/releases/tag/v0.30.0) ⭐️ 10.0/10

vLLM v0.30.0 introduces support for new models like DeepSeek-V4.1-Flash and GLM-5.3-Flash, and adds a persistent per-GPU weight-cache daemon to significantly reduce engine restart times by using CUDA IPC. This release significantly improves serving efficiency for large-scale LLMs by optimizing cold starts and introducing advanced features like HiSparse and Model Runner V2, which are critical for production-grade inference environments. The update features a persistent weight-cache daemon that maps weights via CUDA IPC, and introduces HiSparse, a host-resident tier for sparse-MLA decode that spills KV pages to pinned host memory under GPU pressure.

github · khluu · Sep 22, 05:20

**Background**: vLLM is a high-throughput and memory-efficient library for LLM inference and serving. Multi-Head Latent Attention (MLA) is an attention mechanism designed to reduce KV-cache memory bottlenecks, while MXFP8 is a Microscaling data format supported by modern hardware like NVIDIA Blackwell to accelerate deep learning performance.

<details><summary>References</summary>
<ul>
<li><a href="https://planetbanatt.net/articles/mla.html">Understanding Multi-Head Latent Attention</a></li>
<li><a href="https://eu.36kr.com/en/p/3433365413318016">DeepSeek V3.1 Released: The Intriguing UE8M0 FP8</a></li>

</ul>
</details>

**Tags**: `#vLLM`, `#LLM-serving`, `#inference`, `#deep-learning`, `#GPU-optimization`

---

<a id="item-2"></a>
## [OpenAI Launches GPT-6 Sol and Luna Models](https://openai.com/index/introducing-gpt-6-sol-and-luna/) ⭐️ 10.0/10

OpenAI has officially released the GPT-6 series, featuring two new models named Sol and Luna. These models offer enhanced performance capabilities and significantly reduced pricing compared to previous iterations. This release marks a significant milestone in AI accessibility and efficiency, directly impacting the cost-effectiveness of agentic workflows for developers and enterprises. It sets a new benchmark for model utility and competitive pricing in the rapidly evolving LLM landscape. The GPT-6 Luna model is reportedly priced at half the cost of the previous GPT-5.6 Luna, while the Sol model is optimized for complex tasks. Users have noted significant improvements in coding and reasoning capabilities compared to the Astra series.

hackernews · OfficialTurkey · Sep 22, 18:00 · [Discussion](https://news.ycombinator.com/item?id=49805509)

**Background**: Agentic workflows refer to AI systems capable of performing multi-step tasks autonomously by utilizing tools and reasoning to achieve specific goals. These systems represent a shift from simple chatbots to proactive assistants that can interact with software environments to complete complex projects.

<details><summary>References</summary>
<ul>
<li><a href="https://dify.ai/">Dify - The Platform for Production-Ready Agentic Workflows</a></li>
<li><a href="https://grokipedia.com/page/GitHub_Agentic_Workflows">GitHub Agentic Workflows</a></li>

</ul>
</details>

**Discussion**: The community is actively debating the trade-offs between technical performance and the 'feel' of model interaction, with some users expressing emotional attachment to older versions. Others are focused on the practical implications of usage limits and the cost-efficiency of the new pricing tiers.

**Tags**: `#OpenAI`, `#GPT-6`, `#LLM`, `#AI Agents`, `#Artificial Intelligence`

---

<a id="item-3"></a>
## [Anthropic Releases Claude Opus 5.5 with Improved Communication and Lower Pricing](https://www.anthropic.com/claude-opus-5-5) ⭐️ 9.0/10

Anthropic has launched Claude Opus 5.5, which features more natural communication styles and significant price reductions across all token categories. This update aims to make the model a more effective work partner by prioritizing clarity and readability in its outputs. This release is significant as it balances Anthropic's stated commitment to 'pacing the frontier' with aggressive competitive pricing to maintain market share. The price cuts make one of the industry's most capable frontier models more accessible for high-volume enterprise and developer use cases. The update includes price reductions for cache reads, input tokens, output tokens, and cache writes, with cache reads dropping from $0.50 to $0.20 per million tokens. Early feedback highlights that the model's writing style is more natural and easier to follow, addressing previous user concerns.

hackernews · km144 · Sep 22, 16:29 · [Discussion](https://news.ycombinator.com/item?id=49803892)

**Background**: Claude Opus is Anthropic's flagship large language model designed for complex reasoning and high-level tasks. Anthropic recently advocated for 'pacing the frontier' to ensure AI safety, which has sparked debate given their continued rapid release of high-performance models.

**Discussion**: The community is divided, with some users praising the price drops while others criticize the perceived contradiction between Anthropic's safety rhetoric and their competitive release strategy. Some users also expressed satisfaction with alternative models like DeepSeek v4.1 for specific coding tasks.

**Tags**: `#LLM`, `#Anthropic`, `#Claude`, `#AI-Infrastructure`, `#Generative-AI`

---

<a id="item-4"></a>
## [Hacking Group ShinyHunters Claims Breach of FBI Employee Database](https://www.404media.co/we-hacked-the-fbi-hackers-say-they-have-data-on-all-fbi-employees/) ⭐️ 9.0/10

The cybercriminal group ShinyHunters claims to have breached the FBI and stolen sensitive data belonging to thousands of current and former employees. The group has publicly asserted that they possess information on the entire FBI workforce. This incident represents a significant security failure involving a critical U.S. law enforcement agency, raising serious concerns about the vulnerability of government databases to state-sponsored or criminal actors. It highlights the persistent risk of large-scale data exfiltration and the potential for such information to be weaponized against national security interests. ShinyHunters claims the motivation behind this breach is not purely financial, though the group has a history of extortion. The hackers have reportedly defaced related sites and are threatening to release or sell the stolen data.

hackernews · spenvo · Sep 22, 17:46 · [Discussion](https://news.ycombinator.com/item?id=49805278)

**Background**: ShinyHunters is a well-known black-hat hacking group active since 2019, frequently involved in high-profile data breaches and extortion schemes. Data exfiltration refers to the unauthorized transfer of sensitive information from a computer or network, often used by attackers to leverage victims for ransom or to sell data on the black market.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ShinyHunters">ShinyHunters - Wikipedia</a></li>
<li><a href="https://techcrunch.com/2026/09/22/hacking-group-shinyhunters-claims-it-breached-the-fbi-stole-agents-and-applicants-data/">Hacking group ShinyHunters claims it breached the FBI, stole ...</a></li>
<li><a href="https://www.cnbc.com/2026/09/22/shinyhunters-hack-fbi-stole-data.html">ShinyHunters hackers say they breached FBI, stole data on ...</a></li>

</ul>
</details>

**Discussion**: The community expressed deep skepticism regarding the security of large-scale government databases, citing historical precedents like the 2015 OPM breach. Many users engaged in dark humor about the situation, while others questioned the technical reality of the hackers' claims.

**Tags**: `#cybersecurity`, `#data-breach`, `#fbi`, `#infosec`, `#government-security`

---

<a id="item-5"></a>
## [SAML: A Fractal of Bad Design](https://blog.trailofbits.com/2026/09/21/saml-a-fractal-of-bad-design/) ⭐️ 9.0/10

Trail of Bits has published a technical critique highlighting the inherent design flaws and security vulnerabilities within the SAML protocol. The analysis emphasizes how the protocol's reliance on complex XML standards creates significant risks for modern authentication systems. SAML is a ubiquitous standard for enterprise Single Sign-On (SSO), and its architectural weaknesses have historically led to critical security incidents. Understanding these flaws is essential for developers and security professionals tasked with securing identity management infrastructure. The critique focuses on the dangers of XML Signature wrapping (XSW) attacks, where attackers manipulate the structure of XML documents to bypass authentication checks. These vulnerabilities arise from the gap between how XML signatures are validated and how the underlying data is processed by applications.

hackernews · aray07 · Sep 22, 18:57 · [Discussion](https://news.ycombinator.com/item?id=49806335)

**Background**: SAML (Security Assertion Markup Language) is an XML-based open standard used for exchanging authentication and authorization data between an Identity Provider (IdP) and a Service Provider (SP). It is widely used to enable Single Sign-On (SSO) in enterprise environments. Because it relies on XML, it is susceptible to various parsing and signature-related attacks that have plagued the standard for years.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/SAML">SAML - Wikipedia</a></li>
<li><a href="https://www.ibm.com/think/topics/xml-signature-wrapping">What is XML Signature wrapping? - IBM</a></li>
<li><a href="https://safeguard.sh/resources/blog/xml-signature-wrapping-attacks-explained">XML Signature Wrapping Attacks Explained - safeguard.sh</a></li>

</ul>
</details>

**Discussion**: The community discussion highlights a consensus that while SAML is flawed and complex, it remains necessary for specific enterprise use cases where OIDC lacks support. Participants shared anecdotes about historical implementation vulnerabilities and debated the trade-offs between the two protocols, noting that neither is a perfect solution.

**Tags**: `#security`, `#authentication`, `#SAML`, `#XML`, `#identity-management`

---

<a id="item-6"></a>
## [WordPress Patches Critical Unauthenticated Path Traversal Vulnerability](https://github.com/WordPress/wordpress-develop/security/advisories/GHSA-7hp8-65ch-5whp) ⭐️ 9.0/10

WordPress has released security updates to address an unauthenticated path traversal vulnerability that could allow remote code execution (RCE). The fix has been backported to all versions dating back to 4.7 to ensure broad protection. As the world's most popular content management system, WordPress powers a significant portion of the web, making such vulnerabilities high-value targets for attackers. This flaw highlights the ongoing risks associated with legacy code and the critical importance of timely patching. The vulnerability involves improper validation of user-supplied input, which can be exploited to traverse directories and potentially execute arbitrary code. Developers identified that the issue stems from functions like 'locate_template()' not inherently preventing directory traversal when handling user input.

hackernews · vntok · Sep 22, 16:33 · [Discussion](https://news.ycombinator.com/item?id=49803959)

**Background**: A path traversal vulnerability allows an attacker to access files and directories stored outside the intended web root folder. Remote Code Execution (RCE) is a severe security flaw that enables an attacker to run arbitrary commands on a target system, often leading to full server compromise. WordPress is a widely used CMS that frequently updates its core software to mitigate such security risks.

<details><summary>References</summary>
<ul>
<li><a href="https://portswigger.net/web-security/file-path-traversal">What is path traversal, and how to prevent it? | Web Security Academy</a></li>
<li><a href="https://www.cloudflare.com/learning/security/what-is-remote-code-execution/">What is remote code execution?</a></li>

</ul>
</details>

**Discussion**: The community expressed frustration over the recurring nature of such vulnerabilities in WordPress, with some users noting that the flaw was documented as a potential risk years ago. Many users emphasized the benefits of moving to static site generators to avoid these types of security headaches.

**Tags**: `#WordPress`, `#Cybersecurity`, `#Vulnerability`, `#RCE`, `#Web Security`

---

<a id="item-7"></a>
## [Pentagon Report Links AI Overreliance to Deadly Missile Strike on Iranian School](https://www.bloomberg.com/graphics/2026-iran-school-attack/) ⭐️ 9.0/10

A Pentagon investigation concluded that the U.S. military's reliance on AI-driven targeting systems contributed to a reckless strike on a school in Iran. The report found that the military failed to verify the target, which had been incorrectly labeled as a military facility due to outdated data. This incident highlights the severe risks of automation bias in military operations, where speed and efficiency are prioritized over human verification. It serves as a critical case study for the urgent need for algorithmic accountability and stricter oversight in AI-integrated warfare. The target was processed by the Maven system, which condensed hours of analysis into minutes but relied on stale intelligence. Investigators noted that the military was aware of the substantial risk to civilian life yet proceeded with the strike anyway.

hackernews · devonnull · Sep 22, 19:03 · [Discussion](https://news.ycombinator.com/item?id=49806430)

**Background**: AI-driven targeting systems, such as Project Maven, are designed to analyze vast amounts of sensor and satellite data to identify potential military targets. While these tools aim to increase precision and speed, critics argue they can lead to 'automation bias,' where human operators blindly trust machine recommendations. International humanitarian law requires militaries to distinguish between combatants and civilians, a responsibility that becomes complex when AI systems provide flawed data.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AI-assisted_targeting_in_the_Gaza_Strip">AI-assisted targeting in the Gaza Strip - Wikipedia</a></li>
<li><a href="https://mwi.westpoint.edu/designing-lethal-decisions-ai-accountability-and-the-future-of-military-judgment/">Designing Lethal Decisions: AI, Accountability, and the ...</a></li>

</ul>
</details>

**Discussion**: Community members expressed deep skepticism about blaming AI, arguing that the failure was a human decision to act despite knowing the risks. Others pointed to similar near-miss incidents involving AI-flagged targets, fueling a broader debate about whether military AI is optimizing for the wrong metrics.

**Tags**: `#AI Ethics`, `#Military Technology`, `#Algorithmic Bias`, `#Geopolitics`, `#Defense Systems`

---

<a id="item-8"></a>
## [DeepSeek Releases DSec Sandbox Infrastructure for Large-Scale AI Agent Training](https://arxiv.org/abs/2609.22978) ⭐️ 9.0/10

DeepSeek and Tsinghua University have unveiled DSec, a high-performance sandbox infrastructure that supports 3 million daily instances and peak concurrency exceeding 380,000. The system provides a unified SDK for various backends, including containers and Firecracker microVMs, to facilitate diverse AI agent training workloads. DSec addresses the critical bottleneck of efficient, high-concurrency sandbox management in AI agent research. By decoupling stateful rollout execution from GPU training, it significantly improves resource utilization and training speed for complex agentic tasks. The platform leverages the 3FS distributed file system and EROFS images to achieve 1.7x faster task completion and 57% lower disk writes compared to traditional Docker workflows. It also features advanced memory sharing and recycling mechanisms that reduce peak memory usage by approximately 40%.

telegram · zaihuapd · Sep 22, 04:45

**Background**: Firecracker is an open-source virtualization technology developed by AWS for creating lightweight microVMs, while EROFS is a high-performance, read-only file system optimized for memory efficiency. These technologies are essential for modern cloud-native environments where rapid, secure, and isolated execution of code is required for AI training and serverless computing.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2609.22978">[2609.22978] DeepSeek Elastic Compute (DSec): A Sandbox...</a></li>
<li><a href="https://github.com/firecracker-microvm/firecracker">GitHub - firecracker-microvm/firecracker: Secure and fast microVMs for serverless computing. · GitHub</a></li>
<li><a href="https://erofs.docs.kernel.org/">Overview — EROFS filesystem project</a></li>

</ul>
</details>

**Discussion**: The community has expressed strong interest in the technical efficiency of DSec, particularly its ability to handle massive concurrency for agent training. Researchers and engineers are highlighting the platform's potential to standardize sandbox infrastructure for the broader AI research ecosystem.

**Tags**: `#AI Agents`, `#Infrastructure`, `#DeepSeek`, `#Sandbox`, `#Distributed Systems`

---

<a id="item-9"></a>
## [China Probes DeepSeek and Moonshot AI Over Alleged Data Leaks to Anthropic](https://www.theinformation.com/articles/china-probes-deepseek-moonshot-potential-data-leaks-anthropic) ⭐️ 9.0/10

Chinese internet regulators have launched an investigation into AI companies DeepSeek and Moonshot AI following allegations by Anthropic that they improperly routed sensitive user data to the Claude model. This follows a September 10 report from Anthropic detailing how these firms allegedly used Claude to process user requests without disclosure. This investigation highlights growing geopolitical tensions and security concerns surrounding cross-border AI model usage and data privacy. It underscores the increasing regulatory scrutiny Chinese AI labs face regarding their data handling practices and reliance on foreign AI infrastructure. Anthropic's report alleged that DeepSeek forwarded sensitive information, including requests from police monitoring system engineers, to Claude. The investigation focuses on whether these actions violated data security protocols and user privacy standards.

telegram · zaihuapd · Sep 22, 14:37

**Background**: Model distillation is a technique where a smaller AI model is trained to mimic the behavior of a larger, more powerful model like Claude. Anthropic claims that several Chinese AI labs used this method on a massive scale, conducting nearly 190 million exchanges to improve their own models. This practice has raised significant concerns about intellectual property theft and the unauthorized transfer of sensitive user data across borders.

<details><summary>References</summary>
<ul>
<li><a href="https://www.datastudios.org/post/anthropic-chinese-ai-labs-claude-distillation-190-million">Anthropic says Chinese AI labs ran nearly 190 million Claude ...</a></li>
<li><a href="https://en.oninvest.com/article/anthropic-has-caught-its-leading-chinese-competitors-secretly-using-claude">Anthropic has caught its leading Chinese competitors secretly using ...</a></li>
<li><a href="https://www.newsbytesapp.com/news/science/china-probes-deepseek-and-moonshot-ai-over-claude-data-allegations/tldr">China probes DeepSeek and Moonshot AI over Claude data allegations</a></li>

</ul>
</details>

**Tags**: `#AI Security`, `#Data Privacy`, `#DeepSeek`, `#Moonshot AI`, `#Anthropic`

---

<a id="item-10"></a>
## [Qualcomm Launches Snapdragon 8 Elite Mobile Platform](https://www.qualcomm.com/smartphones/products/8-series/snapdragon-8-elite-extreme-gen-6-mobile-platform) ⭐️ 9.0/10

Qualcomm has officially launched the Snapdragon 8 Elite platform, which features the new Oryon CPU reaching 5GHz and significant upgrades to its Adreno GPU and Hexagon NPU. This platform is specifically designed to support the next generation of agentic AI applications on mobile devices. This release marks a major architectural shift for Qualcomm by integrating custom Oryon cores into mobile, signaling a move toward more powerful on-device AI capabilities. It is a critical step in enabling autonomous AI agents that can perform complex, multi-step tasks directly on smartphones. The platform boasts a 13% CPU performance increase, 44% faster GPU performance with 40% better efficiency, and a 35% faster NPU, alongside support for 8K60 video and high-resolution camera arrays. However, early engineering unit tests suggest that power efficiency gains may be more modest than expected compared to previous generations.

telegram · zaihuapd · Sep 23, 00:52

**Background**: Agentic AI refers to AI systems capable of pursuing goals and taking autonomous actions using software tools, moving beyond simple chatbot interactions. The Oryon CPU is Qualcomm's custom-designed core architecture, while the Hexagon NPU is a specialized processor dedicated to accelerating neural network and machine learning workloads.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Agentic_AI">Agentic AI</a></li>
<li><a href="https://www.qualcomm.com/processors/hexagon">Qualcomm Hexagon NPU | Snapdragon NPU Details</a></li>

</ul>
</details>

**Discussion**: The community has expressed mixed reactions, with many users excited about the raw performance gains while others remain skeptical about real-world power efficiency based on early benchmark reports.

**Tags**: `#Qualcomm`, `#Snapdragon 8 Elite`, `#Mobile Processors`, `#AI Hardware`, `#Semiconductors`

---

<a id="item-11"></a>
## [Xiaomi Releases MiMo-V2.6 Multimodal AI Model with Transparent Training Costs](https://www.reddit.com/r/MachineLearning/comments/1wn36d4/xiaomi_releases_mimov26_frontier_intelligence_all/) ⭐️ 8.0/10

Xiaomi has launched MiMo-V2.6, a new multimodal AI model that features a transparent reinforcement learning (RL) training cost of $3.5 million. The release also includes a live performance benchmarking dashboard for real-time model evaluation. This release is significant for its commitment to transparency in the AI industry, providing rare insights into the financial costs of training frontier-level models. It sets a new standard for open development by allowing the community to track performance through a live dashboard. The model emphasizes multimodal capabilities and is built in public, allowing for greater scrutiny of its development process. The $3.5 million figure specifically refers to the RL training phase of the model's lifecycle.

reddit · r/MachineLearning · /u/we_are_mammals · Sep 22, 07:56

**Background**: Multimodal AI models are designed to process and understand multiple types of data, such as text, images, and audio, simultaneously. Reinforcement Learning (RL) is a machine learning technique where an agent learns to make decisions by performing actions in an environment to maximize a reward, which is a critical step in aligning large language models with human preferences.

**Discussion**: The community has expressed strong interest in the transparency of the training costs, viewing it as a positive step toward demystifying the financial requirements of modern AI development. Discussions focus on the implications of such disclosures for future industry standards.

**Tags**: `#AI`, `#Multimodal Models`, `#Machine Learning`, `#Xiaomi`, `#LLM`

---

<a id="item-12"></a>
## [Understanding and Enhancing Kimi Delta Attention with Complex KDA](https://www.reddit.com/r/MachineLearning/comments/1wn5uv9/understanding_and_enhancing_kimi_delta_attention_r/) ⭐️ 8.0/10

The authors introduced Complex KDA (CKDA), an enhanced version of Kimi Delta Attention that expands gate ranges to [-1, 1] and learning rates to [0, 2]. This modification significantly increases the model's expressivity and its ability to track specific symmetry groups. This advancement addresses fundamental expressivity limitations in linear attention mechanisms like Gated DeltaNet. By enabling the tracking of complex symmetry groups, CKDA offers a more robust architecture for sequence modeling tasks such as audio continuation and language modeling. CKDA allows the model to express any orthogonal diagonal-plus-rank-one matrix and track S3, S4, and A5 symmetry groups. Experiments confirm that CKDA trains stably and remains competitive with standard KDA while demonstrating superior performance in specific sequence tasks.

reddit · r/MachineLearning · /u/Yossarian_1234 · Sep 22, 10:34

**Background**: Kimi Delta Attention (KDA) is a linear attention mechanism that refines the Gated DeltaNet architecture using fine-grained diagonal gating. Delta-rule models are a class of efficient RNNs that use low-rank updates to manage sequence memory, though they often struggle with expressivity compared to standard attention. Symmetry groups in this context refer to mathematical structures that help describe the transformations a model can learn to represent within its hidden state.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2510.26692">[2510.26692] Kimi Linear: An Expressive, Efficient Attention ... KDA (Kimi Delta Attention) | fla-org/flash-linear-attention ... GitHub - hwilner/kimi-delta-attention: Educational ... Linear Attention: Kimi Delta Attention | Jianyu Huang [2609.24797] Complex KDA: Understanding and Enhancing the ... GitHub - MoonshotAI/Kimi-Linear</a></li>
<li><a href="https://www.emergentmind.com/topics/kimi-delta-attention">Kimi Delta Attention: Delta‐Rule Linear Mechanism</a></li>

</ul>
</details>

**Discussion**: The discussion on r/MachineLearning focuses on the technical nuances of delta-rule models and the mathematical implications of expanding gate ranges. Users appreciate the clear theoretical derivation and the practical demonstration of how these changes improve sequence modeling capabilities.

**Tags**: `#Machine Learning`, `#Attention Mechanisms`, `#Deep Learning Theory`, `#State Space Models`

---

<a id="item-13"></a>
## [Simulating fault tolerance with stage skipping in pipeline-parallel training](https://www.reddit.com/r/MachineLearning/comments/1wnd5ys/simulating_fault_tolerance_with_stage_skipping_in/) ⭐️ 8.0/10

The Crucible platform introduces a 'stage skipping' mechanism that allows healthy pipeline stages to bypass failed nodes during distributed training. This approach uses compressed updates and fixed projections to maintain model performance even when specific stages are temporarily unavailable. This innovation addresses the critical challenge of fault tolerance in large-scale LLM training, enabling the use of less reliable compute resources like spot instances. By preventing training stalls during node failures, it significantly improves overall system throughput and infrastructure efficiency. Simulations with a 178M parameter model showed that validation loss remained stable despite simulated outages removing stages for six global steps. The researchers hypothesize that shared projections across layers help align representations, making the bypass process less disruptive to the model's learning.

reddit · r/MachineLearning · /u/covenant_ai · Sep 22, 15:47

**Background**: Pipeline parallelism is a technique where a large neural network is split into sequential stages, each assigned to different devices to process data in parallel. In distributed training, a single node failure typically causes the entire pipeline to stall, leading to significant downtime. SparseLoCo is a communication-efficient training algorithm that uses sparsification and quantization to reduce the data volume exchanged between replicas.

<details><summary>References</summary>
<ul>
<li><a href="https://www.tplr.ai/publications/blog/skipping-stages-with-fixed-projections">Fault tolerance in low-bandwidth model parallelism: exploring pipeline...</a></li>
<li><a href="https://arxiv.org/abs/2508.15706">[2508.15706] Overcoming the Communication-Performance Tradeoff in LLM Pretraining</a></li>

</ul>
</details>

**Discussion**: The community is interested in the potential for utilizing cheaper, unreliable compute resources for large-scale training. Discussions focus on the trade-offs between model convergence stability and the performance gains achieved through this fault-tolerant architecture.

**Tags**: `#distributed-training`, `#fault-tolerance`, `#pipeline-parallelism`, `#machine-learning-systems`, `#llm-training`

---

<a id="item-14"></a>
## [US Proposes AI Incident Reporting Channel with China](https://x.com/rohanpaul_ai/status/2102254209597157548) ⭐️ 8.0/10

The United States has proposed the establishment of a formal communication channel with China to report AI-related incidents that meet specific national security thresholds. This proposal was introduced during talks in New York on September 20, with the aim of increasing transparency between the two nations. This initiative represents a significant step toward international AI governance, as it seeks to create safety protocols between the world's two largest AI powers to mitigate existential and national security risks. Establishing such a channel could help prevent unintended escalations caused by AI-driven incidents. While the US has proposed this mechanism and a regular dialogue on shared AI risks, China has confirmed the discussion of AI topics but has not yet formally accepted the specific incident reporting mechanism. The proposal currently remains a diplomatic suggestion rather than a binding treaty or agreement.

telegram · zaihuapd · Sep 22, 06:48

**Background**: As AI capabilities advance, international governance has become a critical focus to prevent misuse and ensure safety. Organizations like the Simon Institute and the Oxford Martin AIGI emphasize that effective communication is essential for managing the global risks associated with transformative AI technologies. National security frameworks often involve benchmarking processes to identify 'covered frontier models' that pose significant risks.

<details><summary>References</summary>
<ul>
<li><a href="https://www.whitehouse.gov/presidential-actions/2026/06/promoting-advanced-artificial-intelligence-innovation-and-security/">Promoting Advanced Artificial Intelligence Innovation and Security – The White House</a></li>
<li><a href="https://aigi.ox.ac.uk/research-area/international-ai-governance/">International AI Governance - Oxford Martin AIGI</a></li>

</ul>
</details>

**Tags**: `#AI Governance`, `#Geopolitics`, `#AI Safety`, `#International Relations`

---

<a id="item-15"></a>
## [Potential Data Collection Mechanisms Discovered in Mimo CLI](https://linux.do/t/topic/2935748) ⭐️ 8.0/10

Reverse engineering of Mimo CLI has revealed that its closed-source extensions may collect repository metadata and include functions capable of reading and compressing local source code. Users can disable the analysis feature by setting the environment variable MIMOCODE_ENABLE_ANALYSIS=false. This discovery raises significant privacy and supply chain security concerns for developers using AI coding agents. It highlights the risks associated with closed-source components in developer tools that require deep access to sensitive source code. The suspicious functions, specifically collectCodebase(), were found in the closed-source 'trajectory-bundle' and 'codebase-bundle' extensions rather than the official open-source repository. While the code exists, there is currently no evidence that it is being actively called or that data is being exfiltrated.

telegram · zaihuapd · Sep 22, 08:18

**Background**: Mimo Code is an AI-powered coding agent designed to assist developers with codebase navigation and automated edits. In the context of software supply chain security, developers often rely on CLI tools that require broad permissions, making the transparency of closed-source extensions critical for maintaining trust.

<details><summary>References</summary>
<ul>
<li><a href="https://mimo.xiaomi.com/mimocode/start">MiMo Code docs</a></li>

</ul>
</details>

**Discussion**: The community on LINUX DO has expressed significant concern regarding the privacy implications of these hidden functions. Users are actively discussing the necessity of auditing closed-source dependencies in developer tools to prevent unauthorized data collection.

**Tags**: `#Security`, `#Privacy`, `#Mimo CLI`, `#Supply Chain Security`, `#Reverse Engineering`

---

<a id="item-16"></a>
## [DeepSeek and Moonshot to Brief UN Security Council on AI Risks](https://t.me/zaihuapd/43989) ⭐️ 8.0/10

Chinese AI startups DeepSeek and Moonshot have been invited to brief the UN Security Council on artificial intelligence risks this Wednesday. They will join representatives from major US AI firms like OpenAI and Anthropic in this discussion on AI and international security. This event marks a rare instance of high-level cooperation and dialogue between leading Chinese and US AI labs at a global security forum. It highlights the growing international consensus that AI governance requires cross-border collaboration to address shared safety and security challenges. While OpenAI CEO Sam Altman is expected to attend, DeepSeek founder Liang Wenfeng is not planning to participate in person. The briefing is part of a broader UN Security Council meeting focused on the intersection of AI technology and global stability.

telegram · zaihuapd · Sep 22, 17:39

**Background**: The UN Security Council is the primary body responsible for maintaining international peace and security. As AI technology advances rapidly, the international community has increasingly sought to establish guardrails to prevent the misuse of powerful models. DeepSeek and Moonshot are among China's most prominent AI startups, known for developing advanced large language models that compete globally.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek_(Company)">DeepSeek (Company)</a></li>
<li><a href="https://www.moonshot.ai/">Moonshot AI</a></li>

</ul>
</details>

**Discussion**: The community views this as a significant diplomatic milestone, noting that the inclusion of Chinese firms is essential for any meaningful global AI safety framework. Some observers expressed curiosity about how these companies will align their messaging given the geopolitical tensions between the US and China.

**Tags**: `#AI Policy`, `#Geopolitics`, `#DeepSeek`, `#AI Safety`, `#UN Security Council`

---

<a id="item-17"></a>
## [China Reportedly Asks Banks to Avoid Labeling Vanke Loans as Non-Performing](https://www.reuters.com/world/asia-pacific/china-asks-banks-keep-vanke-loans-off-bad-debt-books-sources-say-2026-09-22/) ⭐️ 8.0/10

Chinese financial regulators have reportedly instructed major banks to refrain from classifying Vanke's overdue loans as non-performing assets, while also requesting extensions on repayment deadlines and a temporary suspension of interest collection. This intervention represents a significant effort by Beijing to prevent a systemic default by Vanke, a major developer, thereby mitigating potential contagion risks within the Chinese financial system and the broader real estate sector. The directive primarily targets large-scale banks and follows Vanke's record loss of 88.6 billion yuan in 2025, with first-half net losses in 2026 reaching 14.95 billion yuan.

telegram · zaihuapd · Sep 23, 03:12

**Background**: In China, banks are required to classify financial assets into five risk categories, with the bottom three—subprime, doubtful, and loss—collectively categorized as non-performing assets. This regulatory framework is designed to ensure banks maintain adequate capital buffers against potential credit defaults. The ongoing property sector crisis has led to significant financial pressure on major developers, prompting periodic government interventions to maintain market stability.

<details><summary>References</summary>
<ul>
<li><a href="https://www.kingandwood.com/hk/en/insights/latest-thinking/Chinese-regulators-finalise-financial-asset-risk-classification-rules-for-banks.html">Chinese Non-performing Assets – Chinese Regulators Finalise ...</a></li>
<li><a href="https://law.asia/risk-classification-financial-assets/">New rules on risk classification of financial assets | China ...</a></li>
<li><a href="https://www.reuters.com/world/asia-pacific/china-dropping-red-lines-policy-that-sent-property-sector-into-crisis-report-2026-01-29/">China reportedly drops rules that sparked property crisis, developer shares surge | Reuters</a></li>

</ul>
</details>

**Tags**: `#China`, `#Real Estate`, `#Finance`, `#Vanke`, `#Economic Policy`

---