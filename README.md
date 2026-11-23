# AI Engineer Interview Questions

> A structured guide to AI engineer and machine learning interviews, brought to you by [Aced](https://www.aced.io). Check out the full [AI engineering course](https://www.aced.io/courses/ai-engineering).

---

## Table of contents

- [About this guide](#about-this-guide)
- [The interview loop](#the-interview-loop)
- [Core topics](#core-topics)
- [LLM and AI engineering topics](#llm-and-ai-engineering-topics)
- [ML system design questions](#ml-system-design-questions)
- [Additional resources](#additional-resources)

---

## About this guide

AI engineer and MLE loops now test three distinct skill sets: classical ML fundamentals, ML system design, and (increasingly) LLM-era engineering: RAG, evals, fine-tuning, and agents. This primer organizes prep for all three.

## The interview loop

A typical MLE / AI engineer process:

1. Recruiter screen: background and interest
2. Technical screen: coding (often ML-flavored LeetCode or data manipulation)
3. ML fundamentals round: theory, trade-offs, debugging intuition
4. ML system design: design an end-to-end ML system
5. Behavioral: projects in depth, collaboration, impact

Company-specific breakdowns, including [Anthropic's MLE process](https://www.aced.io/guides/anthropic-machine-learning-engineer-interview), are on Aced.

## Core topics

### ML fundamentals

| Topic | What gets asked |
|-------|-----------------|
| Bias-variance trade-off | Diagnosing under/overfitting, what to do about each |
| Regularization | L1 vs L2, when and why; dropout; early stopping |
| Class imbalance | Resampling, class weights, metric choice |
| Evaluation metrics | Precision/recall, ROC-AUC, calibration, when accuracy lies |
| Feature engineering | Leakage, encoding, normalization |
| Classical models | Linear/logistic regression, trees, gradient boosting, k-means |

### Deep learning

| Topic | What gets asked |
|-------|-----------------|
| Backprop and optimization | SGD vs Adam, learning-rate schedules, vanishing gradients |
| Architectures | CNNs, RNNs, transformers and attention |
| Training at scale | Data/model parallelism, mixed precision, checkpointing |
| Embeddings | Similarity search, two-tower models, vector indexes |

## LLM and AI engineering topics

| Topic | What gets asked |
|-------|-----------------|
| RAG | Chunking, retrieval quality, reranking, grounding, when RAG beats fine-tuning |
| Evals | Building eval sets, LLM-as-judge pitfalls, regression testing prompts |
| Fine-tuning | LoRA, when to fine-tune vs prompt, data curation |
| Inference | Latency/cost trade-offs, batching, caching, quantization |
| Agents | Tool use, planning loops, failure modes, guardrails |
| Prompt engineering | Structured outputs, few-shot design, injection defenses |

## ML system design questions

| Question | Key concepts |
|----------|--------------|
| Design a recommendation system | Candidate generation, ranking, cold start, feedback loops |
| Design a feed-ranking system | Features, online/offline training, A/B testing |
| Design a fraud-detection system | Imbalance, latency budgets, human review loops |
| Design semantic search | Embeddings, ANN indexes, hybrid retrieval |
| Design a RAG-based assistant | Retrieval pipeline, evals, hallucination control |
| Design an ML platform for experimentation | Feature stores, model registry, monitoring, drift |

For each: clarify the product goal, pick metrics, sketch the data pipeline, choose a model family, then spend most of your time on serving, monitoring, and iteration, because that's where senior candidates differentiate.

## Additional resources

- Browse hundreds of other practice questions in the [ML question bank](https://www.aced.io/questions?role=ml-engineer)
- Top company guides on Aced: [Google MLE](https://www.aced.io/guides/google-machine-learning-engineer-interview) · [Meta MLE](https://www.aced.io/guides/meta-machine-learning-engineer-interview) · [Amazon MLE](https://www.aced.io/guides/amazon-machine-learning-engineer-interview)
- From the blog: [AI engineer interview questions](https://www.aced.io/blog/ai-engineer-interview-questions)
- [Aced mock interviews](https://www.aced.io/practice)
- Papers: Attention Is All You Need; InstructGPT; Constitutional AI
- Book: Designing Machine Learning Systems (Chip Huyen)

## Contributing

PRs welcome: questions you've been asked, corrections, new topics. Keep entries interview-focused.

## License

MIT. Maintained by [Aced](https://www.aced.io).

---

**Related guides:** [System Design](https://github.com/jacobsimon/system-design-interview-questions) · [Product Manager](https://github.com/jacobsimon/product-manager-interview-questions)
