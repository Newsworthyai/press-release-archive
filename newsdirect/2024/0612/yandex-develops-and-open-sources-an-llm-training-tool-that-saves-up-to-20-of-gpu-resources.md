# Yandex develops and open-sources an LLM training tool that saves up to 20% of GPU resources

Yandex introduces YaFSDP, a method for faster and more efficient large language model (LLM) training. Potentially saving users hundreds of thousands of dollars per month. Available free.

Yandex, a global tech company, recently introduced YaFSDP, an open-source method for training large language models (LLMs). YaFSDP is currently the most effective publicly available tool for enhancing GPU communication and reducing memory usage in LLM training, offering a speedup of up to 26% compared to FSDP, depending on the architecture and number of parameters. Reducing the training time for LLMs through the use of YaFSDP can result in savings of up to 20% in GPU resources.

“Currently, we're actively experimenting with various model architectures and parameter sizes to expand YaFSDP’s versatility,” noted Mikhail Khruschev, a senior developer at Yandex and part of the team behind YaFSDP. “We are thrilled to share our developments in LLM training with the global ML community, contributing to increased accessibility and efficiency for researchers and developers worldwide.”

The case for YaFSDP

LLM training is a time-consuming and resource-intensive process. Machine learning engineers and companies that develop their own LLMs invest significant time and GPU resources — which equals money — in training these models. The larger the model, the greater the time and expenses associated with its training.

Yandex’s YaFSDP works by eliminating GPU communication inefficiencies, ensuring that training requires only necessary processor memory and making GPU interactions uninterrupted.

YaFSDP optimizes learning speed and performance, enabling AI developers worldwide to use less computing power and GPU resources when training their models. For instance, in a pre-training scenario involving a model with 70 billion parameters, using YaFSDP can save the resources of approximately 150 GPUs, which translates to roughly $0.5 to $1.5 million (depending on the virtual GPU provider or platform) in potential monthly savings.

YaFSDP’s training efficiency

YaFSDP, an enhanced version of FSDP, outperforms the FSDP method in the most communication-heavy stages of LLM training like pre-training, alignment, and fine-tuning. The final speedup shown by YaFSDP on Llama 2 and Llama 3 demonstrates significant improvements in training speed, reaching 21% and 26% on Llama 2 70B and Llama 3 70B respectively.

“YaFSDP has shown impressive results on models ranging from 13 to 70 billion parameters, with particularly strong performance in the 30 to 70 billion range,” said Mikhail Khruschev. “Currently, YaFSDP is best suited for widely-used open-source models based on the LLaMA architecture.”

YaFSDP isn’t Yandex’s first open-source tool. The company has previously shared several other tools that have become popular with the ML community, including:

* CatBoost, a high-performance library for gradient boosting on decision trees.
* YTsaurus, a big data platform for distributed storage and processing.
* AQLM, one of the most advanced quantization algorithms for extreme compression of large language models, developed jointly by Yandex Research, HSE University, IST Austria, and NeuralMagic.
* Petals, a library designed to simplify the process of training and fine-tuning LLMs, developed in a collaboration involving Yandex Research, HSE University, University of Washington, Hugging Face, ENS Paris-Saclay, and Yandex School of Data Analysis.

Accessing YaFSDP

YaFSDP is freely available on Github.

– – – – –

For Reference

During large language model (LLM) training, developers have to efficiently manage three primary resources: computing power, processor memory, and processor communications. YaFSDP conserves the first two, which helps to accelerate the LLM training process.

LLM training relies on numerous GPUs organized into clusters — arrays of interconnected graphics processors that can perform the vast number of calculations necessary to train models with billions of parameters. Distributing computations among processors within a cluster requires constant communication, which often becomes a "bottleneck", slowing the training process and resulting in inefficient use of computing power.

To overcome this bottleneck, Yandex developers created YaFSDP, a method that improves GPU communication and optimizes learning speed and performance. When combined with Yandex’s other performance-enhancing solutions, the method accelerated the training process by up to 45% for some of its models.

YaFSDP works by eliminating GPU communication inefficiencies, which leads to optimized network usage and reduced memory load. It ensures that training requires only necessary processor memory and makes GPU interactions uninterrupted, facilitating further optimizations like minimizing processor communication time. This leads to a significant enhancement in both performance and memory efficiency.

The YaFSDP method can be used effectively in transformer-based text generative models with multiple layers (multilayer perceptrons), mostly represented by LLaMA-like models. In a pre-training scenario involving a model with 70 billion parameters, using YaFSDP can save the resources of approximately 150 GPUs.

When compared to FSDP, the final speedup shown by YaFSDP on Llama 2 and Llama 3 demonstrates significant improvements in training efficiency.

Model

Number of GPUs

Input sequence length

Layers with activation checkpointing

Speedup

Llama 2 7B

64

2048

0

10.56%

Llama 2 7B

64

4096

0

2.54%

Llama 2 13B

128

2048

0

12.57%

Llama 2 13B

128

4096

0

3.45%

Llama 2 34B

256

2048

0

21.92%

Llama 2 34B

256

4096

5

8.12%

Llama 2 70B

256

2048

10

21.58%

Llama 2 70B

256

4096

50

6.44%

Llama 3 8B

64

2048

0

10.15%

Llama 3 8B

64

4096

0

7.98%

Llama 3 70B

256

2048

20

26.60%

About Yandex

Yandex is a global technology company that builds intelligent products and services powered by machine learning. The company’s goal is to help consumers and businesses better navigate the online and offline world. Since 1997, Yandex has been delivering world-class, locally relevant search and information services and has also developed market-leading on-demand transportation services, navigation products, and other mobile applications for millions of consumers across the globe.

Contact DetailsNettResults

Media Team

media@nettresults.com

View source version on newsdirect.com: https://newsdirect.com/news/yandex-develops-and-open-sources-an-llm-training-tool-that-saves-up-to-20-of-gpu-resources-781511400 

---

[Original/Source Press Release](https://newsdirect.com/news/yandex-develops-and-open-sources-an-llm-training-tool-that-saves-up-to-20-of-gpu-resources-781511400)
                    

[Newsramp.com TLDR](https://newsramp.com/curated-news/yandex-introduces-yafsdp-a-game-changer-for-llm-training/8d242b1c82748ef28796d852eacec332) 


Pickup - [advos.io](https://advos.io/en/yandex-introduces-yafsdp-a-revolutionary-tool-for-efficient-llm-training/20244079)
 



[Reddit Post](https://www.reddit.com/r/technology_press/comments/1de6ab0/yandex_introduces_yafsdp_a_gamechanger_for_llm/) 



![Blockchain Registration](https://cdn.newsramp.app/news-direct/qrcode/246/12/limezxsy.webp)