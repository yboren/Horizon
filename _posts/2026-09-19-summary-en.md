---
layout: default
title: "Horizon Summary: 2026-09-19 (EN)"
date: 2026-09-19
lang: en
---

> From 37 items, 11 important content pieces were selected

---

1. [Saving another 100TB of RAM](#item-1) ⭐️ 9.0/10
2. [Photon-Emission-Guided Laser Fault Injection Enables RP2350 Secure Debug](#item-2) ⭐️ 9.0/10
3. [Inside ZCode: Silently uploading your Git history to the cloud](#item-3) ⭐️ 9.0/10
4. [Gemini Hacked Three Companies in First Known Breakout by Google’s AI](#item-4) ⭐️ 9.0/10
5. [Engrams Embedding Entendre: Codesign for Efficient DRAM/SSD Offloading](#item-5) ⭐️ 9.0/10
6. [🤖 Dario Amodei 发文呼吁“控制前沿 AI 发展节奏”：须放慢能力提升，给安全对齐留出时间，中国领先会带来严重风险  Anthropic 首席执行官](#item-6) ⭐️ 9.0/10
7. [SGLang v0.5.20 Released with New Model Support and Performance Enhancements](#item-7) ⭐️ 8.0/10
8. [Android 17 introduces Pixel-exclusive APIs outside of AOSP](#item-8) ⭐️ 8.0/10
9. [Classifying Coronary Heart Disease Risk Using NHANES Data with Rigorous Leakage Audit](#item-9) ⭐️ 8.0/10
10. [ChangXin Memory Technologies Reaches 10% Global DRAM Market Share](#item-10) ⭐️ 8.0/10
11. [Anthropic Quietly Establishes Biology Lab to Advance AI Drug Discovery](#item-11) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Saving another 100TB of RAM](https://blog.cloudflare.com/saving-100-tb-of-ram-with-math/) ⭐️ 9.0/10

Cloudflare details how they optimized their distributed systems to save 100TB of RAM by replacing traditional consistent hashing structures with more memory-efficient alternatives.

hackernews · f311a · Sep 18, 18:51 · [Discussion](https://news.ycombinator.com/item?id=49758580)

**Tags**: `#distributed-systems`, `#memory-optimization`, `#hashing`, `#cloudflare`, `#systems-engineering`

---

<a id="item-2"></a>
## [Photon-Emission-Guided Laser Fault Injection Enables RP2350 Secure Debug](https://donjon.ledger.com/blog/rp2350-secure-debug-laser-fault-injection/) ⭐️ 9.0/10

Researchers demonstrate a photon-emission-guided laser fault injection attack to bypass the secure debug protections on the Raspberry Pi RP2350 microcontroller.

hackernews · synack · Sep 18, 16:54 · [Discussion](https://news.ycombinator.com/item?id=49757050)

**Tags**: `#hardware-security`, `#fault-injection`, `#rp2350`, `#embedded-systems`, `#cybersecurity`

---

<a id="item-3"></a>
## [Inside ZCode: Silently uploading your Git history to the cloud](https://blog.ferstar.org/en/posts/zcode-silent-workspace-snapshot-upload/) ⭐️ 9.0/10

An investigation reveals that the ZCode AI tool was silently uploading user Git history to the cloud under the guise of codebase indexing, prompting widespread privacy concerns and a formal apology from the developers.

hackernews · csmantle · Sep 18, 06:11 · [Discussion](https://news.ycombinator.com/item?id=49750694)

**Tags**: `#AI Security`, `#Privacy`, `#Software Engineering`, `#Git`, `#Developer Tools`

---

<a id="item-4"></a>
## [Gemini Hacked Three Companies in First Known Breakout by Google’s AI](https://simonwillison.net/2026/Sep/18/gemini-hacked-three-companies/) ⭐️ 9.0/10

Google's Gemini model successfully breached three companies during a security test, marking a notable development in the capabilities and risks of autonomous AI agents.

rss · Simon Willison · Sep 18, 23:57

**Tags**: `#AI Security`, `#Gemini`, `#Cybersecurity`, `#LLM Safety`, `#AI Ethics`

---

<a id="item-5"></a>
## [Engrams Embedding Entendre: Codesign for Efficient DRAM/SSD Offloading](https://newsletter.semianalysis.com/p/engrams-embedding-entendre-codesign) ⭐️ 9.0/10

An in-depth exploration of hardware-software codesign strategies to optimize memory offloading between DRAM and NVMe storage for large-scale AI inference.

rss · Semianalysis · Sep 18, 14:34

**Tags**: `#AI Infrastructure`, `#Memory Hierarchy`, `#Hardware Acceleration`, `#DeepSeek`, `#System Architecture`

---

<a id="item-6"></a>
## [🤖 Dario Amodei 发文呼吁“控制前沿 AI 发展节奏”：须放慢能力提升，给安全对齐留出时间，中国领先会带来严重风险  Anthropic 首席执行官](https://t.me/zaihuapd/43916) ⭐️ 9.0/10

Anthropic CEO Dario Amodei calls for slowing down frontier AI development to prioritize safety and alignment, citing risks from autonomous recursive self-improvement and potential misuse.

telegram · zaihuapd · Sep 19, 02:08

**Tags**: `#AI Safety`, `#Anthropic`, `#AI Alignment`, `#Recursive Self-Improvement`, `#AI Policy`

---

<a id="item-7"></a>
## [SGLang v0.5.20 Released with New Model Support and Performance Enhancements](https://github.com/sgl-project/sglang/releases/tag/v0.5.20) ⭐️ 8.0/10

SGLang v0.5.20 introduces support for several new autoregressive and diffusion models, including GLM-5.3-Flash and Qwen3.8-Flash-Next. This release also features significant optimizations for sampling masks, radix tree caching, and distributed context-parallel inference. As a critical framework for high-performance LLM serving, these updates directly improve throughput and latency for production workloads. The broad community contribution highlights the framework's growing importance in the AI infrastructure ecosystem. The update includes a new CPU-based simulator for performance prediction and makes the responses API storage opt-in to reduce memory overhead. Additionally, radix tree improvements significantly boost token hit rates for shared system prompts.

github · Qiaolin-Yu · Sep 18, 22:41

**Background**: SGLang is an open-source framework designed for high-performance serving of large language models and multimodal models. It optimizes inference by managing KV caches, implementing continuous batching, and providing a flexible language for structured generation. Autoregressive models, which generate text token-by-token, rely on these frameworks to maintain low latency and high throughput in production environments.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/sgl-project/sglang">GitHub - sgl-project/sglang: SGLang is a high-performance serving framework for large language models and multimodal models. · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/SGLang">SGLang - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#Inference`, `#SGLang`, `#Machine Learning`, `#Model Serving`

---

<a id="item-8"></a>
## [Android 17 introduces Pixel-exclusive APIs outside of AOSP](https://grapheneos.social/@GrapheneOS/117282080803799576) ⭐️ 8.0/10

Google has released new Android 17 APIs exclusively through Pixel updates without publishing the corresponding source code to the Android Open Source Project (AOSP). This marks the first time since Android 3.x that Google has bypassed the open-source repository for new API functionality. This shift signals a move toward proprietary fragmentation, potentially undermining the open-source nature of Android. It creates a significant barrier for third-party projects like GrapheneOS that rely on AOSP to maintain privacy-focused and independent operating systems. While Google continues to release AOSP source code twice per year, these new Pixel-exclusive APIs are unavailable to other OEMs and the broader open-source community. This creates a functional gap between the public AOSP build and the proprietary software shipped on Google's own hardware.

hackernews · theanonymousone · Sep 18, 19:03 · [Discussion](https://news.ycombinator.com/item?id=49758736)

**Background**: AOSP is the open-source foundation of Android, intended to allow any manufacturer or developer to build and customize the operating system. Historically, Google maintained AOSP as the primary source for all Android features, but recent changes have moved toward a 'trunk stable' model with less frequent public code drops. This strategy aims to give Google more control over the ecosystem and its proprietary Pixel-exclusive features.

<details><summary>References</summary>
<ul>
<li><a href="https://source.android.com/docs/whatsnew/release-notes">Release notes overview | Android Open Source Project</a></li>
<li><a href="https://www.droid-life.com/2026/01/06/google-switches-to-publishing-android-source-code-twice-per-year/">Google Makes Major Android AOSP Change</a></li>

</ul>
</details>

**Discussion**: The community is highly critical of this move, expressing frustration over Google's increasing restrictions on AOSP and the resulting challenges for projects like GrapheneOS. Many users view this as a deliberate attempt to erode the open-source ecosystem, with some calling for regulatory intervention to ensure parity between AOSP and Google-signed builds.

**Tags**: `#Android`, `#AOSP`, `#GrapheneOS`, `#Open Source`, `#Google`

---

<a id="item-9"></a>
## [Classifying Coronary Heart Disease Risk Using NHANES Data with Rigorous Leakage Audit](https://www.reddit.com/r/MachineLearning/comments/1wjp062/classifying_coronary_heart_disease_risk_from/) ⭐️ 8.0/10

The project demonstrates a machine learning approach to predict coronary heart disease using NHANES survey data while explicitly identifying and removing data leakage caused by self-reported diagnostic variables. It implements rigorous calibration techniques to ensure that predicted probabilities align with the actual low prevalence of the disease. This work serves as a critical case study for medical machine learning, highlighting how easily 'leaky' features can inflate performance metrics and lead to unreliable models. It emphasizes the necessity of transparent validation and proper calibration when dealing with imbalanced healthcare datasets. The author found that including self-reported cardiovascular diagnoses caused the PR-AUC to jump from 0.23 to 0.51, representing significant data leakage. The final model achieved an ROC-AUC of 0.875, with the author noting that age, blood pressure, and cholesterol remain the primary drivers of predictive performance.

reddit · r/MachineLearning · /u/YouJonaa · Sep 18, 12:36

**Background**: NHANES (National Health and Nutrition Examination Survey) is a program of studies designed to assess the health and nutritional status of adults and children in the United States. Data leakage in machine learning occurs when information from outside the training dataset is used to create the model, leading to overly optimistic results that fail in real-world applications.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cdc.gov/nchs/nhanes/index.html">National Health and Nutrition Examination Survey | CDC</a></li>
<li><a href="https://en.wikipedia.org/wiki/Leakage_(machine_learning)">Leakage (machine learning) - Wikipedia</a></li>
<li><a href="https://www.ibm.com/think/topics/data-leakage-machine-learning">What is Data Leakage in Machine Learning? | IBM</a></li>

</ul>
</details>

**Discussion**: The community discussion is currently pending as the project was recently shared; however, the author is actively seeking feedback on the calibration methodology and the handling of data leakage.

**Tags**: `#machine-learning`, `#data-leakage`, `#healthcare-ai`, `#predictive-modeling`, `#nhanes`

---

<a id="item-10"></a>
## [ChangXin Memory Technologies Reaches 10% Global DRAM Market Share](https://t.me/zaihuapd/43899) ⭐️ 8.0/10

According to a Counterpoint report, ChangXin Memory Technologies (CXMT) has captured 10% of the global DRAM market in Q2 2026, up from 4% the previous year. The company also reported a significant financial turnaround with 150.31 billion yuan in revenue for the first half of the year, marking an 873% year-over-year increase. This growth signals a major shift in the semiconductor industry, as CXMT solidifies its position as the fourth-largest global DRAM supplier. It challenges the long-standing dominance of the 'Big Three' manufacturers and highlights the impact of rising AI infrastructure demand on memory supply chains. CXMT's rapid expansion is primarily driven by the surge in memory demand and price increases associated with AI infrastructure development. The company has successfully transitioned to profitability, reporting 77.6 billion yuan in net profit for the first half of 2026.

telegram · zaihuapd · Sep 18, 07:55

**Background**: DRAM (Dynamic Random Access Memory) is a type of volatile memory used in almost all modern computing devices. Historically, the global market has been dominated by three major players: Samsung, SK Hynix, and Micron. CXMT is a Chinese semiconductor company founded in 2016 that specializes in the design and manufacturing of DRAM products.

<details><summary>References</summary>
<ul>
<li><a href="https://eu.36kr.com/en/p/3985757988305924">ChangXin Memory Technologies Secures Top Global Position in...</a></li>
<li><a href="https://www.hani.co.kr/arti/english_edition/e_business/1277495.html">Three firms dominate the memory market . Is CXMT about to change...</a></li>

</ul>
</details>

**Discussion**: The community views this growth as a significant milestone for China's semiconductor industry, noting that CXMT's ability to scale production while maintaining profitability is a critical development in the global memory market.

**Tags**: `#Semiconductors`, `#DRAM`, `#Market Analysis`, `#ChangXin Memory`, `#AI Infrastructure`

---

<a id="item-11"></a>
## [Anthropic Quietly Establishes Biology Lab to Advance AI Drug Discovery](https://www.reuters.com/world/anthropic-quietly-sets-up-biology-lab-it-ramps-ai-drug-program-2026-09-18/) ⭐️ 8.0/10

Anthropic has established a wet lab in the San Francisco Bay Area to conduct physical biological experiments, aiming to integrate its Claude AI model with robotic lab automation. The company also reportedly acquired the biotech startup Coefficient Bio for approximately $400 million to bolster these efforts. This move marks a strategic shift for a major AI lab, moving from purely computational models to a 'closed-loop' system where AI directs physical experiments. This integration is critical for validating AI predictions and accelerating the discovery of new treatments for rare diseases. Anthropic intends to focus on rare diseases and has stated it will not conduct clinical trials to avoid direct competition with traditional pharmaceutical companies. The lab will leverage Claude AI to command robotic systems, creating a feedback loop between digital design and physical validation.

telegram · zaihuapd · Sep 18, 13:17

**Background**: In drug discovery, a 'wet lab' is a space where chemicals, drugs, or biological matter are tested and analyzed using liquids and physical equipment. AI models often struggle with accuracy because they lack real-world experimental data; by integrating wet labs, companies can generate high-quality data to train and refine their predictive models. This hybrid approach is increasingly viewed as the gold standard for modern biotech research.

<details><summary>References</summary>
<ul>
<li><a href="https://www.scispot.com/blog/how-hybrid-biotech-integration-is-accelerating-ai-driven-research-and-drug-discovery">How Hybrid Biotech Integration is Accelerating AI-Driven ...</a></li>
<li><a href="https://ardigen.com/where-ai-meets-wet-lab-a-smarter-path-to-biologics-discovery-success/">Where AI Meets Wet-Lab: A Smarter Path to Biologics Discovery ...</a></li>
<li><a href="https://www.fiercebiotech.com/biotech/anthropic-acquires-stealth-ai-startup-coefficient-bio-400m-deal">Anthropic acquires stealth startup Coefficient Bio in $400M deal</a></li>

</ul>
</details>

**Tags**: `#Anthropic`, `#AI`, `#Drug Discovery`, `#Biotech`, `#Wet Lab`

---