---
layout: default
title: "Horizon Summary: 2026-09-29 (EN)"
date: 2026-09-29
lang: en
---

> From 38 items, 14 important content pieces were selected

---

1. [Anthropic Releases Claude Sonnet 5.5 Model](#item-1) ⭐️ 9.0/10
2. [Functional Gradient Descent with Adaptive Representations](#item-2) ⭐️ 9.0/10
3. [Open-Source AI Engineering Course Releases Offline Books and Multi-Language Support](#item-3) ⭐️ 9.0/10
4. [SpaceX Starship Reaches Orbit and Deploys Satellites Before Early Return](#item-4) ⭐️ 9.0/10
5. [AMD to Acquire Fei-Fei Li's AI Startup World Labs for $8.2 Billion](#item-5) ⭐️ 9.0/10
6. [Pirating the Pirates: The Struggle for Digital Media Preservation](#item-6) ⭐️ 8.0/10
7. [Jeff: Jev-compatible 0.8B decision model for high-speed local classification](#item-7) ⭐️ 8.0/10
8. [Reverse-Engineering and Hijacking the PS5 RTMP Streaming Protocol](#item-8) ⭐️ 8.0/10
9. [Updated Google Maps Imagery Reveals Extensive Destruction in Rafah](#item-9) ⭐️ 8.0/10
10. [Analyzing Reddit's Astroturfing Problem Through Data-Driven Patterns](#item-10) ⭐️ 8.0/10
11. [It's Time to Investigate the AI Labs](#item-11) ⭐️ 8.0/10
12. [Qwen3-VL 8B Benchmarked Against Proprietary Models on Document Extraction](#item-12) ⭐️ 8.0/10
13. [Browser Demo of Clash Royale RL Environment Using REINFORCE Policy](#item-13) ⭐️ 8.0/10
14. [Star Catcher to Conduct First Orbital Laser Wireless Power Transmission Test](#item-14) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Anthropic Releases Claude Sonnet 5.5 Model](https://www.anthropic.com/claude-sonnet-5-5) ⭐️ 9.0/10

Anthropic has launched Claude Sonnet 5.5, the latest iteration of its mid-tier large language model, featuring significant improvements in coding performance and operational efficiency. This release provides developers with a more efficient, high-performance tool for complex coding tasks, further intensifying competition in the AI model market. Sonnet 5.5 shows notable gains in cyber capabilities and coding benchmarks, though some performance metrics may be influenced by differences in safety filter triggering compared to the flagship Opus model.

hackernews · D2OQZG8l5BI1S06 · Sep 28, 17:58 · [Discussion](https://news.ycombinator.com/item?id=49881850)

**Background**: Claude is a series of transformer-based large language models developed by Anthropic, designed for high-reasoning and coding-intensive tasks. Mid-tier models like Sonnet are typically positioned to balance cost, speed, and intelligence, serving as a middle ground between lightweight models and the most powerful flagship versions like Opus.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_(AI)">Claude (AI) - Wikipedia</a></li>
<li><a href="https://www.opslyft.com/blog/claude-architecture">Claude Architecture: How Anthropic's AI Models Are Built and Work</a></li>

</ul>
</details>

**Discussion**: Users are debating the practical necessity of Sonnet 5.5 given the efficiency of Opus 5.5, while noting its impressive performance in coding challenges like the PacMan bakeoff. Some users also pointed out that benchmark gaps between models can sometimes be attributed to different safety fallback rates.

**Tags**: `#AI`, `#LLM`, `#Anthropic`, `#Claude`, `#Machine Learning`

---

<a id="item-2"></a>
## [Functional Gradient Descent with Adaptive Representations](https://www.reddit.com/r/MachineLearning/comments/1wsejb7/functional_gradient_descent_with_adaptive/) ⭐️ 9.0/10

Researchers introduced a framework called 'Functional Gradient Descent with Adaptive Representations' that formalizes approximation schemes to ensure global convergence. This method allows functional gradient algorithms to be implemented effectively while outperforming traditional neural networks. This work addresses the convergence issues inherent in infinite-dimensional functional gradient approximations, potentially offering a more robust and efficient alternative to standard deep learning optimization. It represents a significant step forward in bridging the gap between theoretical functional optimization and practical machine learning applications. The framework adaptively refines gradient approximations to satisfy relative error conditions, which provably guarantees descent toward the global minimizer. In various experimental settings, these algorithms have demonstrated performance gains of up to an order of magnitude compared to standard neural networks.

reddit · r/MachineLearning · /u/dccsillag0 · Sep 28, 13:23

**Background**: Functional gradient descent is an optimization technique that operates in infinite-dimensional function spaces rather than finite-dimensional parameter spaces. Because computers cannot process infinite dimensions directly, these gradients must be approximated, which often leads to convergence errors if not handled correctly. This research provides a formal way to manage these approximations to ensure stable optimization.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2606.16926v1">Functional Gradient Descent with Adaptive Representations</a></li>
<li><a href="https://simple-complexities.github.io/optimization/functional/gradient/descent/2020/03/04/functional-gradient-descent.html">Functional Gradient Descent | Simple Complexities</a></li>

</ul>
</details>

**Discussion**: The community has shown significant interest in this NeurIPS-accepted work, with the author actively engaging with researchers to discuss the potential and implementation challenges of the framework.

**Tags**: `#Machine Learning`, `#NeurIPS`, `#Optimization`, `#Functional Gradient Descent`, `#Deep Learning`

---

<a id="item-3"></a>
## [Open-Source AI Engineering Course Releases Offline Books and Multi-Language Support](https://www.reddit.com/r/MachineLearning/comments/1ws6e9p/free_opensource_ai_engineering_course_where_you/) ⭐️ 9.0/10

The 'AI Engineering from Scratch' curriculum has released six EPUB and PDF volumes, expanded its interface to eight languages, and implemented automated testing for its 523 lessons. Users can now also integrate the course into AI coding agents using the 'npx skills' tool. This resource provides a high-quality, 'from scratch' educational path that demystifies complex AI concepts by avoiding high-level library abstractions. Its accessibility improvements make deep technical AI knowledge available to a global audience regardless of their internet connectivity or primary language. The curriculum covers 20 phases ranging from linear algebra and backpropagation to transformers and production serving, emphasizing a 'stdlib-first' coding approach. It is licensed under the MIT license, ensuring broad freedom for educational use and modification.

reddit · r/MachineLearning · /u/SeveralSeat2176 · Sep 28, 05:49

**Background**: Backpropagation is a fundamental algorithm used to train neural networks by calculating how network weights contribute to a loss function using the chain rule. 'Stdlib-first' programming refers to building functionality using only standard language libraries rather than relying on external, high-level frameworks. 'npx skills' is a tool that allows developers to add specialized capabilities or knowledge bases to AI coding agents.

<details><summary>References</summary>
<ul>
<li><a href="https://www.ibm.com/think/topics/backpropagation">What is Backpropagation? | IBM</a></li>
<li><a href="https://medium.com/@jacklandrin/skills-cli-guide-using-npx-skills-to-supercharge-your-ai-agents-38ddf3f0a826">Skills-CLI Guide: Using npx skills to Supercharge Your AI Agents 🚀 | by Bo Liu | Medium</a></li>
<li><a href="https://github.com/vercel-labs/skills">GitHub - vercel-labs/skills: The open agent skills tool - npx skills · GitHub</a></li>

</ul>
</details>

**Discussion**: The community has responded with strong enthusiasm, praising the 'from scratch' methodology for its pedagogical value and the practical utility of the new offline formats. Users particularly appreciate the effort to make complex AI engineering accessible through multi-language support.

**Tags**: `#machine learning`, `#ai engineering`, `#education`, `#open source`, `#curriculum`

---

<a id="item-4"></a>
## [SpaceX Starship Reaches Orbit and Deploys Satellites Before Early Return](https://apnews.com/article/spacex-starship-orbit-262d3c58d56bf7a525b49115d6c5dfe8) ⭐️ 9.0/10

SpaceX successfully launched its Starship vehicle into orbit from Starbase, Texas, and deployed 26 Starlink satellites. Despite an engine shutdown, the spacecraft completed its primary mission objectives before performing an early splashdown in the Pacific Ocean. This mission marks a critical milestone in validating Starship's orbital capabilities, which are essential for NASA's Artemis program to return humans to the Moon. It demonstrates the vehicle's potential to serve as a heavy-lift platform for future deep-space exploration. The flight experienced a premature engine shutdown, leading mission control to cut the planned 10-hour, 6-orbit mission short. The spacecraft successfully performed a controlled landing burn in the Pacific Ocean north of Hawaii.

telegram · zaihuapd · Sep 28, 16:06

**Background**: Starship is a fully reusable, two-stage super heavy-lift launch vehicle developed by SpaceX to enable human travel to the Moon and Mars. NASA has partnered with SpaceX to use a specialized version of the vehicle, known as Starship HLS, to transport astronauts between lunar orbit and the Moon's surface for the Artemis missions.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nasa.gov/humans-in-space/artemis/">Moon to Mars | NASA 's Artemis Program - NASA</a></li>
<li><a href="https://spaceflightnow.com/2026/09/28/starship-returns-to-earth-rocket-splashes-down-north-of-hawaii-after-three-hour-flight/">Starship returns to Earth; rocket splashes down north of Hawaii after three-hour flight – Spaceflight Now</a></li>

</ul>
</details>

**Discussion**: Observers noted the dramatic fireball during the splashdown, contrasting it with previous softer landings. There is significant interest in how the engine failure will impact the timeline for future flight tests.

**Tags**: `#SpaceX`, `#Starship`, `#Aerospace`, `#Space Exploration`, `#Satellite Technology`

---

<a id="item-5"></a>
## [AMD to Acquire Fei-Fei Li's AI Startup World Labs for $8.2 Billion](https://ir.amd.com/news-events/press-releases/detail/1299/amd-to-acquire-world-labs-to-advance-the-future-of-ai-compute) ⭐️ 9.0/10

AMD has announced the acquisition of World Labs, an AI startup founded by Fei-Fei Li, for $8.2 billion. As part of the deal, Fei-Fei Li will join AMD as Executive Vice President and Chief Scientist. This acquisition signals a strategic shift for AMD to integrate advanced world model technology with its high-performance computing hardware. It positions AMD to better compete in the next wave of AI, which focuses on spatial intelligence and physical world simulation rather than just language processing. World Labs specializes in 'world models' that enable AI to perceive, reason about, and simulate 3D physical environments. The transaction is expected to close by the end of the year, pending regulatory approval.

telegram · zaihuapd · Sep 29, 03:59

**Background**: World models represent a shift from traditional LLMs, which primarily process text and code, toward systems that understand the rules of the physical world. By building a 'simulation layer,' these models allow AI to interact with 3D space, which is essential for advancements in robotics and autonomous systems. Fei-Fei Li, a pioneer in computer vision, founded World Labs to advance this 'spatial intelligence.'

<details><summary>References</summary>
<ul>
<li><a href="https://www.worldlabs.ai/blog">Research & Insights | World Labs</a></li>
<li><a href="https://www.linkedin.com/pulse/fei-fei-lis-world-labs-building-missing-simulation-layer-steven-wang-5fhzf">Fei - Fei Li 's World Labs Is Building the Missing Simulation Layer...</a></li>

</ul>
</details>

**Tags**: `#AMD`, `#World Labs`, `#Fei-Fei Li`, `#AI Acquisition`, `#World Models`

---

<a id="item-6"></a>
## [Pirating the Pirates: The Struggle for Digital Media Preservation](https://mubi.com/en/notebook/posts/pirating-the-pirates) ⭐️ 8.0/10

The article explores the critical challenges of preserving digital media, highlighting how unauthorized edits and rigid copyright laws threaten the integrity of historical works. It examines the tension between official digital releases and the efforts of fan preservationists to maintain access to original content. This issue is significant because it highlights the risk of a 'digital dark age' where cultural history is lost due to bit rot or intentional corporate efforts to restrict access to original versions of media. It underscores the vital role of preservationists in maintaining the authenticity of our shared digital heritage. The discussion emphasizes that legal frameworks like the DMCA often hinder preservation efforts, while fan-led initiatives on torrent sites frequently serve as the primary archive for media that studios have altered or withdrawn. Technical challenges like bit rot further complicate the long-term survival of digital files.

hackernews · piotrgrabowski · Sep 28, 15:54 · [Discussion](https://news.ycombinator.com/item?id=49880036)

**Background**: Digital media preservation faces two main threats: 'bit rot,' which is the gradual corruption of data on storage media, and legal restrictions that prevent the archiving of proprietary formats. The DMCA's anti-circumvention provisions often make it illegal for libraries or individuals to bypass copy protection even for the purpose of long-term preservation.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Digital_Millennium_Copyright_Act">Digital Millennium Copyright Act - Wikipedia</a></li>
<li><a href="https://clinic.cyber.harvard.edu/2018/10/26/a-victory-for-software-preservation-dmca-exemption-granted-for-spn/">A Victory for Software Preservation: DMCA Exemption Granted for SPN</a></li>
<li><a href="https://www.datacore.com/glossary/bit-rot/">Understanding Bit Rot : Causes, Prevention & Protection | DataCore</a></li>

</ul>
</details>

**Discussion**: The community expresses frustration with studios removing access to older media and notes that organizations like the EFF are actively lobbying for DMCA exemptions to support preservation. Commenters also highlight the irony of using 'pirate' methods to save cultural history and criticize the frequent, unauthorized editing of classic films by rights holders.

**Tags**: `#digital-preservation`, `#copyright-law`, `#media-history`, `#dmca`, `#culture`

---

<a id="item-7"></a>
## [Jeff: Jev-compatible 0.8B decision model for high-speed local classification](https://github.com/firelex/jeff) ⭐️ 8.0/10

Jeff is an open-source, 0.8B parameter decision model that is compatible with the Jev API, enabling local classification tasks with approximately 30ms latency. It provides a lightweight alternative to hosted AI services by running directly on consumer hardware. This project highlights a growing shift toward using small, specialized models for deterministic tasks like classification, potentially reducing reliance on expensive, large-scale LLMs. It challenges the necessity of massive parameter counts for common business automation use cases. The model is optimized for speed, achieving inference times around 30ms, though some users have reported lower accuracy compared to proprietary Jev implementations. It focuses on single-pass decision-making rather than generative text output.

hackernews · firelex · Sep 28, 20:23 · [Discussion](https://news.ycombinator.com/item?id=49883844)

**Background**: Jev is a framework by TypeSafe AI designed for 'System One' models that make deterministic, software-native decisions rather than generating conversational text. Decision models are specialized to perform a single forward pass to select an option from a predefined schema, making them highly efficient for automation tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://typesafe.ai/blog/introducing-system-one-models-and-jev">Introducing System One Models & Jev - TypeSafe AI Blog</a></li>
<li><a href="https://huggingface.co/mghafiri/qwen3.5-0.8B-decision-model">mghafiri/qwen3.5- 0 . 8 B - decision - model · Hugging Face</a></li>
<li><a href="https://www.orcarouter.ai/blog/intern-decision-0-8b-what-we-know">Intern- Decision - 0 . 8 B : InternLM's Quiet Hugging Face Drop</a></li>

</ul>
</details>

**Discussion**: The community is debating the trade-offs between local efficiency and accuracy, with some users questioning the transparency of the Jev architecture. Others are exploring creative use cases like game automation, while some express skepticism about replacing LLMs with smaller models for critical tasks.

**Tags**: `#machine-learning`, `#llm-optimization`, `#edge-ai`, `#classification`, `#open-source`

---

<a id="item-8"></a>
## [Reverse-Engineering and Hijacking the PS5 RTMP Streaming Protocol](https://yashgarg.dev/posts/hijacking-ps5-rtmp-stream/) ⭐️ 8.0/10

A researcher successfully reverse-engineered the PlayStation 5's internal RTMP streaming traffic, allowing for the interception and modification of the stream to enable custom overlays. This process demonstrates how to manipulate the console's outbound video data before it reaches its final destination. This discovery highlights significant security concerns regarding the use of unencrypted legacy protocols in modern consumer hardware. It exposes potential vulnerabilities where sensitive data or stream integrity could be compromised by third parties. The analysis focuses on the PS5's reliance on the aging RTMP protocol for broadcasting, which lacks modern encryption standards. By performing a man-in-the-middle (MITM) approach, the author was able to redirect and inject content into the stream.

hackernews · ibobev · Sep 28, 15:35 · [Discussion](https://news.ycombinator.com/item?id=49879702)

**Background**: RTMP (Real-Time Messaging Protocol) is a legacy communication protocol originally developed for streaming audio, video, and data over the internet. While widely used in the early days of web streaming, it is often considered insecure by modern standards because it frequently transmits data in plain text without robust encryption. Reverse engineering involves analyzing a system to understand its internal workings, often to identify undocumented features or security flaws.

<details><summary>References</summary>
<ul>
<li><a href="https://upstream.so/blog/what-is-rtmp-a-rtmp-youtube-com-live2/">rtmp ://a. rtmp .youtube.com/live2: YouTube RTMP for Creators</a></li>
<li><a href="https://developers.google.com/youtube/v3/live/guides/ingestion-protocol-comparison">YouTube Live Streaming Ingestion Protocol Comparison</a></li>
<li><a href="https://devtechnosys.ae/blog/video-streaming-protocols/">Video Streaming Protocols : HLS, DASH, WebRTC & More</a></li>

</ul>
</details>

**Discussion**: The community expressed surprise that a modern console still utilizes an unencrypted legacy protocol like RTMP, raising concerns about potential security exploits. Some users noted that this technique mirrors how third-party services like Lightstream previously enabled console overlays, while others shared alternative hardware-based methods for capturing video.

**Tags**: `#reverse-engineering`, `#security`, `#ps5`, `#rtmp`, `#networking`

---

<a id="item-9"></a>
## [Updated Google Maps Imagery Reveals Extensive Destruction in Rafah](https://twitter.com/AliAbunimah/status/2103890594137309425) ⭐️ 8.0/10

Recent updates to Google Maps satellite imagery now display the widespread destruction of buildings and infrastructure in the city of Rafah. Users can compare these current aerial views with historical data to visualize the extent of the damage. This update provides verifiable visual evidence of urban warfare, allowing the public to assess the impact of the ongoing conflict. It serves as a digital record of the humanitarian and structural consequences of the military operations in the region. Users can access the 'historical imagery' feature in Google Earth to view the city's state prior to the destruction. The imagery highlights the contrast between former functional urban areas and the current state of rubble.

hackernews · slowin · Sep 28, 15:32 · [Discussion](https://news.ycombinator.com/item?id=49879645)

**Background**: Rafah is a city located in the southern Gaza Strip that has been a focal point of recent military conflict. Satellite imagery is frequently used by researchers, journalists, and the public to document changes in conflict zones where ground access is restricted.

**Discussion**: The community expressed deep concern, noting the haunting contrast between previous Street View images of daily life and the current aerial views of destruction. Some users analyzed the patterns of damage, while others provided tools for comparing historical imagery with current conditions.

**Tags**: `#geopolitics`, `#satellite-imagery`, `#conflict-analysis`, `#google-maps`

---

<a id="item-10"></a>
## [Analyzing Reddit's Astroturfing Problem Through Data-Driven Patterns](https://www.petervijeh.com/projects/reddit-astroturf) ⭐️ 8.0/10

The analysis examines patterns of coordinated inauthentic behavior on Reddit, identifying how bot networks and manipulated accounts attempt to influence public opinion. It highlights specific indicators of manipulation, such as account history patterns and coordinated posting behaviors. Understanding these manipulation tactics is crucial for maintaining the integrity of online discourse and protecting users from deceptive marketing or political influence. It highlights the ongoing challenge platforms face in distinguishing between genuine community engagement and manufactured consensus. The study notes that traditional indicators of bot accounts, such as low karma or young account age, are becoming less reliable as sophisticated networks now build credibility by posting in diverse subreddits. Detection is further complicated by the 'toupee fallacy,' where users assume they can spot all manipulation because they can identify the most obvious cases.

hackernews · p-s-v · Sep 28, 13:30 · [Discussion](https://news.ycombinator.com/item?id=49877678)

**Background**: Astroturfing is a deceptive practice where organizations or individuals create the illusion of grassroots support for a product, cause, or political stance. On social media platforms like Reddit, this often involves coordinated groups of accounts working together to upvote, comment, or steer conversations to manipulate public perception.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Astroturfing">Astroturfing - Wikipedia</a></li>
<li><a href="https://www.xpoz.ai/blog/guides/detecting-coordinated-inauthentic-behavior-technical-guide/">Detect Coordinated Inauthentic Behavior : Guide | Xpoz Blog</a></li>

</ul>
</details>

**Discussion**: The community expressed skepticism regarding current detection methods, noting that moderation bias and the evolution of bot behavior make it difficult to distinguish authentic users from malicious actors. Some users also criticized the use of AI-generated prose in the report, arguing it obscures the clarity of the underlying data.

**Tags**: `#Reddit`, `#Data Analysis`, `#Social Media`, `#Astroturfing`, `#Bot Detection`

---

<a id="item-11"></a>
## [It's Time to Investigate the AI Labs](https://calnewport.com/its-time-to-investigate-the-ai-labs/) ⭐️ 8.0/10

Cal Newport argues that the focus of AI governance should shift from abstract existential risk theories to concrete investigations into the operational practices and accountability of major AI laboratories. This shift addresses the need for practical oversight of powerful AI companies, ensuring that corporate behavior and safety protocols are held to the same standards as other high-stakes industries. The proposal emphasizes that AI systems are essentially matrix math, and the real danger lies in how these systems are integrated into critical infrastructure and the lack of transparency in corporate decision-making.

hackernews · ibobev · Sep 28, 19:53 · [Discussion](https://news.ycombinator.com/item?id=49883471)

**Background**: AI existential risk refers to the hypothesis that advanced AI could cause human extinction or irreversible global catastrophe. Debates often pit those concerned with long-term alignment against skeptics who argue that AI lacks intrinsic desires. Recent discussions have increasingly focused on whether current regulatory frameworks are sufficient to manage the rapid development of AI agents.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AI_existential_risk">AI existential risk</a></li>
<li><a href="https://www.techtarget.com/searchEnterpriseAI/tip/Build-accountability-into-AI-to-drive-business-value/">Build accountability into AI to drive business value | TechTarget</a></li>

</ul>
</details>

**Discussion**: The community generally supports moving away from vague existential fears toward specific operational accountability. Some users compare AI agents to corporate entities that require strict oversight, while others express concern over the security risks of granting AI agents root access to personal or critical systems.

**Tags**: `#AI Governance`, `#AI Ethics`, `#Corporate Accountability`, `#AI Policy`

---

<a id="item-12"></a>
## [Qwen3-VL 8B Benchmarked Against Proprietary Models on Document Extraction](https://www.reddit.com/r/MachineLearning/comments/1wsbqni/qwen3vl_8b_on_a_laptop_vs_opus_55_sonnet_5_gpt56/) ⭐️ 8.0/10

A comparative benchmark evaluated the Qwen3-VL 8B model against Claude Opus 5.5, Sonnet 5, and GPT-5.6 on 137 diverse documents, including IRS forms and receipts. The results show Qwen3-VL 8B significantly outperforms GPT-5.6 on specific tax forms while struggling with regional date formats and long-context contract processing. This study highlights the practical viability of lightweight local models for specialized document extraction tasks, demonstrating that smaller models can outperform massive proprietary ones in specific domains. It provides valuable insights for developers looking to balance performance, cost, and data privacy in document AI workflows. Qwen3-VL 8B achieved a 59% success rate on the test set, compared to 57% for GPT-5.6, though it failed on Indian date formats and long-context contracts. The author noted that using the 'instruct' variant is critical, as the 'thinking' variant consumes all tokens on long documents without producing output.

reddit · r/MachineLearning · /u/NegotiationKey7184 · Sep 28, 11:11

**Background**: Document AI involves using machine learning to extract structured data from unstructured sources like scanned receipts, invoices, and legal contracts. Datasets like CORD, SROIE, and CUAD are standard benchmarks used to train and evaluate models on their ability to recognize and parse these specific document types.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/clovaai/cord">GitHub - clovaai/ cord : CORD : A Consolidated Receipt Dataset for...</a></li>
<li><a href="https://www.kaggle.com/datasets/urbikn/sroie-datasetv2">A grouped and organized dataset of the original ICDAR 2019 SROIE ...</a></li>
<li><a href="https://www.atticusprojectai.org/cuad/">CUAD Dataset | The Atticus Project</a></li>

</ul>
</details>

**Discussion**: The community expressed significant interest in the methodology, particularly regarding the use of non-public IRS forms to prevent data contamination. Discussions also focused on the model's specific failure modes, such as date format confusion and the limitations of 'thinking' models in long-context scenarios.

**Tags**: `#LLM`, `#Document AI`, `#Benchmarking`, `#Qwen`, `#Local AI`

---

<a id="item-13"></a>
## [Browser Demo of Clash Royale RL Environment Using REINFORCE Policy](https://www.reddit.com/r/MachineLearning/comments/1wsfkwg/browser_demo_of_our_clash_royale_rl_environment_a/) ⭐️ 8.0/10

An interactive browser-based demo has been released featuring a 5.6k-parameter REINFORCE policy trained to optimize defensive unit placement in a Clash Royale simulator. The project utilizes a C++ engine compiled to WebAssembly to perform high-performance simulations directly within the browser. This project provides a transparent, visual way to understand reinforcement learning training loops and policy optimization. By using WebAssembly, it demonstrates how complex game simulations can be effectively ported to the web for educational and research purposes. The policy uses hand-written gradients in JavaScript and employs an annealed entropy bonus to improve exploration. The demo compares the learned agent's performance against a brute-force optimum, revealing specific challenges in local optima for certain unit pairings.

reddit · r/MachineLearning · /u/Potential-Barber8658 · Sep 28, 14:06

**Background**: REINFORCE is a fundamental policy-gradient reinforcement learning algorithm that updates policy parameters based on sampled trajectories. WebAssembly (Wasm) is a binary instruction format that allows code written in languages like C++ to run in web browsers at near-native speeds. Entropy bonuses are often used in RL to encourage exploration by preventing the policy from prematurely converging to a single action.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/analytics-vidhya/reinforce-algorithm-taking-baby-steps-in-reinforcement-learning-ebb1048419e9">REINFORCE Algorithm : Taking baby steps in reinforcement learning</a></li>
<li><a href="https://www.youtube.com/watch?v=xLopnbhF9KA">Porting Libraries to WebAssembly - C++ on the Web Browser</a></li>
<li><a href="https://www.emergentmind.com/topics/entropy-balanced-policy-optimization">Entropy -Balanced Policy Optimization</a></li>

</ul>
</details>

**Discussion**: The community has shown interest in the technical implementation, particularly the use of WebAssembly for game simulation and the transparency of the training process. Users appreciate the ability to visualize the learning gap against a brute-force baseline.

**Tags**: `#Reinforcement Learning`, `#WebAssembly`, `#Game AI`, `#Simulation`, `#JavaScript`

---

<a id="item-14"></a>
## [Star Catcher to Conduct First Orbital Laser Wireless Power Transmission Test](https://www.wired.com/story/space-lasers-are-about-to-get-their-first-real-test-generating-energy/) ⭐️ 8.0/10

Startup Star Catcher is preparing to launch a prototype device via a SpaceX rocket to demonstrate laser-based energy transmission between two independent spacecraft in orbit. This mission marks the first attempt to beam power from an energy node to a separate satellite in space. This technology could revolutionize satellite energy management by reducing reliance on heavy onboard batteries and enabling high-power operations for future space-based data centers. It represents a critical step toward building a functional power grid infrastructure in space. The system uses an 'energy node' to collect and focus sunlight, converting it into a laser beam directed at the solar panels of target satellites. The company aims to provide spacecraft with five to ten times the power they could generate independently.

telegram · zaihuapd · Sep 28, 12:21

**Background**: Wireless power transmission via laser involves converting electrical energy into a laser beam that travels through space to a receiver, where it is converted back into electricity. This concept is considered a key solution for overcoming the power limitations of small satellites and supporting advanced missions that require significant energy. Star Catcher is positioning itself as a provider of space-based energy infrastructure to boost satellite uptime and capabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://www.star-catcher.com/">Star Catcher</a></li>
<li><a href="https://www.factoriesinspace.com/star-catcher">Star Catcher - Factories in Space</a></li>
<li><a href="https://finance.yahoo.com/energy/articles/star-catcher-prepares-orbital-power-120000046.html">Star Catcher Prepares Orbital Power Beaming Demonstration For...</a></li>

</ul>
</details>

**Tags**: `#Space Technology`, `#Wireless Power Transfer`, `#Aerospace Engineering`, `#Energy Systems`

---