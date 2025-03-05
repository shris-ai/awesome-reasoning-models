# awesome-reasoning-models  

# Reasoning Models
- [IBM Granite 3.2](https://www.ibm.com/new/announcements/ibm-granite-3-2-open-source-reasoning-and-vision) | [View the model on Huggingface] (https://huggingface.co/collections/ibm-granite/granite-32-language-models-67b3bc8c13508f6d064cff9a)
- [xAI's Grok 3](https://x.ai/blog/grok-3)
- TheFinAI's Fino1-8B | Paper - [Fino1: On the Transferability of Reasoning Enhanced LLMs to Finance](https://arxiv.org/abs/2502.08127) | [View the model on Huggingface](https://huggingface.co/TheFinAI/Fino1-8B)
- [DeepHermes 3 by Nous Research] (https://huggingface.co/NousResearch/DeepHermes-3-Llama-3-8B-Preview)
- Open o1 | [Github](https://github.com/Open-Source-O1/Open-O1) | [View the model on Huggingface]()
- [OpenThinker-32B](https://www.open-thoughts.ai/blog/scale) | [View the model on Huggingface](https://huggingface.co/open-thoughts/OpenThinker-32B)
- [Sky-T1-32B-Flash by NovaSky](https://novasky-ai.github.io/posts/reduce-overthinking/) | [View the model on Huggingface](https://huggingface.co/NovaSky-AI/Sky-T1-32B-Flash)

# Research Papers  

## Thinking Techniques  

- [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903)  
- [Tree of Thoughts: Deliberate Problem Solving with Large Language Models](https://arxiv.org/abs/2305.10601)  
- [Let's Think Dot by Dot: Hidden Computation in Transformer Language Models](https://arxiv.org/abs/2404.15758)  
- [Think before you speak: Training Language Models With Pause Tokens](https://arxiv.org/abs/2310.02226)  
- [Chain of Draft: Thinking Faster by Writing Less](https://arxiv.org/abs/2502.18600v2)
- [The Relationship Between Reasoning and Performance in Large Language Models -- o3 (mini) Thinks Harder, Not Longer](https://arxiv.org/abs/2502.15631)
- [TokenSkip: Controllable Chain-of-Thought Compression in LLMs](https://arxiv.org/abs/2502.12067)
- [CoAT: Chain-of-Associated-Thoughts Framework for Enhancing Large Language Models Reasoning](https://arxiv.org/abs/2502.02390)

## Scaling Test-Time Compute  

### Generic Papers
- [Scaling LLM Test-Time Compute Optimally can be More Effective than Scaling Model Parameters](https://arxiv.org/abs/2408.03314)
- [s1: Simple test-time scaling](https://arxiv.org/abs/2501.19393)  
- [Can 1B LLM Surpass 405B LLM? Rethinking Compute-Optimal Test-Time Scaling](https://arxiv.org/abs/2502.06703)
- [Thinking Slow, Fast: Scaling Inference Compute with Distilled Reasoners](https://arxiv.org/pdf/2502.20339)
- [LIMO: Less is More for Reasoning](https://arxiv.org/abs/2502.03387)
- [One Example Shown, Many Concepts Known! Counterexample-Driven Conceptual Reasoning in Mathematical LLMs](https://arxiv.org/abs/2502.10454)
- [Adapting Language-Specific LLMs to a Reasoning Model in One Day via Model Merging -- An Open Recipe](https://arxiv.org/abs/2502.09056)
- [Enhancing Reasoning to Adapt Large Language Models for Domain-Specific Applications](https://arxiv.org/abs/2502.04384)
- [CodeI/O: Condensing Reasoning Patterns via Code Input-Output Prediction](https://arxiv.org/abs/2502.07316)
- [LM2: Large Memory Models](https://arxiv.org/abs/2502.06049)]
- [ZebraLogic: On the Scaling Limits of LLMs for Logical Reasoning](https://arxiv.org/abs/2502.01100)
- [The Jumping Reasoning Curve? Tracking the Evolution of Reasoning Performance in GPT-[n] and o-[n] Models on Multimodal Puzzles](https://arxiv.org/abs/2502.01081)
- [TensorLLM: Tensorising Multi-Head Attention for Enhanced Reasoning and Compression in LLMs](https://arxiv.org/abs/2501.15674)
- [Reasoning Language Models: A Blueprint](https://arxiv.org/abs/2501.11223)

### Datasets

- [NaturalReasoning: Reasoning in the Wild with 2.8M Challenging Questions](https://arxiv.org/abs/2502.13124)
- [NuminaMath-1.5B](https://huggingface.co/datasets/AI-MO/NuminaMath-1.5)

### Paper on search algorithms
- [Implicit Search via Discrete Diffusion: A Study on Chess](https://arxiv.org/abs/2502.19805)
- [Self-rewarding correction for mathematical reasoning](https://arxiv.org/pdf/2502.19613)
- 

### Papers focusing on `Verifiers / Reward Models`

- [Let's Verify Step by Step](https://arxiv.org/abs/2305.20050)  
- [Solving math word problems with process- and outcome-based feedback](https://arxiv.org/abs/2211.14275)
- [Improve Mathematical Reasoning in Language Models by Automated Process Supervision](https://arxiv.org/abs/2406.06592)
- [ReST-MCTS*: LLM Self-Training via Process Reward Guided Tree Search](https://arxiv.org/abs/2406.03816)
- [Diverse Inference and Verification for Advanced Reasoning](https://arxiv.org/abs/2502.09955)

### Papers on `Modifying the proposal distribution`

- [The Effect of Sampling Temperature on Problem Solving in Large Language Models](https://arxiv.org/abs/2402.05201)  
- [Large Language Monkeys: Scaling Inference Compute with Repeated Sampling](https://arxiv.org/abs/2407.21787)  
- [Planning with Large Language Models for Code Generation](https://arxiv.org/abs/2303.05510)   
- [Inference Scaling Laws: An Empirical Analysis of Compute-Optimal Inference for Problem-Solving with Language Models](https://arxiv.org/abs/2408.00724)  
- [LightThinker: Dynamic Compression of Intermediate Thoughts for More Efficient LLM Reasoning](https://arxiv.org/abs/2502.15589)
- [Learning to Reason at the Frontier of Learnability](https://arxiv.org/abs/2502.12272)


## Fine-tuning/Reinforcement Learning based reasoning

- [SWE-RL: Advancing LLM Reasoning via Reinforcement Learning on Open Software Evolution](https://arxiv.org/abs/2502.18449)
- [Open Reasoner Zero: An Open Source Approach to Scaling Up Reinforcement Learning on the Base Model](https://github.com/Open-Reasoner-Zero/Open-Reasoner-Zero/blob/main/ORZ_paper.pdf)
- [AlphaMaze: Enhancing Large Language Models' Spatial Intelligence via GRPO](https://arxiv.org/abs/2502.14669)
- [ReasonFlux: Hierarchical LLM Reasoning via Scaling Thought Templates](https://arxiv.org/abs/2502.06772)
- [LLMs Can Easily Learn to Reason from Demonstrations Structure, not content, is what matters!](https://arxiv.org/abs/2502.07374)
- [Competitive Programming with Large Reasoning Models](https://arxiv.org/abs/2502.06807)
- [Exploring the Limit of Outcome Reward for Learning Mathematical Reasoning](https://arxiv.org/abs/2502.06781)
- [Demystifying Long Chain-of-Thought Reasoning in LLMs](https://arxiv.org/abs/2502.03373)
- [Process Reinforcement through Implicit Rewards](https://arxiv.org/abs/2502.01456)
- [Satori: Reinforcement Learning with Chain-of-Action-Thought Enhances LLM Reasoning via Autoregressive Search](https://arxiv.org/abs/2502.02508)
- [Critique Fine-Tuning: Learning to Critique is More Effective than Learning to Imitate](https://arxiv.org/abs/2501.17703)
- [O1-Pruner: Length-Harmonizing Fine-Tuning for O1-Like Reasoning Pruning](https://arxiv.org/abs/2501.12570)

## Latent Reasoning

- [Scaling up Test-Time Compute with Latent Reasoning: A Recurrent Depth Approach](https://arxiv.org/abs/2502.05171)

## Retrieve & Reason

- [Chain-of-Retrieval Augmented Generation](https://arxiv.org/abs/2501.14342)

## Agengtic AI x Reasoning

- [PlanGEN: A Multi-Agent Framework for Generating Planning and Reasoning Trajectories for Complex Problem Solving](https://arxiv.org/abs/2502.16111)
- [SMART: Self-Aware Agent for Tool Overuse Mitigation](https://arxiv.org/abs/2502.11435)
- [OctoTools: An Agentic Framework with Extensible Tools for Complex Reasoning](https://arxiv.org/abs/2502.11271)
- [SiriuS: Self-improving Multi-agent Systems via Bootstrapped Reasoning](https://arxiv.org/pdf/2502.04780)
- [Deep Research by Open AI](https://openai.com/index/introducing-deep-research/)
- [UI-TARS: Pioneering Automated GUI Interaction with Native Agents](https://arxiv.org/abs/2501.12326)


