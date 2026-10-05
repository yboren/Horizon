---
layout: default
title: "Horizon Summary: 2026-10-05 (EN)"
date: 2026-10-05
lang: en
---

> From 24 items, 7 important content pieces were selected

---

1. [Top ARC-AGI Benchmark Scores Jump from 7% to 56% on Kaggle](#item-1) ⭐️ 9.0/10
2. [DynaBase: A Minimal Interpretable Architecture for Zero-Shot Dynamical Systems Reconstruction](#item-2) ⭐️ 9.0/10
3. [Run Qwen 3.8 Flash Next (125B) on consumer hardware at 100T/s with Strata](#item-3) ⭐️ 8.0/10
4. [Researcher Releases 3.9B Position Dataset for Distilling Stockfish](#item-4) ⭐️ 8.0/10
5. [ASRN: Adaptive Sparse Recurrence Network for Efficient Language Modeling](#item-5) ⭐️ 8.0/10
6. [Nonobench: An Open-Source Benchmark Evaluating 49 LLMs on Nonogram Puzzles](#item-6) ⭐️ 8.0/10
7. [Google Releases VeriHarness for Long-Horizon Task Verification](#item-7) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Top ARC-AGI Benchmark Scores Jump from 7% to 56% on Kaggle](https://www.reddit.com/r/MachineLearning/comments/1wxcd4k/top_arc%CE%B1gi3_scores_on_kaggle_just_went_from_7_to/) ⭐️ 9.0/10

Recent Kaggle submissions have seen top performance on the ARC-AGI benchmark surge from 7% to 56% accuracy. This rapid improvement was achieved using small, local AI models rather than massive, cloud-based systems. This milestone challenges the assumption that ARC-AGI requires human-level reasoning or massive scale to solve, suggesting that more efficient algorithmic approaches are highly effective. It marks a significant shift in how researchers evaluate progress toward AGI. The performance gains were achieved within a 30-day period using constrained local model environments. These results indicate that small models can now outperform average humans on tasks specifically designed to test abstract reasoning.

reddit · r/MachineLearning · /u/we_are_mammals · Oct 4, 10:24 · [Discussion](https://www.reddit.com/r/MachineLearning/comments/1wxcd4k/top_arcαgi3_scores_on_kaggle_just_went_from_7_to/)

**Background**: The ARC-AGI (Abstraction and Reasoning Corpus for Artificial General Intelligence) is a benchmark designed by François Chollet to measure an AI's ability to learn new skills and solve novel problems. Unlike traditional benchmarks that rely on pattern recognition in large datasets, ARC-AGI tests for fluid intelligence and the ability to generalize from very few examples.

**Discussion**: The community is actively debating whether these results represent a genuine breakthrough in reasoning or if they indicate that the benchmark is becoming susceptible to specialized optimization techniques. Many users are surprised by the rapid pace of improvement and are questioning the implications for future AGI development.

**Tags**: `#AI`, `#ARC-AGI`, `#Machine Learning`, `#Benchmarking`, `#AGI`

---

<a id="item-2"></a>
## [DynaBase: A Minimal Interpretable Architecture for Zero-Shot Dynamical Systems Reconstruction](https://www.reddit.com/r/MachineLearning/comments/1wxex8n/a_minimal_interpretable_architecture_for_zeroshot/) ⭐️ 9.0/10

Researchers introduced DynaBase, a minimal architecture that uses a single-parameter piecewise affine map and a context selector to reconstruct dynamical systems. It achieves zero-shot performance across various regimes, including fixed points, limit cycles, and chaotic attractors. DynaBase challenges the need for complex foundation models in dynamical systems by demonstrating that minimal, interpretable components can outperform larger models. This provides a tractable mathematical framework to better analyze and understand the performance of time series and dynamical system foundation models. The model uses a single parameter α to control local divergence rates and can be trained analytically via linear regression or a simple grid search. It effectively preserves the correct dynamical regime, unlike basic context-parroting methods.

reddit · r/MachineLearning · /u/DangerousFunny1371 · Oct 4, 12:49

**Background**: Dynamical systems are mathematical models used to describe how a point in a geometric space changes over time, often applied in fields like climate science and neuroscience. Piecewise affine maps are a class of functions that define dynamics by splitting the state space into regions, each governed by a linear transformation. Zero-shot reconstruction refers to the ability of a model to infer the behavior of a new, unseen dynamical system without requiring specific retraining.

<details><summary>References</summary>
<ul>
<li><a href="https://www.sciencedirect.com/science/article/pii/S0022000026000930">Piecewise rational affine maps, multidimensional generalized ...</a></li>
<li><a href="https://arxiv.org/abs/2505.13192">[2505.13192] True Zero-Shot Inference of Dynamical Systems ...</a></li>

</ul>
</details>

**Discussion**: The community has shown significant interest in the paper's focus on interpretability and its ability to outperform complex models with such a simple, mathematically grounded approach.

**Tags**: `#Machine Learning`, `#Dynamical Systems`, `#Interpretability`, `#Foundation Models`, `#NeurIPS`

---

<a id="item-3"></a>
## [Run Qwen 3.8 Flash Next (125B) on consumer hardware at 100T/s with Strata](https://github.com/Niko1221/Strata) ⭐️ 8.0/10

The Strata project enables high-speed inference of large-scale models like Qwen 3.8 Flash Next on consumer-grade hardware, achieving speeds exceeding 100 tokens per second on an RTX 4090. This allows users to run massive models that typically require enterprise-grade infrastructure on standard desktop setups. This development significantly lowers the barrier to entry for running frontier-scale AI models locally, potentially democratizing access to high-performance inference. It demonstrates that extreme optimization can make massive parameter models practical for individual developers and hobbyists. Strata utilizes advanced quantization techniques to fit large models into consumer VRAM, though early community testing suggests these optimizations may lead to a noticeable degradation in model accuracy compared to standard frameworks like llama.cpp.

hackernews · snehesht · Oct 4, 12:51 · [Discussion](https://news.ycombinator.com/item?id=49953495)

**Background**: Large Language Models (LLMs) typically require massive amounts of VRAM to run, often necessitating expensive enterprise GPUs. Quantization is a technique used to reduce the precision of model weights, allowing them to occupy less memory and run faster, albeit often at the cost of some performance or output quality.

**Discussion**: The community is divided; while many are impressed by the speed gains on consumer hardware, others are skeptical about the significant accuracy trade-offs observed in benchmarks. Some users have reported successful deployment across various hardware configurations, including iGPUs and older PCIe generations.

**Tags**: `#LLM`, `#Inference`, `#Quantization`, `#Hardware Acceleration`, `#Open Source`

---

<a id="item-4"></a>
## [Researcher Releases 3.9B Position Dataset for Distilling Stockfish](https://www.reddit.com/r/MachineLearning/comments/1wxz5qq/distilling_stockfish_on_a_billion_positions_full/) ⭐️ 8.0/10

A researcher has released a 3.9 billion position dataset derived from 37 months of Lichess games to distill the Stockfish value function into hybrid CNN-ViT neural network architectures. The project aims to create a faster approximation of depth-limited search compared to traditional methods. This work provides a massive, high-quality dataset for chess engine research and demonstrates the effectiveness of hybrid architectures in capturing complex board evaluations. It offers a potential alternative to NNUE by leveraging the strengths of both convolutional and transformer-based models. The author found that while CNNs excel early in training due to their geometric inductive biases, Vision Transformers (ViT) were initially slow to learn board patterns; combining both architectures yielded the best performance.

reddit · r/MachineLearning · /u/microscope1024 · Oct 5, 04:11

**Background**: Knowledge distillation is a technique where a smaller 'student' model is trained to mimic the behavior of a larger, more complex 'teacher' model like Stockfish. NNUE (Efficiently Updatable Neural Network) is the current standard in modern chess engines, using a small, fast neural network to evaluate positions. Geometric inductive bias refers to the structural assumptions in models like CNNs that help them efficiently process spatial data like a chessboard.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Knowledge_distillation">Knowledge distillation - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Efficiently_updatable_neural_network">Efficiently updatable neural network - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The community has shown significant interest in the dataset's scale and the architectural comparison between CNNs and ViTs for game state evaluation.

**Tags**: `#machine-learning`, `#chess-engines`, `#dataset`, `#neural-networks`, `#distillation`

---

<a id="item-5"></a>
## [ASRN: Adaptive Sparse Recurrence Network for Efficient Language Modeling](https://www.reddit.com/r/MachineLearning/comments/1wxs8qq/asrn_adaptive_sparse_recurrence_network_n/) ⭐️ 8.0/10

The Adaptive Sparse Recurrence Network (ASRN) introduces a novel copy layer that uses learned hash tables to identify and replicate context from previous sequences. This mechanism allows language models to achieve linear memory scaling relative to sequence length. This architecture addresses the quadratic memory bottleneck inherent in standard Transformer attention mechanisms. By enabling linear memory scaling, it facilitates the processing of significantly longer contexts with greater computational efficiency. ASRN functions by using learned hash tables to perform lookups on past activation patterns, effectively acting as a sparse memory retrieval system. This approach avoids the need to store or compute full attention matrices, which is critical for resource-constrained environments.

reddit · r/MachineLearning · /u/Mean-Disaster8380 · Oct 4, 22:17

**Background**: Standard Transformer models rely on attention mechanisms that scale quadratically with sequence length, leading to high memory usage for long inputs. Researchers are increasingly exploring linear complexity models, such as RNN-based architectures or sparse attention methods, to overcome these scaling limitations. Learned hash tables are often used in neural architectures to replace dense indexing, allowing for faster and more memory-efficient data retrieval.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2406.16690v1">Scaling Laws for Linear Complexity Language Models - arXiv.org</a></li>
<li><a href="https://arxiv.org/abs/2312.17241">Compact Neural Graphics Primitives with Learned Hash Probing GitHub - StochasticLP/Learned-Hash-Functions: The hash ... Compact NGP: Compact Neural Graphics Primitives with Learned ... Researchers find neural networks use hash tables for memory... Can Learned Models Replace Hash Functions? Sparse neural networks and hash tables with Locality ... Hash Tables as Engines of Randomness at the Limits of ... - MDPI</a></li>

</ul>
</details>

**Tags**: `#Machine Learning`, `#Language Models`, `#Neural Architectures`, `#Efficient AI`

---

<a id="item-6"></a>
## [Nonobench: An Open-Source Benchmark Evaluating 49 LLMs on Nonogram Puzzles](https://www.reddit.com/r/MachineLearning/comments/1wxa2bs/nonobench_an_open_benchmark_of_49_llms_on/) ⭐️ 8.0/10

Nonobench is a new open-source benchmark that evaluates 49 LLMs on their ability to solve nonogram puzzles, ranging from 5x5 to 20x20 grids. The study reveals that model performance drops significantly as logic complexity increases, with solve rates falling from 85% on small puzzles to 20% on 15x15 grids. This benchmark provides a rigorous test of LLM reasoning capabilities beyond simple pattern matching or memorization. By using logic-based puzzles, it highlights the current limitations of AI in handling complex, multi-step deductive tasks. The benchmark uses 130 puzzle variants and requires models to output grid solutions without external tools in a single attempt. To prevent models from guessing based on common images, the puzzles use random fills, and hard mode requires outputting an array of row strings to maintain accuracy.

reddit · r/MachineLearning · /u/mauricekleine · Oct 4, 07:57

**Background**: Nonograms, also known as Picross, are logic puzzles where players fill in grid cells based on numerical clues to reveal a hidden image. Solving them requires deductive reasoning, often involving line logic where clues constrain the placement of filled squares. While some puzzles can be solved using simple line-by-line deduction, more complex ones require advanced logical strategies.

<details><summary>References</summary>
<ul>
<li><a href="https://www.crazygames.com/game/nonogram">Nonogram Play on CrazyGames</a></li>
<li><a href="https://puzzling.stackexchange.com/questions/129849/nonograms-that-require-more-than-single-line-logic">logical deduction - Nonograms that require more than single- line ...</a></li>
<li><a href="https://printjoey.com/en/tools/nonogram-generator">Nonogram Generator — Free Printable Picture Logic Puzzles (PDF)</a></li>

</ul>
</details>

**Discussion**: The community discussion focuses on the methodology of the benchmark and the inherent difficulties LLMs face with grid-based logic. Users have expressed interest in the limitations of current models when handling tasks that require strict adherence to logical constraints rather than probabilistic generation.

**Tags**: `#LLM`, `#Benchmarking`, `#Reasoning`, `#AI Evaluation`, `#Logic Puzzles`

---

<a id="item-7"></a>
## [Google Releases VeriHarness for Long-Horizon Task Verification](https://arxiv.org/abs/2610.00972v1) ⭐️ 8.0/10

Google has introduced VeriHarness, a framework that uses the same LLM that generated task rollouts to verify, challenge, and revise its own results based on environmental evidence. The project has released approximately 26,000 rollouts and demonstrated significant performance gains across five benchmarks. This framework addresses the common issue of error propagation in long-horizon tasks, where small mistakes compound over time. By enabling evidence-driven self-correction, it improves the reliability and accuracy of AI agents in complex, multi-step workflows. VeriHarness improves performance by selecting the best rollout and performing evidence-driven revisions, yielding gains of 6.2 points for Gemini 3.5 Flash and 6.4 points for Claude Opus. It operates within a standard test-time compute budget by comparing multiple independent rollouts per task.

telegram · zaihuapd · Oct 4, 13:32

**Background**: Long-horizon tasks require AI agents to maintain reasoning and tool use across many interdependent steps, which often leads to hallucinations or loss of coherence. Traditional agent harnesses often struggle with state tracking, allowing incorrect self-assessments to propagate throughout the task execution.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/google-research/veriharness">GitHub - google-research/veriharness</a></li>
<li><a href="https://www.emergentmind.com/topics/long-horizon-reasoning">Long-Horizon Reasoning in AI - emergentmind.com</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#Reasoning`, `#Verification`, `#AI Research`, `#Google`

---