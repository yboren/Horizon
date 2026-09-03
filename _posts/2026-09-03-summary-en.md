---
layout: default
title: "Horizon Summary: 2026-09-03 (EN)"
date: 2026-09-03
lang: en
---

> From 36 items, 16 important content pieces were selected

---

1. [Meta Releases Muse Spark 1.3 AI Model](#item-1) ⭐️ 9.0/10
2. [Google Releases Gemini 3.8 Flash and Flash Cyber Models](#item-2) ⭐️ 9.0/10
3. [Three sites generated over 200,000 AI-written pages to manipulate search results](#item-3) ⭐️ 9.0/10
4. [Most Open-Source AI Detectors Fail to Maintain 0.5% False-Positive Rate](#item-4) ⭐️ 9.0/10
5. [Alibaba Releases Qwen3.8-Max-0902, Topping CodeArena Leaderboard](#item-5) ⭐️ 9.0/10
6. [NVIDIA Reportedly in Talks to Acquire Hugging Face for Over $13 Billion](#item-6) ⭐️ 9.0/10
7. [FBI Probes Nexus Dark Web Service Selling 153 Million Driver's Licenses](#item-7) ⭐️ 9.0/10
8. [OpenAI Announces Astra, the First AI Model Reaching Critical Cybersecurity Thresholds](#item-8) ⭐️ 9.0/10
9. [Google avoids a forced breakup of its ad tech business](#item-9) ⭐️ 8.0/10
10. [Mistral AI Data Privacy and Opt-Out Policy Concerns](#item-10) ⭐️ 8.0/10
11. [Paint.NET Developer Uses LLM to Enable Wine Support](#item-11) ⭐️ 8.0/10
12. [Researcher Releases Massive Dataset of 5.94 Billion TikTok Videos](#item-12) ⭐️ 8.0/10
13. [Deepity: A C++ Library Showing Predictive Coding Networks Can Match Backprop](#item-13) ⭐️ 8.0/10
14. [Moonshot AI Negotiates Revenue Sharing with Major Cloud Giants for Kimi K3](#item-14) ⭐️ 8.0/10
15. [xAI Releases Grok 4.6 with Enhanced Long-Running Agentic Capabilities](#item-15) ⭐️ 8.0/10
16. [Moonshot AI Files for Confidential Hong Kong IPO at $50 Billion Valuation](#item-16) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Meta Releases Muse Spark 1.3 AI Model](https://developer.meta.com/ai/models/muse-spark/) ⭐️ 9.0/10

Meta has launched Muse Spark 1.3, an updated AI model that delivers significant improvements in generation quality and benchmark performance compared to its predecessor. It is positioned as a highly competitive and cost-effective solution for various generative AI tasks. This release marks a milestone in the availability of high-performance, budget-friendly AI models, intensifying competition in the industry and potentially driving down costs for developers. It demonstrates that smaller, optimized models can achieve top-tier performance on complex benchmarks like DeepSWE. Muse Spark 1.3 achieved a record-breaking score of 75.4 on the DeepSWE benchmark, surpassing previous leaders like Gemini 3.8 Flash. The model is noted for its efficiency and transparent pricing structure regarding data usage for training.

hackernews · bvaldivielso · Sep 2, 19:35 · [Discussion](https://news.ycombinator.com/item?id=49541256)

**Background**: The Muse series is part of Meta's broader initiative to develop efficient, agentic AI models that can handle complex workflows, including visual and audio inspection. These models often utilize advanced architectures and distillation techniques to maintain high performance while remaining cost-effective for developers. The underlying technology builds upon concepts like Masked Generative Image Transformers, which improve synthesis efficiency compared to traditional sequential decoding.

<details><summary>References</summary>
<ul>
<li><a href="https://ai.meta.com/blog/introducing-muse-spark-meta-model-api/">Introducing Muse Spark 1.1</a></li>

</ul>
</details>

**Discussion**: The community has responded positively to Muse Spark 1.3, praising its impressive benchmark scores and cost efficiency. Users appreciate the model's ability to follow instructions without being overly opinionated, though some discussions highlight ongoing concerns regarding data privacy and the practice of using user data for model training.

**Tags**: `#AI`, `#LLM`, `#Meta`, `#Machine Learning`, `#Generative AI`

---

<a id="item-2"></a>
## [Google Releases Gemini 3.8 Flash and Flash Cyber Models](https://blog.google/innovation-and-ai/models-and-research/gemini-models/3-8-flash-and-3-8-flash-cyber/) ⭐️ 9.0/10

Google has launched Gemini 3.8 Flash and Flash Cyber, the latest iterations in its model family, which offer significant improvements in reasoning, coding performance, and agentic workflows. These models continue to support customizable effort levels, allowing users to balance quality, cost, and latency. These models represent a major advancement by providing top-tier intelligence and coding capabilities at the high efficiency and low latency typical of the 'Flash' series. This makes them highly competitive for real-time applications and complex agentic tasks where speed is critical. Gemini 3.8 Flash demonstrates performance comparable to larger models like Opus 5 on various benchmarks while maintaining cost-effectiveness. The models retain native multimodal support, including the ability to process audio and video inputs directly.

hackernews · bratao · Sep 2, 15:12 · [Discussion](https://news.ycombinator.com/item?id=49537553)

**Background**: The Gemini Flash series is designed by Google DeepMind to provide a balance between high-performance reasoning and low-latency inference. These models are specifically optimized for agentic workflows, where an AI must perform multi-step tasks, and for developers who require cost-effective, high-throughput solutions for production applications.

<details><summary>References</summary>
<ul>
<li><a href="https://deepmind.google/models/model-cards/gemini-3-8-flash/">Gemini 3.8 Flash - Model Card — Google DeepMind</a></li>
<li><a href="https://ai.google.dev/gemini-api/docs/models">Models - Gemini API | Google AI for Developers</a></li>

</ul>
</details>

**Discussion**: The community is impressed by the model's coding speed and performance, with users noting its effectiveness in HTML/JS generation and real-world data tasks. However, some users observed potential regressions in 'low' effort modes compared to previous versions.

**Tags**: `#AI`, `#LLM`, `#Google Gemini`, `#Machine Learning`, `#Model Benchmarks`

---

<a id="item-3"></a>
## [Three sites generated over 200,000 AI-written pages to manipulate search results](https://trellner.com/reports/manufactured-sources-behind-ai-recommendations/) ⭐️ 9.0/10

An investigation found that three domains created over 215,000 low-quality, AI-generated 'best software' pages specifically designed to influence AI search engines like Perplexity. These sites leverage SEO tactics to ensure they are cited as authoritative sources in AI-generated responses. This highlights a critical vulnerability in RAG systems and AI search engines, where synthetic content farms can create feedback loops that degrade the reliability of AI outputs. It exposes how easily AI models can be manipulated by mass-produced, low-quality web content. The identified domains, including wifitalents.com and gitnux.org, saw thousands of visits before their traffic began to decline. These sites rely on automated content generation to exploit the probabilistic nature of LLMs, which often prioritize frequently cited information regardless of its quality.

hackernews · jakobgreenfeld · Sep 2, 13:59 · [Discussion](https://news.ycombinator.com/item?id=49536375)

**Background**: Retrieval-Augmented Generation (RAG) is a technique where AI models fetch real-time information from the web to provide more accurate answers. However, if the web index is flooded with 'SEO spam' or synthetic content, the model may inadvertently treat unreliable data as facts. This phenomenon is part of a broader concern regarding 'model collapse,' where AI systems trained on AI-generated data lose accuracy over time.

<details><summary>References</summary>
<ul>
<li><a href="https://kevinlee.net/are-llm-based-chat-bots-vulnerable-to-seo-spam-given-the-probabilistic-nature-of-their-responses-if-a-particular-element-of-information-is-corroborated-many-times-across-the-crawlable-web-does-it-inf/">Are LLM based chat bots vulnerable to SEO spam given the ...</a></li>
<li><a href="https://jingrey.com/seo/llm-mention-manipulation/">LLM Mention Manipulation: What It Is, How It Works, and the ...</a></li>

</ul>
</details>

**Discussion**: Users expressed frustration, noting that LLMs often favor their own generated content and struggle with source skepticism. Many commenters shared personal experiences of encountering 'hallucinated' recommendations for non-existent places or products, confirming that AI search quality is currently suffering due to these manipulative tactics.

**Tags**: `#AI`, `#Search Engines`, `#SEO`, `#Data Integrity`, `#LLM`

---

<a id="item-4"></a>
## [Most Open-Source AI Detectors Fail to Maintain 0.5% False-Positive Rate](https://www.reddit.com/r/MachineLearning/comments/1w58erw/most_opensource_ai_detectors_cant_hold_a_05/) ⭐️ 9.0/10

A rigorous evaluation of six notable open-source AI detectors found that most fail to maintain a 0.5% false-positive rate (FPR) and struggle significantly against paraphrased text and non-native English writing. The study highlights that even popular models like MAGE and the OpenAI RoBERTa detector perform poorly under standardized testing conditions. This study exposes critical reliability flaws in current AI detection tools, which are frequently used in academic and professional settings. The findings suggest that these tools may unfairly penalize non-native speakers and are easily bypassed by paraphrasing, undermining their utility as integrity verification systems. The evaluation used a standardized protocol across 6,930 human documents and various AI-generated texts, revealing that four out of six models could not reach the 0.5% FPR threshold. Notably, all tested models showed a bias by flagging non-native essays at a higher rate than native ones.

reddit · r/MachineLearning · /u/grumpyp2 · Sep 2, 12:04

**Background**: AI detectors are machine learning models designed to classify text as human-written or AI-generated. A false-positive occurs when human-written text is incorrectly flagged as AI-generated, a major concern for academic integrity. ROC-AUC is a common metric used to evaluate the performance of these binary classifiers, where a higher score indicates better discrimination between classes.

<details><summary>References</summary>
<ul>
<li><a href="https://gptzero.me/news/ai-accuracy-benchmarking/">How AI Detection Benchmarking Works at GPTZero (2025)</a></li>
<li><a href="https://developers.google.com/machine-learning/crash-course/classification/roc-and-auc">Classification: ROC and AUC | Machine Learning | Google for Developers</a></li>
<li><a href="https://huggingface.co/docs/transformers/model_doc/roberta">RoBERTa · Hugging Face</a></li>

</ul>
</details>

**Discussion**: The community discussion highlights concerns regarding the inherent bias of these models against non-native English speakers and the ongoing 'arms race' between AI generators and detectors. Many users expressed skepticism about the feasibility of reliable AI detection in the long term.

**Tags**: `#AI Detection`, `#Machine Learning`, `#Model Evaluation`, `#NLP`, `#AI Ethics`

---

<a id="item-5"></a>
## [Alibaba Releases Qwen3.8-Max-0902, Topping CodeArena Leaderboard](https://mp.weixin.qq.com/s/BfKRXMAR5ykD58LDkBftLg) ⭐️ 9.0/10

Alibaba has launched Qwen3.8-Max-0902, a new model version that achieved a top score of 1691 on the CodeArena programming leaderboard. It features a 2.4 trillion parameter MoE architecture and supports a 1 million token context window. This release marks a significant shift in the LLM landscape by offering state-of-the-art coding performance at a price point significantly lower than its primary competitors. It makes advanced AI-assisted programming more accessible for enterprise and individual developers. The model is priced at $2 per million input tokens and $6 per million output tokens, significantly undercutting the $12 to $20 average pricing of its rivals. It is currently available via the Qwen AI platform and integrated into Qwen's office and coding tools.

telegram · zaihuapd · Sep 2, 06:05

**Background**: CodeArena is a competitive platform used to evaluate the coding and problem-solving capabilities of large language models. The model utilizes a Mixture-of-Experts (MoE) architecture, which improves efficiency by activating only a subset of its total parameters for each specific task.

<details><summary>References</summary>
<ul>
<li><a href="https://zenmux.ai/qwen/qwen3.8-max-0902">qwen/qwen3.8-max-0902 | ZenMux AI Model Routing</a></li>
<li><a href="https://www.qwencloud.com/models/qwen3.8-max-0902">Qwen3.8-Max-0902 - QwenCloud</a></li>
<li><a href="https://aihubmix.com/model/qwen3.8-max-2026-09-02">Qwen3.8 Max (coding) API - $1.69/M In, $5.07/M Out | AIHubMix</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#Alibaba`, `#CodeArena`, `#AI Models`, `#Programming`

---

<a id="item-6"></a>
## [NVIDIA Reportedly in Talks to Acquire Hugging Face for Over $13 Billion](https://t.me/zaihuapd/43557) ⭐️ 9.0/10

NVIDIA is reportedly in negotiations to acquire the open-source AI platform Hugging Face, with a potential valuation exceeding $13 billion. While NVIDIA is already an existing investor, no final agreement has been reached and the deal could still fall through. This acquisition would significantly consolidate NVIDIA's control over the AI ecosystem by integrating the industry's primary hub for open-source models and machine learning collaboration. It signals a strategic move to dominate both the hardware infrastructure and the software platforms that power modern AI development. Hugging Face was previously valued at $4.5 billion during its 2023 funding round, in which NVIDIA participated. Reports also suggest that Microsoft had previously expressed interest in the company, though those discussions have reportedly ceased.

telegram · zaihuapd · Sep 2, 06:50

**Background**: Hugging Face is a prominent platform that hosts a vast repository of open-source machine learning models, datasets, and demo applications, serving as a central hub for the global AI research community. It operates on a freemium business model, offering free access to open-source tools while monetizing through enterprise-grade security, private hubs, and specialized AI training services.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Hugging_Face">Hugging Face - Wikipedia</a></li>
<li><a href="https://huggingface.co/">Hugging Face – The AI community building the future.</a></li>
<li><a href="https://productmint.com/hugging-face-business-model/">Hugging Face Business Model : How It Makes Money (2025)</a></li>

</ul>
</details>

**Tags**: `#NVIDIA`, `#Hugging Face`, `#AI Infrastructure`, `#Mergers and Acquisitions`, `#Open Source AI`

---

<a id="item-7"></a>
## [FBI Probes Nexus Dark Web Service Selling 153 Million Driver's Licenses](https://krebsonsecurity.com/2026/09/fbi-probes-service-selling-153m-drivers-licenses/) ⭐️ 9.0/10

The FBI is investigating a dark web platform called Nexus that is currently selling 153 million digital scans of driver's licenses from the U.S. and Canada. The platform claims to possess this massive database of sensitive identity documents. This breach poses a severe risk of widespread identity theft and systemic fraud, as the stolen data includes names, addresses, and birth dates. It highlights the persistent vulnerability of personal data held by third-party institutions like insurance companies and car dealerships. Security researcher Brian Krebs suggests the data likely originated from historical breaches at various automotive and insurance firms. Official sources have not yet confirmed the exact source of the leak or the full extent of the impact.

telegram · zaihuapd · Sep 2, 09:31

**Background**: The dark web is a part of the internet that is not indexed by search engines and requires specialized software like Tor to access. It is frequently used by cybercriminals to trade stolen personal information, such as social security numbers and identity documents, for profit. Brian Krebs is a prominent investigative journalist known for his in-depth reporting on cybercrime and data breaches.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/KrebsOnSecurity">KrebsOnSecurity</a></li>

</ul>
</details>

**Tags**: `#Cybersecurity`, `#Data Breach`, `#Identity Theft`, `#FBI`, `#Privacy`

---

<a id="item-8"></a>
## [OpenAI Announces Astra, the First AI Model Reaching Critical Cybersecurity Thresholds](https://t.me/zaihuapd/43571) ⭐️ 9.0/10

OpenAI is preparing to release Astra, a new model that has been officially classified as reaching 'Critical' cybersecurity risk levels. It demonstrates the ability to autonomously identify and exploit zero-day vulnerabilities in hardened systems without human intervention. This development marks a significant shift in AI safety, as Astra is the first model to meet OpenAI's 'Critical' cybersecurity threshold under its Preparedness Framework. Its ability to perform end-to-end cyberattacks necessitates stricter safety protocols and controlled release strategies. Astra achieved a perfect score on the ExploitBench benchmark and successfully identified two zero-day vulnerabilities during internal testing. To mitigate risks, OpenAI has improved its refusal rate for malicious cyber requests to 91.5% and is limiting initial access to a select group of testers.

telegram · zaihuapd · Sep 2, 16:30

**Background**: OpenAI's Preparedness Framework defines 'Critical' cybersecurity risk as the capability to identify and develop functional exploits for zero-day vulnerabilities in hardened systems. ExploitBench is a specialized benchmark designed to measure how effectively AI agents can navigate the stages of a cyberattack, from vulnerability discovery to code execution. Zero-day vulnerabilities are previously unknown security flaws that hackers can exploit before a patch is available.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/index/responding-next-frontier-critical-cyber-capabilities/">Responding to the next frontier of critical cyber capabilities</a></li>
<li><a href="https://exploitbench.ai/">ExploitBench</a></li>
<li><a href="https://www.explainx.ai/blog/openai-astra-cybersecurity-critical-preparedness-framework-2026">OpenAI Astra: Critical Cyber Tier Confirmed (Sept 2026 ...</a></li>

</ul>
</details>

**Tags**: `#OpenAI`, `#Cybersecurity`, `#AI Safety`, `#Zero-day`, `#Astra`

---

<a id="item-9"></a>
## [Google avoids a forced breakup of its ad tech business](https://www.nytimes.com/2026/09/02/technology/google-ad-tech-remedies.html) ⭐️ 8.0/10

A U.S. federal judge has rejected the Department of Justice's request to force Google to divest its advertising technology business, opting instead for behavioral remedies despite finding the company guilty of monopolistic practices. This ruling sets a significant precedent for antitrust enforcement in the tech industry, highlighting the judiciary's preference for behavioral regulation over structural divestiture when addressing Big Tech dominance. While Google avoids a breakup, it is still required to implement specific behavioral changes to its ad tech operations to address the court's findings of illegal anti-competitive behavior.

hackernews · donohoe · Sep 2, 14:46 · [Discussion](https://news.ycombinator.com/item?id=49537131)

**Background**: Google's ad tech stack is a complex ecosystem that facilitates the buying and selling of digital advertising space between publishers and advertisers. The Department of Justice had argued that Google's control over both sides of this marketplace allowed it to unfairly favor its own tools and suppress competition. This case is part of a broader series of antitrust actions aimed at curbing the market power of major technology companies.

<details><summary>References</summary>
<ul>
<li><a href="https://www.reuters.com/legal/litigation/google-defeats-us-bid-force-ad-tech-sale-2026-09-02/">Google escapes ad tech breakup in third Big Tech antitrust ...</a></li>
<li><a href="https://explainx.ai/blog/google-ad-tech-antitrust-ruling-no-breakup-2026">Google Ad Tech Ruling: No Breakup, What Changes (Sept 2026 ...</a></li>
<li><a href="https://hackernoon.com/us-v-google-how-ad-tech-tools-work">US v. Google : How Ad Tech Tools Work | HackerNoon</a></li>

</ul>
</details>

**Discussion**: The community expressed skepticism regarding the effectiveness of behavioral remedies, with some users suggesting that monopolies should be taxed progressively or that divestiture should be as easy to enforce as mergers. Others questioned the distinction between Google's overall ad revenue and its specific 'ad tech' business segment.

**Tags**: `#antitrust`, `#google`, `#adtech`, `#regulation`, `#legal`

---

<a id="item-10"></a>
## [Mistral AI Data Privacy and Opt-Out Policy Concerns](https://help.mistral.ai/en/articles/455207-can-i-opt-out-of-my-input-or-output-data-being-used-for-training) ⭐️ 8.0/10

Users have expressed frustration over Mistral AI's evolving data privacy policies, specifically regarding how input and output data are utilized for model training. While the company maintains that users retain the right to opt out, community members report that default settings and dashboard controls have become less transparent over time. This situation highlights a growing industry trend where enterprise users struggle to maintain data sovereignty amidst changing terms of service. It underscores the widespread anxiety among developers regarding the reliability of AI vendors' privacy promises and the potential for 'rug-pulls' in data usage policies. Mistral AI's official documentation states that while user content may be included in training programs, users can opt out at any time. However, users have reported that these opt-out settings are not always intuitive or consistently applied across different subscription tiers.

hackernews · teekert · Sep 2, 12:30 · [Discussion](https://news.ycombinator.com/item?id=49535284)

**Background**: Data sovereignty in AI refers to an organization's ability to control how its proprietary data is stored, processed, and used for model improvement. As LLMs become integrated into enterprise workflows, companies are increasingly concerned that their sensitive inputs might inadvertently train public models, leading to potential data leaks or loss of competitive advantage.

<details><summary>References</summary>
<ul>
<li><a href="https://assist-software.net/business-insights/data-sovereignty-and-enterprise-ai-why-control-over-your-data-now-strategic">Data sovereignty and enterprise AI : why control... | ASSIST Software</a></li>
<li><a href="https://www.fileorbis.com/ai-sovereignty-what-it-means-for-enterprise-data-and-models/">AI Sovereignty : Enterprise Data and Model Control - FileOrbis</a></li>

</ul>
</details>

**Discussion**: The community is divided; some users feel that AI companies are inherently untrustworthy and will train on data regardless of consent, while others argue that the criticism of Mistral is exaggerated and that the company provides clear, albeit complex, opt-out mechanisms.

**Tags**: `#AI Privacy`, `#Data Sovereignty`, `#Mistral AI`, `#Enterprise AI`, `#LLM Training`

---

<a id="item-11"></a>
## [Paint.NET Developer Uses LLM to Enable Wine Support](https://simonwillison.net/2026/Sep/2/rick-brewster/) ⭐️ 8.0/10

Paint.NET developer Rick Brewster has successfully enabled Wine support by using Claude to generate a massive, from-scratch managed implementation of the Direct2D API. This new component, contained in a specific DLL, allows the application to run on Linux by bypassing the limitations of existing Wine compatibility layers. This achievement demonstrates the practical power of LLMs in solving complex, long-standing software compatibility issues that were previously considered too labor-intensive to address. It highlights a new paradigm where developers can use AI to bridge gaps in legacy software ecosystems. The generated codebase consists of approximately 180,000 lines of code, which the developer describes as 'vibe coded' and requiring significant oversight for resource management and architectural design. The implementation is triggered specifically by the /wine command-line argument.

rss · Simon Willison · Sep 2, 05:50

**Background**: Direct2D is a hardware-accelerated 2D graphics API developed by Microsoft, which is notoriously difficult to fully replicate in Wine, the compatibility layer for running Windows applications on Linux. Clean-room reverse engineering is a technique used to recreate a system's functionality without infringing on intellectual property by ensuring the new implementation is developed independently of the original proprietary code.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Clean-room_reverse_engineering">Clean-room reverse engineering</a></li>
<li><a href="https://learn.microsoft.com/ru-ru/windows/win32/learnwin32/overview-of-the-windows-graphics-architecture">Описывает API графики C++/COM в Windows. | Microsoft Learn</a></li>

</ul>
</details>

**Discussion**: The community is highly impressed by the scale of the achievement, noting the irony of using AI to solve a problem that human developers struggled with for years. Many are discussing the risks of 'vibe coding' and the necessity of human oversight when integrating AI-generated code into critical software.

**Tags**: `#Paint.NET`, `#Wine`, `#LLM`, `#Reverse Engineering`, `#Direct2D`

---

<a id="item-12"></a>
## [Researcher Releases Massive Dataset of 5.94 Billion TikTok Videos](https://www.reddit.com/r/MachineLearning/comments/1w5h9se/i_scraped_594_billion_tiktok_videos_and_323/) ⭐️ 8.0/10

A researcher has published a dataset containing 5.94 billion TikTok videos and 3.23 billion profiles on Hugging Face. The data was collected over three weeks using reverse-engineered API endpoints from the TikTok mobile application. This release provides an unprecedented volume of multimodal data for training large-scale AI models. It significantly lowers the barrier for researchers to access social media data for academic and machine learning purposes. The dataset includes videos, comments, hashtags, and sounds, though the author charges a fee for the full scraping source code. While the data is publicly accessible via API endpoints, the collection method likely violates TikTok's Terms of Service.

reddit · r/MachineLearning · /u/DataShack · Sep 2, 17:38

**Background**: Reverse engineering an API involves analyzing network traffic and application behavior to replicate undocumented endpoints without official documentation. Web scraping at this scale often faces legal and ethical scrutiny regarding data privacy and platform terms of service. Such datasets are highly sought after for training multimodal AI models that require massive amounts of video and text data.

<details><summary>References</summary>
<ul>
<li><a href="https://apidog.com/blog/reverse-engineering-apis/">Reverse Engineering APIs: Guide, Tools & Techniques</a></li>
<li><a href="https://blog.apify.com/reverse-engineer-apis/">How to reverse engineer website APIs - blog.apify.com</a></li>
<li><a href="https://forage.ai/blog/legal-and-ethical-issues-in-web-scraping-what-you-need-to-know/">Is Web Scraping Legal? A Compliance Guide (2026) - ForageAI</a></li>

</ul>
</details>

**Discussion**: The community is divided, with some praising the utility of the massive dataset for research, while others raise significant concerns about the legality of the scraping method and the ethics of paywalling the source code.

**Tags**: `#datasets`, `#machine-learning`, `#web-scraping`, `#data-engineering`, `#tiktok`

---

<a id="item-13"></a>
## [Deepity: A C++ Library Showing Predictive Coding Networks Can Match Backprop](https://www.reddit.com/r/MachineLearning/comments/1w5fuhm/deepity_a_c_library_showing_predictive_coding/) ⭐️ 8.0/10

The developer released Deepity, a high-performance C++ library that implements accelerated Predictive Coding Networks (PCNs) using Direct Kolen-Pollack feedback alignment. It achieves 97.73% accuracy on MNIST in 60 seconds, demonstrating performance parity with standard backpropagation. This project is significant because it optimizes biologically plausible local learning algorithms to be competitive with backpropagation in speed and accuracy. It offers a promising path toward more efficient neural network training that avoids the global weight transport requirements of traditional backprop. Deepity utilizes algorithmic caching to bypass redundant forward projections during the inference settling phase. The developer plans to port the kernels to CUDA to further scale the architecture for continual learning tasks.

reddit · r/MachineLearning · /u/Important-Home4431 · Sep 2, 16:49

**Background**: Predictive Coding Networks (PCNs) are a biologically inspired framework for hierarchical computation that serves as an alternative to backpropagation. Unlike backpropagation, which requires a global backward pass to update weights, PCNs use local learning rules that are more consistent with how the brain processes information. Direct Kolen-Pollack feedback alignment is a technique used to approximate error gradients without the need for symmetric weight transport.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2506.06332">Introduction to Predictive Coding Networks for Machine Learning</a></li>
<li><a href="https://arxiv.org/html/2602.15571">Accelerated Predictive Coding Networks via Direct Kolen – Pollack ...</a></li>
<li><a href="https://www.geeksforgeeks.org/machine-learning/backpropagation-in-neural-network/">Backpropagation in Neural Network - GeeksforGeeks</a></li>

</ul>
</details>

**Discussion**: The community has shown strong interest in the project, focusing on the technical merits of local learning, the efficiency of the C++ implementation, and the potential for these networks to solve challenges in continual learning where backpropagation often struggles.

**Tags**: `#Machine Learning`, `#Predictive Coding`, `#C++`, `#Optimization`, `#Neural Networks`

---

<a id="item-14"></a>
## [Moonshot AI Negotiates Revenue Sharing with Major Cloud Giants for Kimi K3](https://www.jiemian.com/article/15040119.html) ⭐️ 8.0/10

Moonshot AI is reportedly in early-stage negotiations with Microsoft, Amazon, and Google to secure a revenue-sharing agreement of up to 30% for its Kimi K3 model. This would mark the first major revenue-sharing deal between a Chinese AI firm and U.S. cloud providers. This negotiation signals a potential shift in business models for Chinese AI startups, moving toward international collaboration and revenue sharing. It highlights the global competitiveness of Chinese LLMs and the increasing integration of AI services within global cloud ecosystems. Kimi K3, released in July 2026, is a 2.8 trillion parameter model and the world's first open-source 3T-level model. As of mid-June, the model had already achieved an annual recurring revenue (ARR) exceeding $300 million.

telegram · zaihuapd · Sep 2, 07:36

**Background**: Moonshot AI is a prominent Chinese AI startup known for its Kimi chatbot and large language models. Revenue sharing in the AI industry typically involves cloud providers hosting models and taking a cut of the usage fees, while developers provide the underlying technology to attract enterprise customers.

**Tags**: `#Moonshot AI`, `#AI Business Models`, `#Cloud Computing`, `#LLM`, `#Tech Industry`

---

<a id="item-15"></a>
## [xAI Releases Grok 4.6 with Enhanced Long-Running Agentic Capabilities](https://t.me/zaihuapd/43559) ⭐️ 8.0/10

xAI released Grok 4.6 on August 12, 2026, which builds upon the previous version to improve performance in long-running agentic workflows and visual tasks. The model now achieves parity with the GPT-5.6 Sol model on the Artificial Analysis Intelligence Index. This update signifies xAI's commitment to competitive, high-performance AI agents capable of handling complex, multi-step tasks over extended periods. It positions Grok as a top-tier contender for enterprise and developer workflows requiring autonomous decision-making. Grok 4.6 is available via Cursor, Grok Build, and API, priced at $2 per million input tokens and $6 per million output tokens, with a faster version available at double the cost. It leverages a composite benchmark of nine evaluations to measure its holistic intelligence.

telegram · zaihuapd · Sep 2, 08:10

**Background**: Agentic workflows are AI-driven processes where autonomous agents make decisions and coordinate tasks with minimal human intervention. The Artificial Analysis Intelligence Index is a composite benchmark that aggregates various metrics to provide a holistic measure of an AI model's capabilities across coding, reasoning, and science.

<details><summary>References</summary>
<ul>
<li><a href="https://artificialanalysis.ai/evaluations/artificial-analysis-intelligence-index">Artificial Analysis Intelligence Index v4.1.1</a></li>
<li><a href="https://www.ibm.com/think/topics/agentic-workflows">What are agentic workflows? - IBM</a></li>

</ul>
</details>

**Tags**: `#xAI`, `#Grok`, `#LLM`, `#AI Agents`, `#Artificial Intelligence`

---

<a id="item-16"></a>
## [Moonshot AI Files for Confidential Hong Kong IPO at $50 Billion Valuation](https://x.com/latepostnews/status/2095142540660093315) ⭐️ 8.0/10

Moonshot AI, the developer of the Kimi chatbot, has reportedly filed for a confidential IPO with the Hong Kong Stock Exchange and is seeking a new funding round at a $50 billion pre-money valuation. This move signals a rapid acceleration in the valuation of China's leading AI startups and highlights a significant shift toward public markets for the domestic LLM sector. Moonshot AI has maintained a rapid iteration cycle with its Kimi models, and its valuation has surged approximately eightfold in just six months, reaching a post-money valuation of $35 billion by July.

telegram · zaihuapd · Sep 3, 03:15

**Background**: Moonshot AI is one of China's most prominent artificial intelligence startups, known for its Kimi large language model. A confidential IPO filing allows companies to begin the listing process with the Hong Kong Stock Exchange while keeping financial details private until a later stage.

<details><summary>References</summary>
<ul>
<li><a href="https://www.legco.gov.hk/yr12-13/chinese/panels/fa/papers/facb1-362-1-c.pdf">Microsoft Word - facb1-362-1-c.docx</a></li>

</ul>
</details>

**Tags**: `#Moonshot AI`, `#Kimi`, `#IPO`, `#Artificial Intelligence`, `#China Tech`

---