# Research Papers 

## Focus Areas: LLMs, Generative AI, ML

| **Publication**  | **Links** |
| ------------- | ------------- |
| **The Era of 1-bit LLMs** -  This study introduces a 1-bit LLM variant called BitNetb1.58, where every single parameter (weight) of the LLM is ternary {-1, 0, 1}. BitNetb1.58 matches the full-precision Transformer LLM in terms of model size and training tokens, achieving similar perplexity and end-task performance. However, it proves significantly more cost-effective in terms of latency, memory usage, throughput, and energy consumption. Notably, the 1.58-bit LLM establishes a new scaling law and training approach for creating high-performance and cost-effective LLMs. It also opens the possibility of a new computation paradigm and the design of hardware optimized specifically for 1-bit LLMs. | [Publication](https://arxiv.org/abs/2402.17764)|
| **AtP*** -  Activation Patching computes causal attributions of behavior to model components, but its exhaustive application is costly, especially for state-of-the-art Large Language Models (LLMs). Attribution Patching (AtP), a faster gradient-based approximation to Activation Patching, revealing two significant failure modes that result in notable false negatives. To address these, a variant with modifications aimed at mitigating these failure modes while maintaining scalability. Through systematic study AtP outperforms alternative methods for faster activation patching, and AtP* offers further substantial improvement, supplemented by a method to bound the probability of remaining false negatives in AtP* estimates.| [Publication](https://arxiv.org/abs/2403.00745)|
| **LLMs on Tabular Data** -  Recent advancements in large language modeling have enabled extensive exploration of their application in various tabular data modeling tasks. However, there's a lack of comprehensive reviews summarizing key techniques, metrics, datasets, and methodologies in this domain. This survey aims to address this gap by consolidating recent progress, identifying strengths, limitations, and future research directions. It provides valuable insights and references to empower researchers in effectively navigating and tackling challenges in this rapidly evolving field.| [Publication](https://arxiv.org/abs/2402.17944)|
| **LargeLanguageModelsforDataAnnotation:ASurvey** -  explores the potential of advanced Large Language Models (LLMs) like GPT-4 in automating and revolutionizing data annotation, a labor-intensive process crucial for improving machine learning models. It uniquely focuses on LLMs' utility for data annotation, covering methodologies, assessing LLM-generated annotations, and learning strategies. It provides insights into challenges and limitations while aiming to guide researchers and practitioners in leveraging LLMs for enhanced data annotation, fostering advancements in this critical domain.| [Publication](https://arxiv.org/abs/2402.13446)|
|**LoRA+** - demonstrated that the Low Rank Adaptation (LoRA) method, leads to suboptimal fine-tuning for models with large width (embedding dimension) due to the identical learning rate used for adapter matrices A and B. By employing scaling arguments for large width networks, it's illustrated that this uniform learning rate impedes efficient feature learning. To address this, the proposed algorithm, LoRA+, adjusts learning rates for the adapter matrices A and B, resulting in improved performance (1-2% enhancements) and fine-tuning speed (up to ∼ 2X SpeedUp) in extensive experiments, without increased computational cost compared to LoRA. | [Publication](https://arxiv.org/abs/2402.12354)|
|**When is Tree Search Useful for LLM Planning** - explores how large language models (LLMs) approach multi-step problems within a language agent framework, utilizing generators, discriminators, and planning methods. It evaluates two advanced planning methods, iterative correction and tree search, alongside a simpler re-ranking method, across tasks like text-to-SQL parsing and mathematical reasoning. Findings indicate that advanced planning methods require discriminators with at least 90% accuracy to significantly surpass re-ranking. However, current LLMs' discrimination abilities fall short of this threshold, hindering the effectiveness of advanced planning methods. Moreover, when using LLM-based discriminators, balancing accuracy and efficiency proves challenging, as seen with tree search, which, despite being significantly slower, offers minimal performance gains compared to other methods, limiting its practical utility. | [Publication](https://arxiv.org/abs/2402.10890) |
