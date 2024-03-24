# :star: :bookmark: awesome-generative-ai-guide
Generative AI is experiencing rapid growth, and this repository serves as a comprehensive hub for updates on generative AI research, interview materials, notebooks, and more! 

Explore the following resources:

1. [Monthly Best GenAI Papers List](https://github.com/aishwaryanr/awesome-generative-ai-guide?tab=readme-ov-file#star-best-genai-papers-list-january-2024)
2. [GenAI Interview Resources](https://github.com/aishwaryanr/awesome-generative-ai-guide?tab=readme-ov-file#computer-interview-prep)
3. [Applied LLMs Mastery 2024 (created by Aishwarya Naresh Reganti) course material](https://github.com/aishwaryanr/awesome-generative-ai-guide?tab=readme-ov-file#ongoing-applied-llms-mastery-2024)
4. [List of all GenAI-related free courses (over 30 already listed)](https://github.com/aishwaryanr/awesome-generative-ai-guide?tab=readme-ov-file#book-list-of-free-genai-courses)
5. [List of code repositories/notebooks for developing generative AI applications](https://github.com/aishwaryanr/awesome-generative-ai-guide?tab=readme-ov-file#notebook-code-notebooks)

We'll be updating this repository regularly, so keep an eye out for the latest additions!






Happy Learning!

---
## :speaker: Announcements
- Applied LLMs Mastery full course content has been released!!! ([Click Here](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/free_courses/Applied_LLMs_Mastery_2024))
- 5-day roadmap to learn LLM foundations out now! ([Click Here](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/resources/genai_roadmap.md))
- 60 Common GenAI Interview Questions out now! ([Click Here](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/interview_prep/60_gen_ai_questions.md))
- ICLR 2024 paper summaries ([Click Here](https://areganti.notion.site/06f0d4fe46a94d62bff2ae001cfec22c?v=d501ca62e4b745768385d698f173ae14))
- List of free GenAI courses ([Click Here](https://github.com/aishwaryanr/awesome-generative-ai-guide#book-list-of-free-genai-courses))




---

## :star: Best GenAI Papers List (February 2024)
*Updated at the end of every month

| Date        | Name                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Topics                         |
|-------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------|
| 28 Feb 2024 | [Sora: A Review on Background, Technology, Limitations, and Opportunities of Large Vision Models](https://arxiv.org/pdf/2402.17177.pdf) | The paper provides a thorough analysis of Sora, a text-to-video generative AI model launched by OpenAI. It examines Sora's evolution, underlying technologies, diverse applications across industries, and potential impact on creativity and productivity. Challenges like safety and bias in video generation are discussed, along with future directions for Sora and similar models, envisioning enhanced human-AI collaboration and innovation in video production. Note that this paper is not written by the creators of Sora, it is reverse engineered by a group of researchers. | Multimodal Models |
| 28 Feb 2024 | [OpenCodeInterpreter: Integrating Code Generation with Execution and Refinement](https://arxiv.org/pdf/2402.14658.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | The paper introduces OpenCodeInterpreter, a family of open-source code systems aimed at addressing the limitations of existing open-source models in code generation by incorporating execution capabilities and iterative refinement similar to advanced systems like the GPT-4 Code Interpreter. Leveraging the CodeFeedback dataset, which includes 68K multi-turn interactions, OpenCodeInterpreter integrates execution and human feedback for dynamic code refinement. Evaluation across key benchmarks demonstrates exceptional performance, with OpenCodeInterpreter33B achieving close accuracy to GPT-4 on HumanEval and MBPP benchmarks, effectively bridging the gap between open-source and proprietary code generation systems.                                                           | Task Specific LLMs, Evaluation |
| 27 Feb 2024 | [Evaluating Very Long-Term Conversational Memory of LLM Agents](https://arxiv.org/pdf/2402.17753.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | This paper introduces a machine-human pipeline to generate high-quality, very long-term dialogues, spanning up to 35 sessions, using large language models and retrieval augmented generation techniques. The conversations are grounded on personas and temporal event graphs, with each agent capable of sharing and reacting to images. The resulting dataset, LOCOMO, comprises conversations with 300 turns on average. Evaluation benchmarks measure long-term memory in models, revealing challenges for LLMs in understanding lengthy conversations and comprehending long-range temporal dynamics. While strategies like long-context LLMs or RAG show improvements, models still lag behind human performance.                                                                                | RAG, Benchmark, Long Context   |
| 27 Feb 2024 | [When Scaling Meets LLM Finetuning: The Effect of Data, Model, and Finetuning Method](https://arxiv.org/pdf/2402.17193.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | This paper investigates the scaling properties of different finetuning methods for LLMs. Through systematic experiments, it explores the impact of various scaling factors, including model size, pretraining data size, and finetuning data size, on finetuning performance. Results suggest a power-based multiplicative joint scaling law between finetuning data size and other factors, with LLM model scaling offering more benefits than pretraining data scaling. Additionally, the optimal finetuning method varies depending on the task and finetuning data. These findings aim to enhance understanding and development of LLM finetuning methods.                                                                                                                                          | Fine-Tuning                    |
| 27 Feb 2024 | [The Era of 1-bit LLMs:](https://arxiv.org/pdf/2402.17764.pdf) [All Large Language Models are in 1.58 Bits](https://arxiv.org/pdf/2402.17764.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | This paper introduces BitNet b1.58, a variant where every parameter is ternary {-1, 0, 1}, matching full-precision Transformer LLMs in both perplexity and end-task performance while offering significant cost-effectiveness. This 1.58-bit LLM sets a new standard for high-performance, cost-effective models and opens opportunities for new computation paradigms and hardware designs optimized for 1-bit LLMs.                                                                                                                                                                                                                                                                                                                                                                                   | Cost Effective LLMs            |
| 26 Feb 2024 | [Rainbow Teaming: Open-Ended Generation of Diverse Adversarial Prompts](https://arxiv.org/pdf/2402.16822.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | The paper introduces Rainbow Teaming, a method for diversely generating adversarial prompts to enhance the robustness of LLMs. By framing prompt generation as a quality-diversity problem, it uncovers vulnerabilities across various domains, including safety, question answering, and cybersecurity. Additionally, fine-tuning LLMs on synthetic data produced by Rainbow Teaming improves safety without compromising general capabilities, offering a path to open-ended self-improvement.                                                                                                                                                                                                                                                                                                        | Red-Teaming                    |
| 26 Feb 2024 | [Do Large Language Models Latently Perform Multi-Hop Reasoning?](https://arxiv.org/pdf/2402.16837.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | The study investigates whether LLMs engage in latent multi-hop reasoning when processing complex prompts. By analyzing individual hops and their co-occurrence, the research examines how LLMs identify and utilize bridge entities to complete prompts. Results show strong evidence of latent multi-hop reasoning in certain relation types, with the reasoning pathway used in over 80% of prompts. However, the utilization varies contextually, and while evidence for the first hop is substantial, it's more moderate for the second hop. Additionally, there's a scaling trend with increasing model size for the first hop but not the second, indicating potential challenges and opportunities for future LLM development.                                                                   | Evaluation                     |
| 26 Feb 2024 | [Revisiting REINFORCE Style Optimization for Learning from Human Feedback in LLMs](https://arxiv.org/pdf/2402.14740.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | The paper discusses Reinforcement Learning from Human Feedback (RLHF) as vital for large language model LLM alignment. While Proximal Policy Optimization (PPO) is commonly used, its high computational cost and hyperparameter sensitivity pose challenges. The study proposes simpler REINFORCE-style optimization variants for RLHF, showing superior performance compared to PPO and other methods like DPO and RAFT. It suggests that adapting to LLM alignment characteristics allows for efficient online RL optimization.                                                                                                                                                                                                                                                                      | Instruction Tuning             |
| 23 Feb 2024 | [A Human-Inspired Reading Agent with Gist Memory of Very Long Contexts](https://arxiv.org/pdf/2402.09727.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | The paper introduces ReadAgent, an innovative LLM system that significantly extends effective context length, up to 20 times in experiments. Mimicking human reading, ReadAgent strategically stores and compresses content into "gist memories," enabling efficient retrieval when needed. Evaluation on long-document reading tasks demonstrates ReadAgent's superiority over baselines, enhancing performance while expanding the effective context window by 3 to 20 times.                                                                                                                                                                                                                                                                                                                         | LLM Agents                     |
| 22 Feb 2024 | [MobileLLM: Optimizing Sub-billion Parameter Language Models for On-Device Use Cases](https://arxiv.org/pdf/2402.14905.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | The paper addresses the need for efficient LLMs on mobile devices by focusing on models with fewer than a billion parameters. Contrary to the belief that data and parameter quantity determine model quality, the study emphasizes the significance of model architecture. Introducing MobileLLM, leveraging deep and thin architectures, the model demonstrates notable accuracy boosts over previous state-of-the-art models. Additionally, MobileLLM-LS, incorporating block-wise weight sharing, further enhances accuracy with marginal latency overhead, highlighting the potential of small models for on-device use cases.                                                                                                                                                                     | Smaller Models                 |
| 22 Feb 2024 | [Stable Diffusion 3](https://stability.ai/news/stable-diffusion-3) |[Stability.ai](http://Stability.ai) announced the early preview of Stable Diffusion 3, their latest text-to-image model, boasting significant improvements in multi-subject prompts, image quality, and spelling abilities. The waitlist for early access is now open, allowing users to contribute insights for enhancing performance and safety prior to its public release. Ranging from 800M to 8B parameters, the suite offers scalability options to cater to various creative needs.Emphasizing safe and responsible AI practices, [Stability.ai](http://Stability.ai) has implemented numerous safeguards and continues to collaborate with researchers and experts to ensure integrity throughout development and deployment. | Multimodal Models              |
| 21 Feb 2024 | [Coercing Large Language Models (LLMs) to Do and Reveal (Almost) Anything](https://arxiv.org/pdf/2402.14020.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | The paper expands the scope of adversarial attacks on LLMs beyond "jailbreaking," highlighting various attack surfaces and goals. Through concrete examples, it categorizes attacks inducing unintended behaviors like misdirection, model control, denial-of-service, and data extraction. Controlled experiments reveal many attacks originate from pre-training with coding capabilities and the presence of "glitch" tokens in LLM vocabularies, emphasizing the need for security measures.                                                                                                                                                                                                                                                                                                        | Red-Teaming                    |
| 21 Feb 2024 | [LongRoPE: Extending LLM Context Window Beyond 2 Million Tokens](https://arxiv.org/pdf/2402.13753.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | The paper introduces LongRoPE, which extends the context window of pre-trained LLMs to an impressive 2048k tokens, overcoming limitations of current extended context windows. Key innovations include exploiting non-uniformities in positional interpolation, a progressive extension strategy, and readjusting to recover short context window performance. Extensive experiments demonstrate the effectiveness of LongRoPE across various tasks, with models retaining the original architecture and minor modifications to positional embedding.                                                                                                                                                                                                                                                   | Long Context, Embedding        |
| 21 Feb 2024 | [Gemma: Open Models Based on Gemini Research and Technology](https://storage.googleapis.com/deepmind-media/gemma/gemma-report.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | This work introduces Gemma, a family of lightweight, state-of-the art open models built from the research and technology used to create Gemini models. Gemma models demonstrate strong performance across academic benchmarks for language understanding, reasoning, and safety. We release two sizes of models (2 billion and 7 billion parameters), and provide both pretrained and fine-tuned checkpoints. Gemma outperforms similarly sized open models on 11 out of 18 text-based tasks, and we present comprehensive evaluations of safety and responsibility aspects of the models, alongside a detailed description of model development. We believe the responsible release of LLMs is critical for improving the safety of frontier models, and for enabling the next wave of LLM innovations | Foundation LLMs                |
| 21 Feb 2024 | [Large Language Models for Data Annotation: A Survey](https://arxiv.org/pdf/2402.13446.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | The paper focuses on leveraging advanced LLMs, like GPT-4, for automating data annotation, a labor-intensive process in machine learning. It offers insights into LLM-Based Data Annotation, Assessing LLM-generated Annotations, and Learning with LLM-generated annotations. The survey includes a taxonomy of methodologies, reviews learning strategies, and discusses challenges and limitations. Aimed at guiding researchers and practitioners, it aims to foster advancements in data annotation using the latest LLMs.                                                                                                                                                                                                                                                                         | Task Specific LLMs             |
| 21 Feb 2024 | [In Search of Needles in a 11M Haystack: Recurrent Memory Finds What LLMs Miss](https://arxiv.org/pdf/2402.10790.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | The paper introduces BABILong, a benchmark designed to evaluate the processing capabilities of generative transformer models on long documents. While common methods are effective only for sequences up to 10^4 elements, fine-tuning GPT-2 with recurrent memory augmentations enables it to handle tasks involving up to 11 × 10^6 elements. This achievement represents a substantial leap, demonstrating significant improvement in processing capabilities for long sequences and marking the longest input processed by any neural network model to date.                                                                                                                                                                                                                                        | Benchmark, Long Context        |
| 20 Feb 2024 | [Large Language Models: A Survey](https://arxiv.org/pdf/2402.06196.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | The paper provides a comprehensive review of LLMs since the release of ChatGPT in November 2022. It discusses prominent LLM families (GPT, LLaMA, PaLM), their characteristics, contributions, and limitations, along with techniques for building and augmenting LLMs. Additionally, it surveys datasets, evaluation metrics, and performance comparisons of popular LLMs on representative benchmarks. The paper concludes by highlighting open challenges and future research directions in the field of LLMs.                                                                                                                                                                                                                                                                                       | Survey of LLMs                 |
| 19 Feb 2024 | [LongAgent: Scaling Language Models to 128k Context Through Multi-Agent Collaboration](https://arxiv.org/pdf/2402.11550.pdf) |The paper introduces LongAgent, a method employing multi-agent collaboration to scale LLMs like LLaMA to process long texts up to 128K tokens. LongAgent utilizes a leader to interpret user intent and coordinate team members in acquiring information. To address hallucination-induced response inaccuracies, an inter-member communication mechanism resolves conflicts through information sharing. Experimental results demonstrate LongAgent's superiority over GPT-4 in tasks such as 128k-long text retrieval and multi-hop question answering.                                                                                                                                                                                                                                               | LLM Agents                     |
| 19 Feb 2024 | [LoRA+: Efficient Low Rank Adaptation of Large Models](https://arxiv.org/pdf/2402.12354.pdf)| The paper identifies suboptimal fine-tuning in models with large width (embedding dimension) using Low Rank Adaptation (LoRA) due to updating adapter matrices A and B with the same learning rate. By setting different learning rates for A and B with a fixed ratio in a proposed algorithm called LoRA+, the suboptimality of LoRA can be corrected. Extensive experiments demonstrate that LoRA+ improves performance (1% − 2% improvements) and fine-tuning speed (up to ∼ 2X SpeedUp) at the same computational cost as LoRA.                                                                                                                                                                                                                                                                    | PEFT                           |
| 15 Feb 2024 | [Generative Representational Instruction Tuning](https://arxiv.org/pdf/2402.09906.pdf) | The paper introduces generative representational instruction tuning (GRIT), enabling a large language model to excel in both generative and embedding tasks by distinguishing between them through instructions. GRITLM 7B sets a new state-of-the-art on the Massive Text Embedding Benchmark (MTEB) and outperforms all models of its size on generative tasks. Scaling up to GRITLM 8X7B further surpasses all open generative language models while remaining among the best embedding models. GRIT unifies generative and embedding training without performance loss, significantly speeding up RAG by over 60% for long documents. Models and code are available.                                                                                                                                | RAG, Instruction Tuning        |
| 15 Feb 2024 | [Chain-of-Thought Reasoning Without Prompting](https://arxiv.org/pdf/2402.10200.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | The study enhances large language models' reasoning abilities without explicit prompting by altering the decoding process to uncover inherent chain-of-thought (CoT) reasoning paths. This method bypasses manual prompt engineering, assesses intrinsic reasoning abilities, and correlates CoT presence with higher confidence in decoded answers. Extensive empirical studies across benchmarks demonstrate significant performance improvement over standard greedy decoding.                                                                                                                                                                                                                                                                                                                       | Prompt Engineering             |
| 15 Feb 2024 | [Gemini 1.5: Unlocking multimodal understanding across millions of tokens of context](https://storage.googleapis.com/deepmind-media/gemini/gemini_v1_5_report.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                  | The report introduces Gemini 1.5 Pro, a highly efficient multimodal model excelling in recalling and reasoning over vast amounts of context, including long documents and videos. It achieves near-perfect recall across tasks, surpasses previous state-of-the-art models, and exhibits surprising translation abilities for rare languages like Kalamang.                                                                                                                                                                                                                                                                                                                                                                                                                                             | Foundation LLMs                |
| 15 Feb 2024 | [Revisiting Feature Prediction for Learning Visual Representations from Video](https://scontent.fsyd14-1.fna.fbcdn.net/v/t39.2365-6/427986745_768441298640104_1604906292521363076_n.pdf) | The paper introduces V-JEPA, a collection of vision models trained solely on video data using a feature prediction objective, without relying on pretrained image encoders, text, negative examples, or reconstruction. Trained on 2 million videos, these models are evaluated on downstream image and video tasks, demonstrating versatile visual representations that excel in both motion and appearance-based tasks without requiring adaptation of model parameters. The largest model, a ViT-H/16 trained only on videos, achieves impressive performance on Kinetics-400, Something-Something-v2, and ImageNet1K datasets.                                                                                                                                                                      | Multimodal LLMs                |
| 13 Feb 2024 | [World Model on Million-Length Video and Language with Ring Attention](https://arxiv.org/pdf/2402.08268.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | The paper addresses limitations of current language models by proposing a joint modeling approach with video sequences to enhance understanding of complex, long-form tasks. It curates a large dataset of diverse videos and books, trains transformers with RingAttention technique on long sequences, and gradually increases context size. Key contributions include training one of the largest context size transformers, overcoming vision-language training challenges, and open-sourcing optimized models capable of processing multimodal sequences over 1M tokens. This work enables training on massive datasets to develop understanding of both human knowledge and the multimodal world, paving the way for broader AI capabilities.                                                      | Multimodal LLMs                |
| 10 Feb 2024 | [ChemLLM: A Chemical Large Language Model](https://arxiv.org/pdf/2402.06852.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | The paper introduces ChemLLM, the first large language model tailored specifically for chemistry applications, addressing the challenge of integrating structured chemical data into coherent dialogue. Through a template-based instruction construction method, ChemLLM transforms structured knowledge into plain dialogue for effective language model training. ChemLLM outperforms GPT-3.5 and GPT-4 on key chemistry tasks such as name conversion, molecular captioning, and reaction prediction, demonstrating exceptional adaptability to related mathematical and physical tasks. Moreover, ChemLLM showcases proficiency in specialized NLP tasks within chemistry, opening new avenues for exploration in chemical studies.                                                                 | Task Specific LLMs             |
| 6 Feb 2024  | [LLM Agents can Autonomously Hack Websites](https://arxiv.org/pdf/2402.06664v1.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | The paper demonstrates that LLMs, particularly GPT-4, possess the capability to autonomously conduct website hacking tasks such as blind database schema extraction and SQL injections without prior knowledge of vulnerabilities. This ability, enabled by advanced models adept at tool usage and leveraging extended context, raises concerns about the potential offensive capabilities of LLM agents and prompts questions regarding their widespread deployment in cybersecurity contexts.                                                                                                                                                                                                                                                                                                        | LLM Agents                     |
| 6 Feb 2024  | [AnyTool: Self-Reflective, Hierarchical Agents for Large-Scale API Calls](https://arxiv.org/pdf/2402.04253.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | The paper introduces AnyTool, a large language model agent designed to enhance the utilization of over 16,000 APIs sourced from Rapid API to address user queries efficiently. AnyTool comprises an API retriever, a solver for query resolution, and a self-reflection mechanism. Powered by the function calling feature of GPT-4, AnyTool eliminates the need for external module training. Additionally, the paper revises the evaluation protocol to introduce AnyToolBench, demonstrating superior performance over strong baselines such as ToolLLM and a GPT-4 variant tailored for tool utilization across various datasets. The code is available at [https://github.com/dyabel/AnyTool](https://github.com/dyabel/AnyTool).                                                                  | LLM Agents                     |
| 6 Feb 2024  | [Large Language Models as an Indirect Reasoner: Contrapositive and Contradiction for Automated Reasoning](https://arxiv.org/pdf/2402.03667.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | The paper introduces a novel Indirect Reasoning (IR) method to enhance the reasoning capabilities of LLMs beyond the limitations of Direct Reasoning (DR) frameworks like Chain-of-Thought and Self-Consistency. By leveraging logic of contrapositives and contradictions, the IR method tackles tasks such as factual reasoning and mathematical proof. Experimental results on popular LLMs, including GPT-3.5-turbo and Gemini-pro, demonstrate a substantial improvement in accuracy for both factual reasoning and mathematical proof compared to traditional DR methods. Combining IR with DR further enhances performance, underscoring the effectiveness of the proposed strategy.                                                                                                             | Prompt Engineering             |
| 6 Feb 2024  | [Self-Discover: Large Language Models Self-Compose Reasoning Structures](https://arxiv.org/pdf/2402.03620.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | The paper introduces SELF-DISCOVER, a framework for LLMs to autonomously identify task-specific reasoning structures, improving performance on challenging reasoning benchmarks like BigBench-Hard and MATH. By selecting and composing atomic reasoning modules during a self-discovery process, SELF-DISCOVER enhances reasoning abilities, surpassing models like GPT-4 and PaLM 2 by up to 32% compared to traditional methods like Chain of Thought (CoT). Notably, it outperforms inference-intensive methods like CoT-Self-Consistency by over 20%, with significantly lower inference compute requirements, while exhibiting universality across different LLM model families and echoing human reasoning patterns.                                                                             | Prompt Engineering             |
| 6 Feb 2024  | [DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models](https://arxiv.org/pdf/2402.03300.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | The paper introduces DeepSeekMath 7B, a model designed to tackle mathematical reasoning challenges by continuing pretraining with a large dataset sourced from Common Crawl. Achieving a notable score of 51.7% on the MATH benchmark without external toolkits, it approaches the performance of advanced models like Gemini-Ultra and GPT-4. DeepSeekMath's success is attributed to leveraging web data via a sophisticated data selection pipeline and employing Group Relative Policy Optimization (GRPO) to enhance mathematical reasoning while optimizing memory usage.                                                                                                                                                                                                                         | Task Specific LLMs             |
| 4 Feb 2024  | [Large Language Model for Table Processing: A Survey](https://arxiv.org/pdf/2402.05121.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | The survey provides a comprehensive overview of table-centric tasks and the utilization of LLMs to automate them, including traditional areas like Table QA and fact verification, as well as newer aspects such as table manipulation and advanced data analysis. It delves into recent paradigms in LLM usage, focusing on instruction-tuning, prompting, and agent-based approaches. The paper also addresses challenges like private deployment, efficient inference, and the need for extensive benchmarks in table manipulation and advanced data analysis.                                                                                                                                                                                                                                       | Task Specific LLMs             |
| 3 Feb 2024  | [More Agents Is All You Need](https://arxiv.org/pdf/2402.05120.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | The paper demonstrates that the performance of LLMs can be improved by scaling the number of instantiated agents using a simple sampling-and-voting method. This method is independent of existing complex enhancement techniques and its effectiveness correlates with task difficulty. Extensive experiments across various LLM benchmarks validate this finding and explore associated properties. The code for the experiments is publicly accessible on Git.                                                                                                                                                                                                                                                                                                                                       | LLM Agents                     |
| 1 Feb 2024  | [OLMo: Accelerating the Science of Language Models](https://arxiv.org/pdf/2402.00838.pdf)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | OLMo aims to accelerate the science of language models by providing a platform for rapid experimentation and understanding of LLMs. It offers tools for model training, fine-tuning, and evaluation, alongside a collaborative environment for researchers. The goal is to facilitate discoveries and advancements in LLM technology, making it more accessible to a wider audience.                                                                                                                                                                                                                                                                                                                                                                                      | Open-Source LLMs |
---




## :mortar_board: Courses
#### [Ongoing] Applied LLMs Mastery 2024
Join 1000+ students on this 10-week adventure as we delve into the application of LLMs across a variety of use cases
#### [Link](https://areganti.notion.site/Applied-LLMs-Mastery-2024-562ddaa27791463e9a1286199325045c) to the course website
##### [Feb 2024] Registrations are still open [click here](https://forms.gle/353sQMRvS951jDYu7) to register

🗓️*Week 1 [Jan 15 2024]***: [Practical Introduction to LLMs](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/free_courses/Applied_LLMs_Mastery_2024/week1_part1_foundations.md)**
- Applied LLM Foundations
- Real World LLM Use Cases
- Domain and Task Adaptation Methods

🗓️*Week 2 [Jan 22 2024]***: [Prompting and Prompt 
Engineering](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/free_courses/Applied_LLMs_Mastery_2024/week2_prompting.md)**
- Basic Prompting Principles
- Types of Prompting
- Applications, Risks and Advanced Prompting

🗓️*Week 3 [Jan 29 2024]***: [LLM Fine-tuning](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/free_courses/Applied_LLMs_Mastery_2024/week3_finetuning_llms.md)** 
- Basics of Fine-Tuning
- Types of Fine-Tuning
- Fine-Tuning Challenges

🗓️*Week 4 [Feb 5 2024]***: [RAG (Retrieval-Augmented Generation)](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/free_courses/Applied_LLMs_Mastery_2024/week4_RAG.md)**
- Understanding the concept of RAG in LLMs
- Key components of RAG
- Advanced RAG Methods

🗓️*Week 5 [ Feb 12 2024]***: [Tools for building LLM Apps](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/free_courses/Applied_LLMs_Mastery_2024/week5_tools_for_LLM_apps.md)**
- Fine-tuning Tools
- RAG Tools
- Tools for observability, prompting, serving, vector search etc.

🗓️*Week 6 [Feb 19 2024]***: [Evaluation Techniques](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/free_courses/Applied_LLMs_Mastery_2024/week6_llm_evaluation.md)**
- Types of Evaluation
- Common Evaluation Benchmarks
- Common Metrics

🗓️*Week 7 [Feb 26 2024]***: [Building Your Own LLM Application](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/free_courses/Applied_LLMs_Mastery_2024/week7_build_llm_app.md)**
- Components of LLM application
- Build your own LLM App end to end

🗓️*Week 8 [March 4 2024]***: [Advanced Features and Deployment](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/free_courses/Applied_LLMs_Mastery_2024/week8_advanced_features.md)**
- LLM lifecycle and LLMOps
- LLM Monitoring and Observability
- Deployment strategies

🗓️*Week 9 [March 11 2024]***: [Challenges with LLMs](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/free_courses/Applied_LLMs_Mastery_2024/week9_challenges_with_llms.md)**
- Scaling Challenges
- Behavioral Challenges
- Future directions

🗓️*Week 10 [March 18 2024]***: [Emerging Research Trends](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/free_courses/Applied_LLMs_Mastery_2024/week10_research_trends.md)**
- Smaller and more performant models
- Multimodal models
- LLM Alignment

🗓️*Week 11 *Bonus* [March 25 2024]***: [Foundations](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/free_courses/Applied_LLMs_Mastery_2024/week11_foundations.md)**
- Generative Models Foundations
- Self-Attention and Transformers
- Neural Networks for Language

---

#### :book: List of Free GenAI Courses
##### LLM Basics and Foundations

1. [Large Language Models](https://rycolab.io/classes/llm-s23/) by ETH Zurich

2. [Understanding Large Language Models](https://www.cs.princeton.edu/courses/archive/fall22/cos597G/) by Princeton

3. [Transformers course](https://huggingface.co/learn/nlp-course/chapter1/1) by Huggingface

4. [NLP course](https://huggingface.co/learn/nlp-course/chapter1/1) by Huggingface

5. [CS324 - Large Language Models](https://stanford-cs324.github.io/winter2022/) by Stanford

6. [Generative AI with Large Language Models](https://www.coursera.org/learn/generative-ai-with-llms) by Coursera

7. [Introduction to Generative AI](https://www.coursera.org/learn/introduction-to-generative-ai) by Coursera

8. [Generative AI Fundamentals](https://www.cloudskillsboost.google/paths/118/course_templates/556) by Google Cloud

9. [Introduction to Large Language Models](https://www.cloudskillsboost.google/paths/118/course_templates/539) by Google Cloud
11. [Introduction to Generative AI](https://www.cloudskillsboost.google/paths/118/course_templates/536) by Google Cloud
12. [Generative AI Concepts](https://www.datacamp.com/courses/generative-ai-concepts) by DataCamp (Daniel Tedesco Data Lead @ Google)
13. [1 Hour Introduction to LLM (Large Language Models)](https://www.youtube.com/watch?v=xu5_kka-suc) by WeCloudData
14. [LLM Foundation Models from the Ground Up | Primer](https://www.youtube.com/watch?v=W0c7jQezTDw&list=PLTPXxbhUt-YWjMCDahwdVye8HW69p5NYS) by Databricks
15. [Generative AI Explained](https://courses.nvidia.com/courses/course-v1:DLI+S-FX-07+V1/) by Nvidia
16. [Transformer Models and BERT Model](https://www.cloudskillsboost.google/course_templates/538) by Google Cloud
17. [Generative AI Learning Plan for Decision Makers](https://explore.skillbuilder.aws/learn/public/learning_plan/view/1909/generative-ai-learning-plan-for-decision-makers) by AWS
18. [Introduction to Responsible AI](https://www.cloudskillsboost.google/course_templates/554) by Google Cloud
19. [Fundamentals of Generative AI](https://learn.microsoft.com/en-us/training/modules/fundamentals-generative-ai/) by Microsoft Azure
20. [Generative AI for Beginners](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-122979-leestott)  by Microsoft
21. [ChatGPT for Beginners: The Ultimate Use Cases for Everyone](https://www.udemy.com/course/chatgpt-for-beginners-the-ultimate-use-cases-for-everyone/) by Udemy
22. 

    


##### Building LLM Applications

1. [LLMOps: Building Real-World Applications With Large Language Models](https://www.udacity.com/course/building-real-world-applications-with-large-language-models--cd13455) by Udacity

2. [Full Stack LLM Bootcamp](https://fullstackdeeplearning.com/llm-bootcamp/) by FSDL

3. [Generative AI for beginners](https://github.com/microsoft/generative-ai-for-beginners/tree/main) by Microsoft

4. [Large Language Models: Application through Production](https://www.edx.org/learn/computer-science/databricks-large-language-models-application-through-production) by Databricks

5. [Generative AI Foundations](https://www.youtube.com/watch?v=oYm66fHqHUM&list=PLhr1KZpdzukf-xb0lmiU3G89GJXaDbAIF) by AWS

6. [Introduction to Generative AI Community Course](https://www.youtube.com/watch?v=ajWheP8ZD70&list=PLmQAMKHKeLZ-iTT-E2kK9uePrJ1Xua9VL) by ineuron

7. [LLM University](https://docs.cohere.com/docs/llmu) by Cohere
8. [LLM Learning Lab](https://lightning.ai/pages/llm-learning-lab/) by Lightning AI

9. [Functions, Tools and Agents with LangChain](https://learn.deeplearning.ai/functions-tools-agents-langchain) by Deeplearning.AI

10. [LangChain for LLM Application Development](https://learn.deeplearning.ai/login?redirect_course=langchain&callbackUrl=https%3A%2F%2Flearn.deeplearning.ai%2Fcourses%2Flangchain) by Deeplearning.AI

11. [LLMOps](https://learn.deeplearning.ai/llmops) by DeepLearning.AI

12. [Automated Testing for LLMOps](https://learn.deeplearning.ai/automated-testing-llmops) by DeepLearning.AI
13. [Building RAG Agents with LLMs](https://courses.nvidia.com/courses/course-v1:DLI+S-FX-15+V1/) by Nvidia
14. [Building Generative AI Applications Using Amazon Bedrock](https://explore.skillbuilder.aws/learn/course/external/view/elearning/17904/building-generative-ai-applications-using-amazon-bedrock-aws-digital-training) by AWS
15. [Efficiently Serving LLMs](https://learn.deeplearning.ai/courses/efficiently-serving-llms/lesson/1/introduction) by DeepLearning.AI
16. [Building Systems with the ChatGPT API](https://www.deeplearning.ai/short-courses/building-systems-with-chatgpt/) by DeepLearning.AI
17. [Serverless LLM apps with Amazon Bedrock](https://www.deeplearning.ai/short-courses/serverless-llm-apps-amazon-bedrock/) by DeepLearning.AI
18. [Building Applications with Vector Databases](https://www.deeplearning.ai/short-courses/building-applications-vector-databases/) by DeepLearning.AI
19. [Automated Testing for LLMOps](https://www.deeplearning.ai/short-courses/automated-testing-llmops/) by DeepLearning.AI
20. [LLMOps](https://www.deeplearning.ai/short-courses/llmops/) by DeepLearning.AI
21. [Build LLM Apps with LangChain.js](https://www.deeplearning.ai/short-courses/build-llm-apps-with-langchain-js/) by DeepLearning.AI
22. [Advanced Retrieval for AI with Chroma](https://www.deeplearning.ai/short-courses/advanced-retrieval-for-ai/) by DeepLearning.AI
23. [LangChain & Vector Databases in Production](https://learn.activeloop.ai/courses/langchain) by ActiveLoop
    

##### 3. Prompt Engineering, RAG and Fine-Tuning
1. [LangChain & Vector Databases in Production](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbVhnQW8xNDdhSU9IUDVLXzFhV2N0UkNRMkZrQXxBQ3Jtc0traUxHMzZJcGJQYjlyckYxaGxYVWlsOFNGUFlFVEdhNzdjTWpPUlQ2TF9XczRqNkxMVGpJTnd5YmYzV0prQ0IwZURNcHhIZ3h1Z051VTl5MXBBLUN0dkM0NHRkQTFua1Jpc0VCRFJUb0ZQZG95b0JqMA&q=https%3A%2F%2Flearn.activeloop.ai%2Fcourses%2Flangchain&v=gKUTDC13jys) by Activeloop

2. [Reinforcement Learning from Human Feedback](https://learn.deeplearning.ai/reinforcement-learning-from-human-feedback) by DeepLearning.AI

3. [Building Applications with Vector Databases](https://learn.deeplearning.ai/building-applications-vector-databases) by DeepLearning.AI

4. [Finetuning Large Language Models](https://learn.deeplearning.ai/finetuning-large-language-models) by Deeplearning.AI
5. [LangChain: Chat with Your Data](http://learn.deeplearning.ai/langchain-chat-with-your-data/) by Deeplearning.AI

6. [Building Systems with the ChatGPT API](https://learn.deeplearning.ai/chatgpt-building-system) by Deeplearning.AI
7. [Prompt Engineering with Llama 2](https://www.deeplearning.ai/short-courses/prompt-engineering-with-llama-2/) by Deeplearning.AI
8. [Building Applications with Vector Databases](https://learn.deeplearning.ai/building-applications-vector-databases) by Deeplearning.AI
9. [ChatGPT Prompt Engineering for Developers](https://learn.deeplearning.ai/chatgpt-prompt-eng/lesson/1/introduction) by Deeplearning.AI
10. [Advanced RAG Orchestration series](https://www.youtube.com/watch?v=CeDS1yvw9E4) by LlamaIndex
11. [Prompt Engineering Specialization](https://www.coursera.org/specializations/prompt-engineering) by Coursera
12. [Augment your LLM Using Retrieval Augmented Generation](https://courses.nvidia.com/courses/course-v1:NVIDIA+S-FX-16+v1/) by Nvidia
13. [Knowledge Graphs for RAG](https://www.deeplearning.ai/short-courses/knowledge-graphs-rag/)  by Deeplearning.AI
14. [Open Source Models with Hugging Face](https://www.deeplearning.ai/short-courses/open-source-models-hugging-face/) by Deeplearning.AI
15. [Vector Databases: from Embeddings to Applications](https://www.deeplearning.ai/short-courses/vector-databases-embeddings-applications/) by Deeplearning.AI
16. [Understanding and Applying Text Embeddings](https://www.deeplearning.ai/short-courses/google-cloud-vertex-ai/) by Deeplearning.AI
    

##### Evaluation
1. [Building and Evaluating Advanced RAG Applications](https://learn.deeplearning.ai/building-evaluating-advanced-rag) by DeepLearning.AI
2. [Evaluating and Debugging Generative AI Models Using Weights and Biases](https://learn.deeplearning.ai/evaluating-debugging-generative-ai) by Deeplearning.AI
3. [Quality and Safety for LLM Applications](https://www.deeplearning.ai/short-courses/quality-safety-llm-applications/) by Deeplearning.AI
   

##### Multimodal 
1. [How Diffusion Models Work](https://www.deeplearning.ai/short-courses/how-diffusion-models-work/) by DeepLearning.AI
2. [How to Use Midjourney, AI Art and ChatGPT to Create an Amazing Website](https://www.youtube.com/watch?v=5wdCev86RYE) by Brad Hussey
3. [Build AI Apps with ChatGPT, DALL-E and GPT-4](https://scrimba.com/learn/buildaiapps) by Scrimba
   



   



---

## :paperclip: Resources
- [ICLR 2024 Paper Summaries](https://areganti.notion.site/06f0d4fe46a94d62bff2ae001cfec22c?v=d501ca62e4b745768385d698f173ae14)


---


## :computer: Interview Prep 
#### Topic wise Questions:
1. [Common GenAI Interview Questions](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/interview_prep/60_gen_ai_questions.md)
2. Prompting and Prompt Engineering 
3. Model Fine-Tuning 
4. Model Evaluation 
5. MLOps for GenAI 
6. Generative Models Foundations 
7. Latest Research Trends 

#### GenAI System Design (Coming Soon):

1. Designing an LLM-Powered Search Engine
2. Building a Customer Support Chatbot
3. Building a system for natural language interaction with your data.
4. Building an AI Co-pilot
5. Designing a Custom Chatbot for Q/A on Multimodal Data (Text, Images, Tables, CSV Files)
6. Building an Automated Product Description and Image Generation System for E-commerce



---
## :notebook: Code Notebooks
#### RAG Tutorials
- [AWS Bedrock Workshop Tutorials](https://github.com/aws-samples/amazon-bedrock-workshop) by Amazon Web Services
- [Langchain Tutorials](https://github.com/gkamradt/langchain-tutorials) by gkamradt
- [LLM Applications for production](https://github.com/ray-project/llm-applications/tree/main) by ray-project
- [LLM tutorials](https://github.com/ollama/ollama/tree/main/examples) by Ollama
- [LLM Hub](https://github.com/mallahyari/llm-hub) by mallahyari

#### Fine-Tuning Tutorials
- [LLM Fine-tuning tutorials](https://github.com/ashishpatel26/LLM-Finetuning) by ashishpatel26
- [PEFT](https://github.com/huggingface/peft/tree/main/examples) example notebooks by Huggingface
- [Free LLM Fine-Tuning Notebooks](https://levelup.gitconnected.com/14-free-large-language-models-fine-tuning-notebooks-532055717cb7) by Youssef Hosni



---

## :black_nib: Contributing
If you want to add to the repository or find any issues, please feel free to raise a PR and ensure correct placement within the relevant section or category.


---

## :pushpin: Cite Us

To cite this guide, use the below format:

```
@article{areganti_generative_ai_guide,
author = {Reganti, Aishwarya Naresh},
journal = {https://github.com/aishwaryanr/awesome-generative-ai-resources},
month = {01},
title = {{Generative AI Guide}},
year = {2024}
}
```

## License

[MIT License]


