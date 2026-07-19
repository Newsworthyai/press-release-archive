# ACE ROBOTICS Unveils Kairos 3.1 and Expands Its Embodied AI Stack from Data to Deployment at WAIC 2026

The launch combines a unified, action-oriented world model with Ambient Capture Engine 2.0, three commercial solutions and a new industry benchmark, connecting high-density data with real-world robotic operations.

 SHANGHAI, CHINA - [Media OutReach Newswire](https://www.media-outreach.com/) - 19 July 2026 - ACE ROBOTICS today unveiled Kairos 3.1, its latest action-oriented world model, alongside Ambient Capture Engine 2.0 and three commercial solutions spanning instant retail, hospitality and outdoor service scenarios.    The announcements were made at a forum ACE ROBOTICS organized during the 2026 World Artificial Intelligence Conference, convened around the theme of advancing physical AI from "understanding" to "execution." The event brought together economists, technology executives and embodied AI researchers to examine how general-purpose world models can move from laboratory research to industrial deployment.   The forum also marked the launch of PHYSICAL IQ, a unified benchmark for embodied physical intelligence. It was jointly initiated by the Shanghai Artificial Intelligence Association, the Shenzhen Loop Area Institute and the East China branch of the China Academy of Information and Communications Technology, with participation from more than 20 universities and industry partners.   Thomas J. Sargent, Nobel laureate in Economic Sciences, discussed the limitations of current intelligent systems in rare and previously unseen situations.   A world model built for the physical world   "In the digital world, a model error may result in a flawed image or paragraph. In the physical world, an incorrect action can have real consequences," said Wang Xiaogang, Chairman of ACE ROBOTICS. "Kairos 3.1 is built around a first-principles approach to embodied world models, helping robots act more reliably in complex and uncertain environments, and accelerating the arrival of physical AI's Kairos moment."   Kairos 3.1 is designed as a natively unified model that integrates generative, physical and cognitive intelligence within a single architecture, rather than combining separately developed capabilities.   Built on a hybrid Transformer architecture with a shared mixed-attention mechanism, it brings visual observations, language instructions, force and tactile signals, and policy trajectories into a unified latent space.   This supports an "understand, reason, execute and reflect" loop. The model can break down long-horizon tasks, simulate physical cause and effect across multiple scenarios, rank candidate actions, execute the selected strategy and evaluate the outcome for further adjustment.   At the core of its spatial understanding is ACE-BRAIN-0.5. ACE ROBOTICS said it has achieved state-of-the-art results across 12 public evaluations covering spatial understanding, navigation, manipulation and task-progress assessment, among publicly reported models as of July 2026.   In a household laundry scenario, for example, a robot can identify spatial relationships between objects, divide a task into more than a dozen steps and verify each stage in real time. If a failure occurs, it can identify the affected step and restart from that point rather than repeating the entire task.   For physical generation and reasoning, Kairos-HomeWorld supports whole-home scene generation and object interaction. It is built on 300,000 residential floor plans, 5,000 simulated home environments and 8,700 3D assets covering six categories of physical properties, designed to reflect common residential layouts in China.   The model can simulate multiple action trajectories in parallel and rank them based on predicted success and execution cost before sending instructions to a physical robot.   In internal testing, the Kairos 3.1 8B model achieved an inference latency of 125 milliseconds on the NVIDIA Jetson Thor platform at BF16 precision. Its in-house KairosRT computing engine supports real-time, on-device inference.   Kairos 3.1 also incorporates self-reflective iteration. When an action fails, the robot can evaluate the result and adjust its strategy. In one test, for example, it changed from a three-finger to a four-finger grasp after an unsuccessful attempt and subsequently completed the task.   From high-density data to continuous learning   ACE ROBOTICS also introduced what it calls the "Information-Density Law" for embodied models: the value of data is determined not only by its volume, but by whether it contains information capable of changing the outcome of an agent's actions.   ACE ROBOTICS classifies embodied data across five information-density levels, from L1 to L5. L1 and L2 data support foundational pre-training; L3 and L4 data remain focused on known tasks; and at L5, data incorporates three-dimensional force and tactile signals, failure-recovery trajectories and variables from open environments. The company says these higher-density forms of interaction data support stronger generalization, reflection and continuous learning.   Built on this principle, Ambient Capture Engine 2.0 is a human-centric system for capturing, processing and reusing high-density physical-interaction data.   ACE Ego Kit is a lightweight wireless wearable comprising head, hand and chest components. It includes the ACE Sense Glove, which offers sensitivity of 0.01 newtons and a joint-angle error of less than two degrees. The system can synchronize data from more than 20 heterogeneous sensors with a timing error of less than one millisecond.   ACE Data Engine is an automated data-production platform for continuous, high-precision annotation of long-horizon tasks. It incorporates ACE-ViDiHand, a generative 4D hand-motion-capture framework designed to track movements despite occlusion and rapid motion, which ACE ROBOTICS reports led across three public benchmarks (ARCTIC, HOT3D and HOI4D) as of July 2026. The company recorded a frame-level accuracy of 0.997 and up to a 4.8-fold improvement in motion smoothness.   ACE Ego Matrix standardizes embodied data across four dimensions: spatial coordinates, embodiment structure, action timing and data quality. It is designed to align data collected by different operators, devices and robot platforms for reuse across systems. ACE ROBOTICS has open-sourced the framework, which it says placed first on the RoboCase and RoboTwin leaderboards.   ACE ROBOTICS also announced the open release of ACE-Data-0, an L5 household-interaction dataset featuring complex physical tasks and high-precision annotations.   Three solutions moving into commercial operation   Building on its data infrastructure and Kairos world-model capabilities, ACE ROBOTICS introduced three standardized industry solutions designed for deployment within existing commercial workflows.   Xiaoman, its integrated fulfillment solution for instant retail, is paired with the new W1 fulfillment robot. The W1 has a robot-to-payload weight ratio of less than 2:1, force-control precision within one newton and a minimum required aisle width of 75 centimeters, making it suitable for high-density shelving environments. It is able to grasp both flexible packaging and rigid goods.   The solution connects robot hardware, world-model capabilities, motion control, product information, warehouse locations and order management. It supports lightweight deployment within days across flash-fulfillment warehouses, small-format stores and integrated warehouse-store setups. It has been deployed with customers including Sense MartGo, Kuaikeda and PetroChina convenience stores, using real order and shelf data to improve fulfillment performance. ACE ROBOTICS plans to deploy the solution across 1,000 retail locations over the next year and expand to approximately 10,000 stores within two years.   Xiaoxin addresses hotel-laundry operations, where ACE ROBOTICS estimates that approximately 80% of demand occurs at night.   The solution enables robots to handle collection, loading, unloading, washing, sorting and folding, with ironing capabilities planned for future versions. It is designed to reduce night-shift staffing pressure and improve operational consistency across non-standard hotel laundry environments.   Xiaotu is designed for autonomous operation in complex outdoor environments. Using a "one brain, many bodies" architecture, it applies a general-purpose intelligent brain (Agentic AI) across multiple quadruped robot platforms.   The system supports indoor and outdoor navigation, dynamic obstacle avoidance, autonomous charging, remote dispatch and multi-robot coordination. It has been deployed in visitor-guidance and interactive experience services at cultural-tourism events, including the Begonia Flower Festival in Tianjin.   Building an open embodied AI ecosystem   ACE ROBOTICS also announced a series of partnerships spanning infrastructure, computing and commercial deployment.   The company entered into a strategic collaboration with the Caohejing Development Zone to develop an embodied AI innovation platform.   In retail and fulfillment, ACE ROBOTICS announced collaborations with PetroChina, Kuaikeda and SenseTime Shanhui covering autonomous warehouse stores, front warehouses and unmanned retail environments.   To support the computing requirements of world-model development, ACE ROBOTICS launched the World Model Cloud Ecosystem initiative with Baidu AI Cloud, Alibaba Cloud, Huawei Cloud, Tencent Cloud and SenseCore AI Cloud.   By connecting high-density data, unified world models, robot platforms, commercial applications and shared evaluation standards, ACE ROBOTICS aims to support the transition of embodied AI from individual technical demonstrations to sustained operations in real-world environments.   Hashtag: #ACEROBOTICS[https://www.linkedin.com/company/acerobotics/posts/?feedView=all&viewAsMember=true%EF%BD%9C](https://www.linkedin.com/company/acerobotics/posts/?feedView=all&viewAsMember=true%EF%BD%9C)[https://x.com/ace_robotics](https://x.com/ace_robotics)The issuer is solely responsible for the content of this announcement.

About ACE ROBOTICS – Equipping robots with intelligent "brains" and engaging "souls"ACE ROBOTICS is a pioneering robotics company dedicated to advancing the field of embodied intelligence. Through breakthrough technological innovations and deep insights into embodied intelligence scenarios, we aim to empower robots with the ability to autonomously understand and explore the physical world, thereby accelerating their commercial implementation.   The company pioneered the ACE R&D paradigm and built a vision-based "environmental data engine, real-world cognition, embodied interaction generalization" technology chain. Using full spatiotemporal and multi-perspective environmental capture as its engine, along with Kairos 3.0 – China's first open-source and commercially applicable world model – plus the Embodied Foundation Model as its technical backbone, ACE ROBOTICS addresses core industry challenges such as data scarcity, common sense gaps, poor generalization, and limited versatility. Simultaneously, the company unveiled its flagship A1 Embodied Super Brain Module, accelerating the large-scale commercial deployment of embodied intelligence across diverse scenarios.   ACE ROBOTICS is both a technology pioneer and an ecosystem builder. Through strategic cooperation with top hardware manufacturers, cloud service providers, and vertical scenario partners, we have broken through the "model-hardware-scenario" industrial deadlock, providing standardized and customized solutions that are driving the development of China's embodied intelligence industry.

![](//track.media-outreach.com/index.php/WebView/476863/279561) 

---

[Original/Source Press Release](https://www.media-outreach.com/news/united-states/2026/07/19/476863/)
                    

[Newsramp.com TLDR](https://newsramp.com/curated-news/ace-robotics-launches-kairos-3-1-world-model-and-commercial-solutions/c613d1825424be81747840357858cbf1) 


Pickup - [https://advos.io/en](https://advos.io/en/ace-robotics-unveils-kairos-31-and-expands-embodied-ai-stack-at-waic-2026)

Pickup - [https://ai-industrynews.com](https://ai-industrynews.com/news/ace-robotics-launches-kairos-31-and-expands-embodied-ai-stack-at-waic-2026)

Pickup - [https://bayareametrowire.com](https://bayareametrowire.com/news/ace-robotics-unveils-kairos-31-and-expands-embodied-ai-stack-at-waic-2026)

Pickup - [https://burstable.news](https://burstable.news/news/ace-robotics-launches-kairos-31-and-expands-embodied-ai-stack-at-waic-2026)

Pickup - [https://platzennachrichten.de/nachrichten](https://platzennachrichten.de/nachrichten/ace-robotics-bringt-kairos-31-auf-den-markt-und-erweitert-den-embodied-ai-stack-auf-der-waic-2026)

Pickup - [https://estallarnoticias.com/noticias](https://estallarnoticias.com/noticias/ace-robotics-lanza-kairos-31-y-amplia-su-pila-de-ia-incorporada-en-waic-2026)

Pickup - [https://actueclair.com/actualites](https://actueclair.com/actualites/ace-robotics-lance-kairos-31-et-etend-sa-pile-ia-incarnee-a-la-waic-2026)

Pickup - [https://oestouro.com/noticias](https://oestouro.com/noticias/ace-robotics-lanca-kairos-31-e-expande-stack-de-ia-incorporada-na-waic-2026)

Pickup - [https://chicagometrowire.com](https://chicagometrowire.com/news/ace-robotics-launches-kairos-31-and-embodied-ai-stack-at-waic-2026-bridging-data-and-deployment)

Pickup - [https://dallasmetrowire.com](https://dallasmetrowire.com/news/ace-robotics-unveils-kairos-31-and-expands-embodied-ai-stack-at-waic-2026)

Pickup - [https://dcmetrowire.com](https://dcmetrowire.com/news/ace-robotics-unveils-kairos-31-and-expands-embodied-ai-stack-at-waic-2026)

Pickup - [https://fishervista.com/en](https://fishervista.com/en/ace-robotics-unveils-kairos-31-and-expands-embodied-ai-stack-at-waic-2026)

Pickup - [https://houstonmetrowire.com](https://houstonmetrowire.com/news/ace-robotics-launches-kairos-31-and-embodied-ai-stack-at-waic-2026-targeting-commercial-deployment)

Pickup - [https://lametrowire.com](https://lametrowire.com/news/ace-robotics-unveils-kairos-31-and-expands-embodied-ai-stack-at-waic-2026)

Pickup - [https://miamimetrowire.com](https://miamimetrowire.com/news/ace-robotics-unveils-kairos-31-and-expands-embodied-ai-stack-at-waic-2026)

Pickup - [https://news.newswriter.ai/curated-news](https://news.newswriter.ai/curated-news/ace-robotics-launches-kairos-31-world-model-and-expands-embodied-ai-stack-at-waic-2026)

Pickup - [https://nymetrowire.com](https://nymetrowire.com/news/ace-robotics-unveils-kairos-31-and-expands-embodied-ai-stack-at-waic-2026)

Pickup - [https://phillymetrowire.com](https://phillymetrowire.com/news/ace-robotics-unveils-kairos-31-and-expands-embodied-ai-stack-at-waic-2026)

Pickup - [https://phoenixmetrowire.com](https://phoenixmetrowire.com/news/ace-robotics-launches-kairos-31-world-model-and-commercial-solutions-at-waic-2026-advancing-embodied-ai-from-data-to-deployment)

Pickup - [https://sametrowire.com](https://sametrowire.com/news/ace-robotics-unveils-kairos-31-and-expands-embodied-ai-stack-from-data-to-deployment-at-waic-2026)

Pickup - [https://sdmetrowire.com](https://sdmetrowire.com/news/ace-robotics-unveils-kairos-31-and-expands-embodied-ai-stack-at-waic-2026)

Pickup - [https://news.trinzik.ai/frontier-tech-news](https://news.trinzik.ai/frontier-tech-news/ace-robotics-launches-kairos-31-world-model-and-three-commercial-solutions-advancing-physical-ai-from-understanding-to-execution)

Pickup - [https://www.newsworthy.ai/curated](https://www.newsworthy.ai/curated/ace-robotics-unveils-kairos-31-and-expands-embodied-ai-stack-at/202635629)

Pickup - [https://ai-industrynews.com](https://ai-industrynews.com/pr/mediaoutreach/ace-robotics-unveils-kairos-31-and-expands-its-embodied-ai-stack-from-data-to-deployment-at-waic-2026)

Pickup - [https://bayareametrowire.com](https://bayareametrowire.com/pr/mediaoutreach/ace-robotics-unveils-kairos-31-and-expands-its-embodied-ai-stack-from-data-to-deployment-at-waic-2026)

Pickup - [https://chicagometrowire.com](https://chicagometrowire.com/pr/mediaoutreach/ace-robotics-unveils-kairos-31-and-expands-its-embodied-ai-stack-from-data-to-deployment-at-waic-2026)

Pickup - [https://dallasmetrowire.com](https://dallasmetrowire.com/pr/mediaoutreach/ace-robotics-unveils-kairos-31-and-expands-its-embodied-ai-stack-from-data-to-deployment-at-waic-2026)

Pickup - [https://dcmetrowire.com](https://dcmetrowire.com/pr/mediaoutreach/ace-robotics-unveils-kairos-31-and-expands-its-embodied-ai-stack-from-data-to-deployment-at-waic-2026)

Pickup - [https://houstonmetrowire.com](https://houstonmetrowire.com/pr/mediaoutreach/ace-robotics-unveils-kairos-31-and-expands-its-embodied-ai-stack-from-data-to-deployment-at-waic-2026)

Pickup - [https://lametrowire.com](https://lametrowire.com/pr/mediaoutreach/ace-robotics-unveils-kairos-31-and-expands-its-embodied-ai-stack-from-data-to-deployment-at-waic-2026)

Pickup - [https://miamimetrowire.com](https://miamimetrowire.com/pr/mediaoutreach/ace-robotics-unveils-kairos-31-and-expands-its-embodied-ai-stack-from-data-to-deployment-at-waic-2026)

Pickup - [https://nymetrowire.com](https://nymetrowire.com/pr/mediaoutreach/ace-robotics-unveils-kairos-31-and-expands-its-embodied-ai-stack-from-data-to-deployment-at-waic-2026)

Pickup - [https://phillymetrowire.com](https://phillymetrowire.com/pr/mediaoutreach/ace-robotics-unveils-kairos-31-and-expands-its-embodied-ai-stack-from-data-to-deployment-at-waic-2026)

Pickup - [https://phoenixmetrowire.com](https://phoenixmetrowire.com/pr/mediaoutreach/ace-robotics-unveils-kairos-31-and-expands-its-embodied-ai-stack-from-data-to-deployment-at-waic-2026)

Pickup - [https://sametrowire.com](https://sametrowire.com/pr/mediaoutreach/ace-robotics-unveils-kairos-31-and-expands-its-embodied-ai-stack-from-data-to-deployment-at-waic-2026)

Pickup - [https://sdmetrowire.com](https://sdmetrowire.com/pr/mediaoutreach/ace-robotics-unveils-kairos-31-and-expands-its-embodied-ai-stack-from-data-to-deployment-at-waic-2026)
 

 



![Blockchain Registration](https://cdn.newsramp.app/mediaoutreach/qrcode/267/19/moonP70I.webp)