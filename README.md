<h1 align="center">Maxwell Calkin</h1>

<p align="center">
  <strong>AI Safety Research &middot; Alignment Evaluation &middot; Mechanistic Interpretability</strong>
</p>

<p align="center">
  <a href="https://maxwellcalkin.com">Website</a> &middot;
  <a href="https://twitter.com/maxcalkin">Twitter/X</a> &middot;
  <a href="https://linkedin.com/in/maxwellcalkin">LinkedIn</a>
</p>

---

I build open-source tools and frameworks for measuring whether AI systems are safe and aligned. My work focuses on two questions:

1. **How do we know a model is aligned?** &mdash; Developing rigorous, reproducible evaluation methods for alignment-relevant behaviors (sycophancy, deception, power-seeking, corrigibility) that go beyond surface-level red-teaming.

2. **What is actually happening inside the model?** &mdash; Building practical mechanistic interpretability tools that help researchers trace model behavior to specific internal circuits and representations.

I'm currently a systems engineer with the U.S. Space Force, where I work on safety-critical systems and apply aerospace-grade engineering rigor to AI deployment. The overlap between space systems safety and AI safety is deeper than most people realize &mdash; both domains demand formal verification, defense in depth, and the assumption that failure is catastrophic and irreversible.

### Featured Research Tools

**[alignment-evals](https://github.com/MaxwellCalkin/alignment-evals)** &mdash; Framework for evaluating alignment properties (sycophancy, corrigibility, deception, goal stability, power-seeking) with statistical confidence intervals across models. Designed for reproducibility and extensibility.

**[alignment-probes](https://github.com/MaxwellCalkin/alignment-probes)** &mdash; Structured probing toolkit with a taxonomy of 11+ calibrated probes across 5 alignment-critical behavior categories, drawn from Hubinger et al. (2019), Sharma et al. (2023), and Anthropic's sleeper agents work (2024).

**[interpretability-toolkit](https://github.com/MaxwellCalkin/interpretability-toolkit)** &mdash; Practical mechanistic interpretability tools: activation caching, linear probes, activation patching, and circuit discovery for transformer models. Built for researchers who want to understand what's actually happening inside the network.

**[prompt-injection-benchmark](https://github.com/MaxwellCalkin/prompt-injection-benchmark)** &mdash; Rigorous benchmark for LLM robustness to prompt injection attacks. Formal taxonomy of 6 attack categories, 14+ vectors, and multi-dimensional scoring that balances resistance with helpfulness.

**[llm-circuit-visualizer](https://github.com/MaxwellCalkin/llm-circuit-visualizer)** &mdash; Interactive visualization for exploring internal circuits, attention patterns, and activation flows in language models.

### Research Interests

- **Alignment evaluation methodology** &mdash; Developing metrics and benchmarks that actually measure alignment, not just compliance. How do we build evaluations that are robust to Goodharting?
- **Mechanistic interpretability** &mdash; Activation patching, circuit discovery, and linear probes as tools for building a mechanistic theory of model behavior.
- **Scalable oversight** &mdash; As AI systems grow more capable than their overseers, what institutional and technical mechanisms maintain meaningful human control?
- **AI safety for space & defense systems** &mdash; Applying safety-critical engineering principles from aerospace (formal verification, fault trees, defense in depth) to AI deployment in high-stakes environments.
- **Existential risk from advanced AI** &mdash; Long-term catastrophic risk reduction through technical alignment work and governance research.

### Approach

I believe AI safety needs to be built on the same engineering discipline we apply to other safety-critical domains. That means: reproducible evaluations, open tools, adversarial testing, and the assumption that if you can't measure it, you can't trust it. Everything I build is open-source because safety research that lives behind closed doors doesn't make anyone safer.

### Tech

Python &middot; PyTorch &middot; HuggingFace Transformers &middot; TypeScript &middot; React &middot; NumPy &middot; CUDA &middot; Docker &middot; Linux

---

<p align="center"><em>If you're working on alignment, interpretability, or AI governance &mdash; I'd love to collaborate. Reach out.</em></p>
