---
layout: default
title: "Horizon Summary: 2026-07-30 (EN)"
date: 2026-07-30
lang: en
---

> From 38 items, 11 important content pieces were selected

---

1. [TurboFieldfare: Run 26B Gemma 4 Models on M-series Macs with 2GB RAM](#item-1) ⭐️ 9.0/10
2. [Superlogical](#item-2) ⭐️ 9.0/10
3. [Handbook.md shows that long policy documents do not reliably govern agents](#item-3) ⭐️ 9.0/10
4. [AI Worming through Word](#item-4) ⭐️ 9.0/10
5. [反网络暴力法征求意见稿公布，AI 网暴纳入规制](#item-5) ⭐️ 9.0/10
6. [OpenAI Launches Free Access Program for 100,000 Academic Researchers](#item-6) ⭐️ 9.0/10
7. [Top AI Startups Increasingly Prioritize Proprietary Research Over Public Disclosure](#item-7) ⭐️ 8.0/10
8. [Matthew Green on AI's Role in Post-Quantum Cryptanalysis](#item-8) ⭐️ 8.0/10
9. [The Rise of Modular 'LEGO-like' Data Center Construction](#item-9) ⭐️ 8.0/10
10. [Moonshot AI Seeks $2 Billion Funding at $30 Billion Valuation](#item-10) ⭐️ 8.0/10
11. [UK Proposes Relaxing Apple and Google App Payment Restrictions](#item-11) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [TurboFieldfare: Run 26B Gemma 4 Models on M-series Macs with 2GB RAM](https://github.com/drumih/turbo-fieldfare) ⭐️ 9.0/10

TurboFieldfare is a new inference engine built with Swift and Metal that allows running 26B parameter models on Apple Silicon by streaming routed experts from SSD. It keeps only the shared model components and KV cache in RAM, significantly reducing the memory footprint. This project demonstrates that large language models can be run on resource-constrained hardware by optimizing data access patterns rather than relying solely on high-capacity RAM. It challenges the assumption that entire model weights must reside in memory, potentially democratizing access to powerful AI models on consumer devices. The engine uses a small expert cache and bounded parallel pread operations to synchronize SSD data retrieval with GPU computation. It achieves 5–6 tokens per second on an 8GB M2 MacBook Air and includes an OpenAI-compatible local server.

hackernews · gitpusher42 · Jul 29, 15:05 · [Discussion](https://news.ycombinator.com/item?id=49098510)

**Background**: Mixture of Experts (MoE) is an architecture where only a subset of model parameters (experts) are activated for each input, allowing for large models with lower computational costs. KV cache is a standard optimization in transformer models that stores previously computed key and value tensors to avoid redundant calculations during autoregressive generation. Apple's Metal framework provides low-level hardware access to the GPU, enabling high-performance compute tasks on Mac hardware.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.nvidia.com/blog/applying-mixture-of-experts-in-llm-architectures/">Applying Mixture of Experts in LLM Architectures | NVIDIA Technical Blog</a></li>
<li><a href="https://lzwjava.github.io/kv-cache-inference-en">Understanding KV Cache in LLM Inference</a></li>
<li><a href="https://deepwiki.com/skyzh/tiny-llm/7.2-metal-kernels">Metal Kernels | skyzh/tiny- llm | DeepWiki</a></li>

</ul>
</details>

**Discussion**: The community expressed strong interest in the project's efficiency, with users comparing its SSD-streaming approach to standard mmap techniques used in llama.cpp. Developers also discussed potential collaborations for similar projects and provided technical tips for compiling the engine on older macOS versions.

**Tags**: `#on-device-ai`, `#inference-optimization`, `#apple-silicon`, `#llm`, `#memory-management`

---

<a id="item-2"></a>
## [Superlogical](https://www.superlogical.com/) ⭐️ 9.0/10

Mitchell Hashimoto introduces Superlogical, a new company focused on building agentic, terminal-native developer tools that leverage the open-source libghostty library.

hackernews · yan · Jul 29, 15:41 · [Discussion](https://news.ycombinator.com/item?id=49098965)

**Tags**: `#developer-tools`, `#terminal`, `#agentic-workflows`, `#open-source`, `#software-architecture`

---

<a id="item-3"></a>
## [Handbook.md shows that long policy documents do not reliably govern agents](https://arxiv.org/abs/2607.25398) ⭐️ 9.0/10

The research demonstrates that long policy documents are often ineffective at governing AI agents, highlighting significant reliability issues in current long-context model architectures.

hackernews · spIrr · Jul 29, 13:01 · [Discussion](https://news.ycombinator.com/item?id=49096969)

**Tags**: `#LLM`, `#AI Agents`, `#Context Window`, `#Alignment`, `#Machine Learning`

---

<a id="item-4"></a>
## [AI Worming through Word](https://simonwillison.net/2026/Jul/29/ai-worming-through-word/#atom-everything) ⭐️ 9.0/10

Security researcher Håkon Måløy discovered a self-replicating prompt injection vulnerability in Microsoft Word's Copilot feature that allows malicious instructions to propagate across documents.

rss · Simon Willison · Jul 29, 18:43

**Tags**: `#AI Security`, `#Prompt Injection`, `#Microsoft Copilot`, `#Cybersecurity`, `#LLM Vulnerabilities`

---

<a id="item-5"></a>
## [反网络暴力法征求意见稿公布，AI 网暴纳入规制](https://mp.weixin.qq.com/s/PrzKFhbwjgFEGBPADvFD6Q) ⭐️ 9.0/10

China has released a draft 'Anti-Cyberbullying Law' for public comment, which specifically introduces regulatory measures for AI-generated abusive content and mandates stricter platform oversight.

telegram · zaihuapd · Jul 29, 10:59

**Tags**: `#AI Regulation`, `#Cybersecurity`, `#Legal Policy`, `#Digital Ethics`, `#China Tech`

---

<a id="item-6"></a>
## [OpenAI Launches Free Access Program for 100,000 Academic Researchers](https://openai.com/index/chatgpt-for-academic-researchers/) ⭐️ 9.0/10

OpenAI has launched the 'ChatGPT for Academic Researchers' program, which will provide 100,000 researchers with free access to GPT-5.6 models and technical support by 2027. The program includes data privacy protections, ensuring that user data is not used for model training. This initiative significantly lowers the barrier for academic institutions to utilize advanced AI, potentially accelerating breakthroughs in fields like genomics and protein modeling. It represents a major commitment of over $250 million to support global scientific discovery. Participants can invite up to four institutional collaborators, and the program covers the entire research lifecycle, including literature reviews and grant applications. Applicants must be affiliated with degree-granting institutions and submit a formal research plan.

telegram · zaihuapd · Jul 30, 00:17

**Background**: AI for Science refers to the application of machine learning models to solve complex scientific problems, such as predicting protein structures or analyzing large-scale biological data. As AI models become more powerful, they are increasingly used as tools to augment human intelligence in experimental design and data interpretation.

<details><summary>References</summary>
<ul>
<li><a href="https://www.123ai.org/tags/蛋白质建模/">蛋 白 质 建 模 技巧 教程 进阶 新手入门 | 123AI</a></li>

</ul>
</details>

**Tags**: `#OpenAI`, `#AI for Science`, `#Research`, `#GPT-5.6`, `#Academic Computing`

---

<a id="item-7"></a>
## [Top AI Startups Increasingly Prioritize Proprietary Research Over Public Disclosure](https://www.science.org/content/article/ai-s-top-startups-are-barely-publishing-their-research) ⭐️ 8.0/10

Leading AI startups are shifting away from publishing their research findings to maintain competitive advantages. This trend marks a move toward closed-source models to prevent competitors from replicating their work. This shift threatens the culture of open scientific collaboration that has historically driven AI progress. It raises concerns about transparency, reproducibility, and the concentration of power within a few well-funded organizations. Research indicates that while some companies like OpenAI maintain high citation counts, many startups now treat their findings as intellectual property rather than academic contributions. This behavior is often a defensive strategy to avoid being copied by larger, better-resourced competitors.

hackernews · YeGoblynQueenne · Jul 29, 21:25 · [Discussion](https://news.ycombinator.com/item?id=49103285)

**Background**: Historically, AI research was deeply rooted in academia and open-source sharing, allowing the community to build upon shared breakthroughs. As AI has become a multi-billion dollar industry, the incentive structure has changed, leading companies to protect their models, weights, and training data as proprietary assets. This tension between open science and commercial secrecy is a defining challenge in modern technology policy.

<details><summary>References</summary>
<ul>
<li><a href="https://tune.beehiiv.com/p/suited-corps-push-to-close-noble-science/">Suited Corps Push to Close Noble Science</a></li>
<li><a href="https://www.analyticsinsight.net/artificial-intelligence/proprietary-ai-vs-open-source-ai-an-in-depth-analysis">Proprietary AI vs . Open Source AI : An In-Depth Analysis</a></li>
<li><a href="https://www.goodfirms.co/artificial-intelligence-software/blog/open-source-ai-vs-proprietary-ai-ultimate-comparison-guide">Open -Source AI vs Proprietary AI : The Ultimate Comparison Guide</a></li>

</ul>
</details>

**Discussion**: The community is divided, with some developers arguing that secrecy is necessary for survival against larger incumbents, while others criticize the lack of transparency. Some participants noted that the current environment encourages 'blogification' of research, where claims are made without rigorous, peer-reviewed evidence.

**Tags**: `#Artificial Intelligence`, `#Research`, `#Open Science`, `#Tech Policy`, `#Startups`

---

<a id="item-8"></a>
## [Matthew Green on AI's Role in Post-Quantum Cryptanalysis](https://simonwillison.net/2026/Jul/29/matthew-green/#atom-everything) ⭐️ 8.0/10

Cryptographer Matthew Green notes that the current industry-wide transition to post-quantum algorithms, such as HAWK, coincides with the emergence of AI models capable of performing advanced cryptanalysis. He suggests this timing could either expose fundamental weaknesses or significantly strengthen the robustness of new cryptographic standards. This development is critical because the global shift to post-quantum cryptography is a massive, high-stakes security undertaking. If AI can effectively audit these new algorithms, it could accelerate the discovery of vulnerabilities before they are widely deployed. The discussion references Anthropic's Claude Mythos model, which recently identified improvements in attacks against existing cryptographic algorithms, highlighting the dual-use potential of AI in both breaking and verifying security protocols.

rss · Simon Willison · Jul 29, 18:18

**Background**: Post-quantum cryptography (PQC) refers to cryptographic algorithms designed to be secure against attacks by quantum computers, which threaten current standards like RSA. Impagliazzo's Five Worlds is a conceptual framework in computational complexity theory that categorizes the relationship between different types of computational problems and the feasibility of cryptography. HAWK is a specific digital signature scheme currently being evaluated as a candidate for post-quantum security.

<details><summary>References</summary>
<ul>
<li><a href="https://arstechnica.com/security/2026/07/mythos-uncovers-crypto-weaknesses-that-went-unknown-for-years/">Mythos attack on 3rd-round PQC algorithm candidate... - Ars Technica</a></li>
<li><a href="https://blog.computationalcomplexity.org/2004/06/impagliazzos-five-worlds.html">Computational Complexity: Impagliazzo 's Five Worlds</a></li>
<li><a href="https://www.ai-jarvis.eu/anthropics-mythos-found-flaws-aes-and-hawk-cryptography-100000-attack">Anthropic's Mythos Found Flaws in AES and HAWK Cryptography ...</a></li>

</ul>
</details>

**Tags**: `#cryptography`, `#post-quantum`, `#AI`, `#cybersecurity`, `#cryptanalysis`

---

<a id="item-9"></a>
## [The Rise of Modular 'LEGO-like' Data Center Construction](https://newsletter.semianalysis.com/p/the-wild-wild-west-of-lego-datacenters) ⭐️ 8.0/10

The industry is increasingly adopting modular, prefabricated construction methods to build data centers, treating infrastructure components like LEGO blocks to accelerate deployment. This shift is a direct response to severe labor shortages and the urgent need for faster scaling in the AI era. Modular construction allows companies to bypass traditional, slow-moving construction site constraints, significantly reducing time-to-market for critical compute capacity. This approach is essential for meeting the massive infrastructure demands of modern AI workloads. Prefabricated data centers, often referred to as containerized or integrated modular solutions, are engineered off-site to ensure precision and quality control. These systems allow for standardized, scalable deployments that can be rapidly integrated into existing power and cooling grids.

rss · Semianalysis · Jul 29, 22:09

**Background**: Traditional data center construction is a labor-intensive, time-consuming process involving complex on-site assembly of concrete, steel, and electrical systems. Modular data centers simplify this by using factory-built modules that arrive on-site ready for connection. This shift helps address the industry's struggle to find skilled labor while meeting the rapid growth in global data demand.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Modular_data_center">Modular data center - Wikipedia</a></li>
<li><a href="https://www.se.com/ww/en/work/solutions/data-centers-and-networks/modular-data-center/">EcoStruxure™ Modular Data Center | Schneider Electric</a></li>
<li><a href="https://www.vertiv.com/en-asia/solutions/prefabricated-data-center/">Prefabricated Modular Data Center</a></li>

</ul>
</details>

**Tags**: `#Data Centers`, `#Infrastructure`, `#Modular Construction`, `#Supply Chain`, `#Industry Analysis`

---

<a id="item-10"></a>
## [Moonshot AI Seeks $2 Billion Funding at $30 Billion Valuation](https://t.me/zaihuapd/42845) ⭐️ 8.0/10

Moonshot AI is initiating its third funding round in six months, aiming to raise up to $2 billion at a $30 billion valuation. The company is also reportedly dismantling its offshore corporate structure to prepare for a potential IPO in Hong Kong. This rapid valuation growth reflects the intense capital competition in China's LLM sector, driven by the strong commercial performance of the Kimi chatbot and the company's expansion into agentic AI tools. Moonshot AI's annual recurring revenue surpassed $200 million in April, bolstered by the success of its Kimi chatbot and the launch of its new AI agent tool, Kimi Work.

telegram · zaihuapd · Jul 29, 10:12

**Background**: Moonshot AI is a leading Chinese AI startup known for its Kimi chatbot, which utilizes long-context window technology. Dismantling offshore structures, often referred to as 'Red Chip' or VIE structures, is a strategic move for Chinese tech companies to comply with domestic regulatory requirements before pursuing public listings.

<details><summary>References</summary>
<ul>
<li><a href="https://www.moonshot.ai/">Welcome to Moonshot AI . Our mission is to seek the optimal...</a></li>
<li><a href="https://www.kimi.com/products/kimi-work">Kimi Work : Next-Gen Desktop AI Agent for Knowledge Workers</a></li>
<li><a href="https://accesspath.com/policy/chinese-ai-firms-begin-dismant-moqfpfqqqx2l">Meta收购Manus受阻，中国AI企业加速 拆 除 离岸 架 构 | 前途科技</a></li>

</ul>
</details>

**Discussion**: The community is closely watching the company's rapid valuation surge, with many debating whether the revenue growth can justify such high capital requirements in the current AI market.

**Tags**: `#Moonshot AI`, `#AI Funding`, `#LLM`, `#Kimi`, `#Startup Valuation`

---

<a id="item-11"></a>
## [UK Proposes Relaxing Apple and Google App Payment Restrictions](https://t.me/zaihuapd/42855) ⭐️ 8.0/10

The UK's Competition and Markets Authority (CMA) has proposed allowing app developers to direct users to payment options outside of Apple and Google's app stores. Additionally, the regulator is considering requiring Apple to open its NFC technology to third-party developers for mobile payments. This move aims to lower transaction fees and foster competition within the mobile ecosystem, potentially reducing the dominance of major tech platforms. It directly impacts the revenue models of Apple and Google while offering developers more flexibility and lower costs. The proposal mandates that if Apple or Google charge fees for these alternative payment paths, such fees must be fair, reasonable, and lower than current commission rates. The savings are expected to benefit consumers or be reinvested into innovation.

telegram · zaihuapd · Jul 30, 02:10

**Background**: The CMA is a non-ministerial government department in the UK responsible for preventing anti-competitive practices. This proposal is part of a broader regulatory effort under the UK's new digital markets regime, following findings that Apple and Google hold strategic market positions in the mobile sector. Similar to the EU's Digital Markets Act (DMA), these regulations aim to curb the market power of digital giants.

<details><summary>References</summary>
<ul>
<li><a href="https://m.jiemian.com/article/14672490_microcontent.html">m.jiemian.com/article/14672490_microcontent.html</a></li>
<li><a href="https://yandex-ads.com/yandexzixun/171.html">中和Google的不公平数据优势_Yandex广告网</a></li>

</ul>
</details>

**Discussion**: The community generally views this as a positive step toward breaking the 'walled garden' approach of major tech companies, though some express skepticism about whether the tech giants will comply without significant legal pressure.

**Tags**: `#Regulation`, `#Apple`, `#Google`, `#Mobile Ecosystem`, `#Fintech`

---