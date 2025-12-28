 # 📘 AI Engineering Notes & Insights  
### Based on *“AI Engineering: Building Applications with Foundation Models”* by Chip Huyen

<p align="center">
  <img src="https://m.media-amazon.com/images/I/815KH9GjFTL.jpg" alt="AI Engineering Book Cover" width="280"/>
</p>

<p align="center">
  <strong>Research Notes & Reflections by Mohini Giri</strong><br>
  Exploring how to turn foundation models into real-world AI systems.
</p>

---

## 🌟 About This Repository

This repository contains my **chapter-wise notes, explanations, and personal insights** while studying the book:

> **AI Engineering: Building Applications with Foundation Models** — *Chip Huyen*

Rather than just summarizing, I focus on:
- Breaking down complex ideas into simple intuition  
- Connecting theory with real-world AI systems  
- Adding reflections as a junior AI engineer and researcher  
- Making the content beginner-friendly and practical  

This is part of my journey to deeply understand how modern AI systems are built — not just how to use them.

---

## 🧠 What You’ll Find Here

✔️ Clear explanations of key concepts  
✔️ Section-wise breakdowns of each chapter  
✔️ Intuition behind math, architectures, and training methods  
✔️ My personal insights and reflections  
✔️ Diagrams and tables (where helpful)  
✔️ Practical perspective for builders  

---

## 📚 Chapters Covered

### 📘 Chapter 1 — *Introduction to AI Engineering*
Key themes:
- Why **scale** defines modern AI  
- Rise of **AI engineering** as a discipline  
- LLMs as next-token predictors  
- From language models to **foundation models**  
- Prompting, RAG, and fine-tuning as core tools  
- AI systems vs demos  

💡 *Insight:*  
> AI engineering is about turning powerful models into **reliable systems** that solve real problems.

---

### 📘 Chapter 2 — *Understanding Foundation Models*
Key themes:
- Training data and its impact on behavior  
- Transformers and the **attention mechanism**  
- Model size and scaling trade-offs  
- Post-training: **SFT, RLHF, DPO**  
- Sampling strategies: temperature, top-k, top-p  
- Test-time compute and structured outputs  
- The **probabilistic nature** of AI  

💡 *Insight:*  
> What feels like magic is really matrix math, attention, and representations working at scale.

---

### Chapter 3 – Evaluation Methodology

#### Overview
This chapter introduces the **core methodologies for evaluating modern AI systems**, with an emphasis on **foundation models and open-ended generation**. As models become more capable, failures become more costly, making evaluation increasingly critical—and increasingly difficult.

#### Why This Chapter Matters
- Stronger models increase the risk of **catastrophic failures**
- Open-ended generation lacks a single ground truth
- Evaluation investments lag behind model and application development

#### What This Chapter Covers
- Why **foundation models are harder to evaluate** than traditional ML models
- The role of **human evaluation** and why it remains essential despite scalability limits
- Automatic evaluation techniques and where they succeed or fail
- **Language modeling metrics**, including:
  - Cross entropy
  - Perplexity
- How to interpret language modeling metrics and use them in practice
- Approaches to evaluating open-ended outputs:
  - Functional correctness (exact evaluation)
  - Similarity-based metrics
  - AI as a judge
- Limitations of subjective metrics and judge dependency
- **Comparative evaluation** and pairwise ranking
- Preference signals and **preference models** used in alignment and evaluation

#### Key Insights
- Exact metrics are reliable but limited in scope
- Subjective evaluation scales but lacks long-term stability
- Scores from different AI judges are not directly comparable
- Preference-based and comparative evaluation are increasingly important
- No single evaluation method is sufficient on its own

#### Takeaway
Reliable evaluation of modern AI systems requires **combining exact evaluation, subjective judgments, comparative signals, and human feedback**.

#### How This Chapter Fits
This chapter focuses on **evaluation techniques and metrics**.  
Chapter 4 builds on this foundation to explain **how to apply these methods in real-world AI systems**.

---

### Chapter 4 – Evaluating AI Systems

#### Overview
This chapter focuses on **putting evaluation into practice**. It explains how to evaluate AI systems holistically, select appropriate models, and design **reliable evaluation pipelines** that support real-world deployment and long-term improvement.

#### Why This Chapter Matters
- Lack of evaluation pipelines is a **major blocker to AI adoption**
- The main challenge has shifted from building models to **selecting the right models**
- Evaluation is essential for trust, safety, and scalability

#### What This Chapter Covers
- Core **evaluation criteria** for AI applications:
  - Domain-specific capabilities
  - Generation quality
  - Instruction-following ability
  - Factual consistency and hallucinations
  - Safety
  - Cost and latency
- How traditional NLP metrics (fluency, coherence, faithfulness) apply to foundation models
- **Evaluation-driven development**, inspired by test-driven development
- Designing end-to-end **evaluation pipelines**
- Evaluating:
  - Individual components
  - Intermediate outputs
  - End-to-end task success
- Creating evaluation guidelines and scoring rubrics
- Aligning evaluation metrics with **business goals**
- Evaluating the evaluation pipeline itself

#### Model Selection
- Selecting models based on **cost–performance tradeoffs**
- Differentiating between:
  - **Hard attributes** (difficult or impossible to change)
  - **Soft attributes** (can be improved through prompts, tuning, or iteration)
- Using public benchmarks to filter models—not to select the best one
- Treating model selection as building a **private leaderboard** tailored to your application

#### Build vs Buy
- Evaluating whether to:
  - Host models yourself
  - Use model APIs
- Tradeoffs across key axes:
  - Data privacy
  - Data lineage
  - Performance
  - Functionality
  - Control
  - Cost
  - On-device deployment
- Emphasizing that build vs buy decisions are **context-dependent**

#### Key Insights
- No perfect evaluation method exists
- High-dimensional AI systems cannot be captured by a few metrics
- Combining multiple evaluation approaches mitigates bias and limitations
- Evaluation must be **continuous**, not one-time

## How This Chapter Fits
This chapter shows **how to operationalize evaluation methodologies** discussed in Chapter 3.  
Evaluation continues to reappear throughout AI development, including:
- Retrieval and agent evaluation
- Memory, latency, and cost analysis
- Data quality verification
- User feedback in production systems

## Transition
With evaluation foundations in place, the next step is **model adaptation**, starting with **prompt engineering**.


## 🎯 Why I Built This

I am documenting my learning in public to:
- Build strong fundamentals in AI/LLMs  
- Practice thinking like a system designer, not just a model user  
- Help other learners who feel overwhelmed by the AI space  
- Create a long-term knowledge base for myself and others  

If you’re starting your AI journey or transitioning into AI engineering, I hope these notes make the path clearer.

---

## 🚀 How to Use This Repo

- Download the html file first  
- Skim summaries for quick revision  
- Dive into reflections for deeper intuition  
- Use as reference while building AI projects  

---

## 🤝 Contributions & Feedback

This is a personal learning project, but:
- Suggestions  
- Corrections  
- Discussions  
- PRs  

are always welcome. Let’s learn together.

---

## 🙌 Acknowledgements

All credit for the original ideas goes to:  
**Chip Huyen**, author of *AI Engineering: Building Applications with Foundation Models*.

This repository is purely for educational and learning purposes.

---

## 🔗 Connect With Me

👩‍💻 **Mohini Giri**  
Aspiring AI Engineer | LLM Enthusiast | Learning in Public  

- LinkedIn:  https://www.linkedin.com/in/mohini-giri-a9085b282/ 
- GitHub:  https://github.com/Mohini117 

---

⭐ If you find this useful, consider starring the repo to support my journey!

