---
layout: default
title: "Horizon Summary: 2026-09-08 (EN)"
date: 2026-09-08
lang: en
---

> From 35 items, 14 important content pieces were selected

---

1. [Google Accelerates TPU Infrastructure Externalization via InferenceX](#item-1) ⭐️ 9.0/10
2. [LLM-guided program evolution improves 10 best-known circle-packing solutions](#item-2) ⭐️ 9.0/10
3. [UNEP Reports Global Warming Likely to Exceed 1.5°C Target](#item-3) ⭐️ 9.0/10
4. [美国审查中国 AI 企业海外获取英伟达芯片渠道  知情人士透露，美国商务部工业与安全局（BIS）正系统性审查中国 AI 企业如何在海外获取和使用英伟达芯片，包括](#item-4) ⭐️ 9.0/10
5. [I've factored the RSA keys of a Certificate Authority from the 90s](#item-5) ⭐️ 8.0/10
6. [Jellyfin 12.0](#item-6) ⭐️ 8.0/10
7. [Creepy crawlies](#item-7) ⭐️ 8.0/10
8. [OpenAI Chief Scientist Jakub Pachocki on Defensive AI Strategy](#item-8) ⭐️ 8.0/10
9. [Generating Bad Apple autonomously using a tiny 417k parameter recurrent dynamical system](#item-9) ⭐️ 8.0/10
10. [EmbedFlow Enables Zero-Downtime Migration Between Embedding Models](#item-10) ⭐️ 8.0/10
11. [Rustuna: A High-Performance Rust Implementation of Optuna](#item-11) ⭐️ 8.0/10
12. [Proposing a Stockfish-like evaluation engine for competitive games using Offline RL](#item-12) ⭐️ 8.0/10
13. [Ukraine Becomes First European Nation to Launch Starlink Direct to Cell Service](#item-13) ⭐️ 8.0/10
14. [ByteDance Reportedly Planning 5-Trillion Parameter Large Language Model](#item-14) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Google Accelerates TPU Infrastructure Externalization via InferenceX](https://newsletter.semianalysis.com/p/tpu-inferencex-full-steam) ⭐️ 9.0/10

Google is aggressively expanding the external availability of its TPU infrastructure, including the new TPUv8i architecture, to provide up to 50% better price-performance ratios for AI inference. This initiative, tracked by the InferenceX benchmarking platform, marks a strategic shift to make Google's specialized hardware more accessible to external developers. This move directly challenges NVIDIA's market dominance by attempting to erode the 'CUDA moat' through superior hardware efficiency and broader accessibility. By offering a more cost-effective alternative for inference, Google aims to capture a larger share of the AI compute market currently dominated by NVIDIA GPUs. The strategy includes the introduction of the TPUv8i chip, which is specifically optimized for power efficiency and inference throughput. InferenceX serves as a critical benchmarking tool to validate these performance claims against existing NVIDIA and AMD hardware stacks.

rss · Semianalysis · Sep 7, 20:00

**Background**: TPUs (Tensor Processing Units) are Google's custom-designed ASICs built specifically for machine learning workloads. The 'CUDA moat' refers to the significant competitive advantage NVIDIA maintains due to its mature software ecosystem, which makes it difficult for developers to switch to alternative hardware without substantial code refactoring.

<details><summary>References</summary>
<ul>
<li><a href="https://www.servethehome.com/googles-tpuv8s-for-training-and-inference-at-hot-chips-2026/">Google 's TPUv 8 s for Training and Inference at Hot... - ServeTheHome</a></li>
<li><a href="https://inferencex.semianalysis.com/">Open-Source Agentic Inference Benchmark | InferenceX</a></li>
<li><a href="https://quantabundancia.com/articles/nvda-cuda-moat">The CUDA moat - why NVIDIA's software ecosystem defends the...</a></li>

</ul>
</details>

**Discussion**: The community is closely monitoring whether Google's hardware performance gains can overcome the behavioral and ecosystem lock-in associated with CUDA. Many observers are skeptical about the ease of migration, noting that software compatibility remains a significant hurdle for widespread TPU adoption.

**Tags**: `#Google Cloud`, `#TPU`, `#AI Infrastructure`, `#NVIDIA`, `#Inference`

---

<a id="item-2"></a>
## [LLM-guided program evolution improves 10 best-known circle-packing solutions](https://www.reddit.com/r/MachineLearning/comments/1w9xlyi/llmguided_program_evolution_improves_10_bestknown/) ⭐️ 9.0/10

Researchers used an LLM to iteratively evolve optimization algorithms, successfully improving the best-known solutions for 10 values of the Packomania csqv benchmark. The process achieved improvements of 2.4% to 5.4% in just 15 iterations at a total cost of $27.72. This work demonstrates a highly cost-effective method for automated scientific discovery by using LLMs to evolve algorithms rather than just generating static solutions. It highlights the potential for AI to push the boundaries of long-standing mathematical optimization problems. The approach uses a seed solver where the LLM proposes algorithmic changes based on a scoreboard and history, with an independent verifier ensuring only successful improvements are retained. The author specifically seeks feedback on the plateau-detection stopping rule used in the loop.

reddit · r/MachineLearning · /u/SIGH_I_CALL · Sep 7, 16:54

**Background**: Circle packing is a mathematical optimization problem that involves arranging circles of various sizes within a container, such as a unit square, to maximize the sum of their radii. The Packomania csqv benchmark is a well-known repository for these packing problems, providing a standard for comparing the efficiency of different optimization algorithms.

<details><summary>References</summary>
<ul>
<li><a href="https://packomania.com/csqv/csqv.html">The best known packings of unequal circles in a square</a></li>
<li><a href="https://arxiv.org/html/2609.05093">LLM-Guided Program Evolution for Circle Packing :Breaking 10...</a></li>

</ul>
</details>

**Discussion**: The community has shown significant interest in the methodology, particularly regarding the effectiveness of the plateau-detection stopping rule and the potential for applying this evolutionary loop to other optimization domains.

**Tags**: `#LLM`, `#Optimization`, `#Automated Discovery`, `#Mathematics`, `#Algorithms`

---

<a id="item-3"></a>
## [UNEP Reports Global Warming Likely to Exceed 1.5°C Target](http://www.unep.org/resources/limiting-overshoot-navigating-exceedance) ⭐️ 9.0/10

The United Nations Environment Programme (UNEP) reports that current global emission trajectories are projected to peak at approximately 1.8°C, surpassing the 1.5°C limit set by the Paris Agreement. Exceeding the 1.5°C threshold significantly increases the risk of triggering dangerous climate tipping points, which could lead to irreversible and catastrophic changes in the Earth's climate system. The report highlights that current national emission reduction efforts are insufficient and failing to meet the necessary speed required to keep warming within the 1.5°C limit.

telegram · zaihuapd · Sep 8, 03:05

**Background**: The Paris Agreement is an international treaty aimed at limiting global warming to well below 2°C, preferably 1.5°C, compared to pre-industrial levels. Climate tipping points are critical thresholds in the Earth's system that, once crossed, can lead to large-scale and often irreversible shifts in climate states.

<details><summary>References</summary>
<ul>
<li><a href="https://zh.wikipedia.org/zh-hans/气候临界点">气候临界点 - 维基百科，自由的百科全书</a></li>
<li><a href="https://ideacarbon.org/news_free/52463/">全球15个"气候临界点"已被激活9个:或许,你已经在见证人类历史</a></li>

</ul>
</details>

**Tags**: `#Climate Change`, `#UNEP`, `#Sustainability`, `#Environmental Policy`, `#Global Warming`

---

<a id="item-4"></a>
## [美国审查中国 AI 企业海外获取英伟达芯片渠道  知情人士透露，美国商务部工业与安全局（BIS）正系统性审查中国 AI 企业如何在海外获取和使用英伟达芯片，包括](https://t.me/zaihuapd/43676) ⭐️ 9.0/10

The U.S. Department of Commerce is systematically investigating how Chinese AI firms bypass export restrictions by remotely accessing NVIDIA chips through overseas cloud services.

telegram · zaihuapd · Sep 8, 03:35

**Tags**: `#AI Policy`, `#Geopolitics`, `#Semiconductors`, `#Export Controls`, `#Cloud Computing`

---

<a id="item-5"></a>
## [I've factored the RSA keys of a Certificate Authority from the 90s](https://mcpherrin.ca/2026/09/07/rsa.html) ⭐️ 8.0/10

A researcher successfully factors 1990s-era 512-bit RSA keys from a Certificate Authority using a consumer GPU, highlighting the vulnerability of historical encrypted traffic.

hackernews · ahlCVA · Sep 8, 01:16 · [Discussion](https://news.ycombinator.com/item?id=49604637)

**Tags**: `#cryptography`, `#rsa`, `#cybersecurity`, `#legacy-systems`, `#infosec`

---

<a id="item-6"></a>
## [Jellyfin 12.0](https://jellyfin.org/posts/jellyfin-release-12.0/) ⭐️ 8.0/10

Jellyfin 12.0 introduces significant performance improvements and stability updates for its open-source media server platform, drawing positive feedback from users migrating from commercial alternatives.

hackernews · 0xC0ncord · Sep 8, 01:56 · [Discussion](https://news.ycombinator.com/item?id=49604861)

**Tags**: `#Jellyfin`, `#Media Server`, `#Open Source`, `#Self-hosting`, `#Software Release`

---

<a id="item-7"></a>
## [Creepy crawlies](https://simonwillison.net/2026/Sep/7/creepy-crawlies/) ⭐️ 8.0/10

Konstantin Ryabitsev reports that abusive web crawlers consume more CPU cycles on kernel.org than legitimate traffic, raising concerns about the impact of automated scraping on infrastructure.

rss · Simon Willison · Sep 7, 23:08

**Tags**: `#web-scraping`, `#infrastructure`, `#linux-kernel`, `#git`, `#web-sustainability`

---

<a id="item-8"></a>
## [OpenAI Chief Scientist Jakub Pachocki on Defensive AI Strategy](https://simonwillison.net/2026/Sep/7/jakub-pachocki/) ⭐️ 8.0/10

OpenAI Chief Scientist Jakub Pachocki argues that developing advanced, aligned AI is a necessary defensive measure against potential AI-driven threats. He emphasizes that while this necessitates continued progress, it must not serve as a justification for reckless development. This stance highlights a critical strategic shift in the AI industry, framing the development of powerful AI as a cybersecurity necessity rather than just a competitive race. It reflects the growing tension between accelerating AI capabilities and the imperative of safety and alignment. Pachocki specifically identifies securing infrastructure and protecting against rogue AI agents as primary goals for future deployment efforts. He explicitly rejects the 'race at all costs' mentality, citing the high stakes involved in AI development.

rss · Simon Willison · Sep 7, 22:26

**Background**: The concept of 'AI alignment' refers to the challenge of ensuring that AI systems act in accordance with human values and intentions. As AI models become more autonomous, the risk of them being used for malicious purposes or behaving unpredictably has become a central focus of global AI policy and safety research.

**Tags**: `#AI Safety`, `#OpenAI`, `#AI Ethics`, `#AI Policy`, `#Cybersecurity`

---

<a id="item-9"></a>
## [Generating Bad Apple autonomously using a tiny 417k parameter recurrent dynamical system](https://www.reddit.com/r/MachineLearning/comments/1wa8rub/generating_bad_apple_autonomously_from_a_single/) ⭐️ 8.0/10

A researcher developed a compact recurrent neural network that autonomously generates the entire 6,500-frame 'Bad Apple' video sequence from a single initial latent state. The model operates in a closed loop without requiring external timestamp inputs. This project demonstrates the potential of recurrent dynamical systems for efficient generative video, offering a lightweight alternative to standard coordinate-based MLPs. It highlights techniques for stabilizing long-horizon generation in neural networks. The model uses 417,129 parameters (~1.60 MB) and achieves over 200 FPS on an RTX 4080. Training involved a curriculum of increasing rollout horizons and state perturbation noise to ensure long-term trajectory stability.

reddit · r/MachineLearning · /u/SEBADA321 · Sep 8, 00:05

**Background**: Coordinate-based MLPs, such as SIREN, typically represent video by mapping time and spatial coordinates to pixel values. In contrast, recurrent dynamical systems model the temporal flow of latent states, allowing the system to 'evolve' the video frame-by-frame from an initial condition.

<details><summary>References</summary>
<ul>
<li><a href="https://velog.io/@yeomjinseop/Implicit-Neural-Representations-with-Periodic-Activation-Functions">Implicit Neural Representations with Periodic Activation Functions</a></li>

</ul>
</details>

**Discussion**: The community expressed strong interest in the technical novelty of the approach, specifically praising the use of Muon optimization and the curriculum learning strategy for stabilizing the recurrent dynamics.

**Tags**: `#Machine Learning`, `#Generative Models`, `#RNN`, `#Computer Vision`, `#Neural Dynamics`

---

<a id="item-10"></a>
## [EmbedFlow Enables Zero-Downtime Migration Between Embedding Models](https://www.reddit.com/r/MachineLearning/comments/1wabmm7/my_lab_found_a_way_to_migrate_between_embedding/) ⭐️ 8.0/10

The author introduced 'embedflow,' a tool that allows users to switch between embedding models without performing a full, time-consuming re-indexing of their entire document database. It works by taking a subset of documents from the old index and reranking them using the new model to maintain retrieval quality. Upgrading embedding models in large-scale RAG systems is typically a massive engineering bottleneck that requires days of compute time. This tool provides a practical heuristic to bypass expensive backfills, significantly reducing operational downtime and costs. The library is compatible with Qdrant and is available via PyPI; tests showed that reranking as few as 50 documents can achieve retrieval quality comparable to native indexing. Determining the optimal number of documents (K) to rerank remains a critical challenge for users.

reddit · r/MachineLearning · /u/Potential_Low_1183 · Sep 8, 02:16

**Background**: In RAG (Retrieval-Augmented Generation) systems, documents are converted into vector embeddings to enable semantic search. When a developer upgrades to a better embedding model, the entire database must usually be re-indexed, which is computationally expensive and can take days for millions of documents.

<details><summary>References</summary>
<ul>
<li><a href="https://pypi.org/project/embedflow/0.1.0/">embedflow · PyPI</a></li>
<li><a href="https://qdrant.tech/documentation/tutorials-operations/embedding-model-migration/">Migrate to a New Embedding Model - Qdrant</a></li>

</ul>
</details>

**Discussion**: The community is actively debating the mathematical validity of the reranking heuristic and discussing potential edge cases where the method might fail to match native retrieval quality. Some users are also comparing this approach to existing strategies like dual-writing or named vector columns in vector databases.

**Tags**: `#RAG`, `#Vector Databases`, `#Machine Learning`, `#Embeddings`, `#System Architecture`

---

<a id="item-11"></a>
## [Rustuna: A High-Performance Rust Implementation of Optuna](https://www.reddit.com/r/MachineLearning/comments/1w9nyhz/rustuna_a_highperformance_rust_implementation_of/) ⭐️ 8.0/10

Rustuna has been released as a high-speed, memory-efficient implementation of the Optuna hyperparameter optimization framework written entirely in Rust. It maintains API compatibility with the original Optuna while eliminating all Python dependencies. This development is significant for the machine learning ecosystem as it provides a faster, more secure, and resource-efficient alternative to the standard Python-based Optuna. By removing Python dependencies, it also mitigates risks associated with software supply chain attacks. Rustuna leverages Rust's native memory management to significantly reduce memory overhead compared to its Python counterpart. It is designed to be a drop-in replacement for users familiar with the existing Optuna workflow.

reddit · r/MachineLearning · /u/c-bata · Sep 7, 10:01

**Background**: Optuna is a popular open-source hyperparameter optimization framework used to automate the search for optimal machine learning model configurations. Hyperparameter optimization is a critical process in machine learning that involves tuning parameters to improve model performance and accuracy.

**Discussion**: The community has shown interest in the performance benefits of a Rust-based implementation and the improved security posture gained by removing Python dependencies. Users are particularly focused on how easily they can migrate existing projects to the new framework.

**Tags**: `#Rust`, `#Machine Learning`, `#Hyperparameter Optimization`, `#Optuna`, `#Performance`

---

<a id="item-12"></a>
## [Proposing a Stockfish-like evaluation engine for competitive games using Offline RL](https://www.reddit.com/r/MachineLearning/comments/1wadyz7/what_if_competitive_games_such_as_rocket_league/) ⭐️ 8.0/10

The proposal suggests using Offline Reinforcement Learning techniques, specifically Trajectory Transformers and Implicit Q-Learning, to evaluate decision-making quality in physics-based games like Rocket League. It also explores using frequency spectrum analysis and kinematic limits to detect cheating and smurfing. This approach could provide a standardized, objective metric for player performance, similar to how chess engines analyze move quality. It offers a path to move beyond simple statistics toward understanding the mathematical optimality of player actions in complex, continuous environments. The model treats the game as a Sequential Partially Observable Markov Decision Process (POMDP) and calculates decision probabilities based on professional gameplay datasets. It specifically leverages Implicit Q-Learning to estimate the value of optimal actions without requiring direct interaction with the environment.

reddit · r/MachineLearning · /u/Ligras · Sep 8, 04:11

**Background**: Stockfish is a powerful open-source chess engine that evaluates positions to determine the best possible move. Offline Reinforcement Learning allows agents to learn optimal policies from static datasets without needing to interact with a live environment, making it suitable for analyzing recorded game replays.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2110.06169">[2110.06169] Offline Reinforcement Learning with Implicit Q-Learning</a></li>
<li><a href="https://github.com/ikostrikov/implicit_q_learning">GitHub - ikostrikov/implicit_q_learning · GitHub</a></li>

</ul>
</details>

**Discussion**: The community has engaged in high-quality technical discussions regarding the feasibility of applying chess-like analysis to continuous-state environments. Participants are debating the challenges of modeling high-dimensional physics and the difficulty of defining 'optimal' play in games that lack the discrete, turn-based structure of chess.

**Tags**: `#Reinforcement Learning`, `#Game AI`, `#Offline RL`, `#Competitive Gaming`, `#Decision Theory`

---

<a id="item-13"></a>
## [Ukraine Becomes First European Nation to Launch Starlink Direct to Cell Service](https://t.me/zaihuapd/43673) ⭐️ 8.0/10

Ukrainian telecom operator Kyivstar has launched Starlink's Direct to Cell service, allowing users to connect to satellite networks using their existing smartphones. This makes Ukraine the first country in Europe to deploy this technology for public use. This deployment provides a critical lifeline for communication in conflict zones and areas with damaged infrastructure, ensuring connectivity where traditional ground networks fail. It demonstrates the practical resilience of satellite-to-mobile technology in emergency scenarios. The service currently supports text messaging for all Kyivstar users without requiring hardware upgrades, with plans to expand to data, voice, and video capabilities in the future. It is being offered as a trial to ensure connectivity in frontline and humanitarian mission areas.

telegram · zaihuapd · Sep 8, 02:35

**Background**: Starlink's Direct to Cell technology uses specialized satellites to provide connectivity directly to standard LTE-enabled smartphones, bypassing the need for traditional cell towers. This is particularly valuable in remote or disaster-stricken regions where ground-based telecommunications infrastructure is unavailable or destroyed.

<details><summary>References</summary>
<ul>
<li><a href="https://starlink.com/public-files/DIRECT_TO_CELL_SERVICE_FEB_25.pdf">STARLINK DIRECT TO CELL SERVICE NOW AVAILABLE</a></li>
<li><a href="https://www.starlink.com/business/direct-to-cell">Starlink Business | Starlink Mobile</a></li>

</ul>
</details>

**Tags**: `#Starlink`, `#Telecommunications`, `#Satellite Technology`, `#Ukraine`, `#Direct to Cell`

---

<a id="item-14"></a>
## [ByteDance Reportedly Planning 5-Trillion Parameter Large Language Model](https://t.me/zaihuapd/43677) ⭐️ 8.0/10

ByteDance is reportedly in the early stages of planning a large language model with over 5 trillion parameters, led by Seed Foundation head Xiang Liang and pre-training data lead Shen Ke. This move signals a significant strategic shift for ByteDance, prioritizing raw scaling and intelligence ceilings over model distillation, which aligns with CEO Zhang Yiming's vision for long-term innovation. If realized, this model would surpass current domestic leaders like Alibaba's Qwen 3.8-Max and Moonshot AI's K3 in parameter scale, with a specific focus on programming capabilities.

telegram · zaihuapd · Sep 8, 04:05

**Background**: Model distillation is a technique where a smaller 'student' model learns to mimic the behavior of a larger 'teacher' model to improve efficiency. ByteDance's Seed Foundation is the company's dedicated research division focused on pushing the boundaries of general intelligence and foundation models.

<details><summary>References</summary>
<ul>
<li><a href="https://seed.bytedance.com/">ByteDance Seed</a></li>
<li><a href="https://kingy.ai/blog/ai-model-distillation-explained/">AI Model Distillation Explained: Technical Guide | Kingy AI</a></li>

</ul>
</details>

**Discussion**: The community is noting the strategic pivot away from distillation, viewing it as a bold bet on large-scale compute to achieve true breakthroughs rather than incremental improvements.

**Tags**: `#ByteDance`, `#LLM`, `#AI Infrastructure`, `#Machine Learning`, `#Large-scale Models`

---