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

I build open-source tools for measuring whether AI systems are safe &mdash; and I believe most alignment work is too narrow because it only looks at the problem from one angle.

A model that *behaves* correctly on benchmarks may still harbor misaligned internal representations. A model with well-understood internals may still cause harm when embedded in poorly designed institutions. A technically aligned system deployed without shared understanding across the teams operating it is a disaster waiting to happen. These aren't separate problems &mdash; they're four faces of the same problem, and alignment only works when we address all of them simultaneously:

1. **What is happening inside the model?** &mdash; The interior of the system itself. Mechanistic interpretability, circuit discovery, and representation analysis &mdash; understanding the actual computational structures that produce behavior, not just the behavior we observe.

2. **What does the model actually do?** &mdash; Observable behavior under rigorous evaluation. Sycophancy, deception, power-seeking, corrigibility &mdash; measured reproducibly across conditions, not just spot-checked.

3. **What shared values and understanding do we bring to deployment?** &mdash; The culture, norms, and meaning-making of the teams and communities building and operating AI systems. Technical safety without shared understanding of *why* it matters is brittle. Alignment is as much a coordination problem as a technical one.

4. **What systems, institutions, and governance structures do we build around AI?** &mdash; The external structures that constrain, monitor, and correct AI behavior at scale. Oversight mechanisms, deployment infrastructure, regulatory frameworks, and feedback loops that operate even when individual components fail.

Most alignment research lives in just one or two of these dimensions. My work is an attempt to build tools that bridge them.

I'm currently a systems engineer with the U.S. Space Force, where I work on safety-critical systems and apply aerospace-grade engineering rigor to AI deployment. Aerospace taught me something that applies directly to alignment: **safety is never a property of a single component &mdash; it's a property of the entire system, including the humans, institutions, and culture surrounding it.** A rocket engine can be flawless and still fail catastrophically if the organizational culture suppresses dissent about risk. The same is true for AI.

### Featured Research Tools

**[alignment-evals](https://github.com/MaxwellCalkin/alignment-evals)** &mdash; Framework for evaluating alignment properties (sycophancy, corrigibility, deception, goal stability, power-seeking) with statistical confidence intervals across models. Designed for reproducibility and extensibility.

**[alignment-probes](https://github.com/MaxwellCalkin/alignment-probes)** &mdash; Structured probing toolkit with a taxonomy of 11+ calibrated probes across 5 alignment-critical behavior categories, drawn from Hubinger et al. (2019), Sharma et al. (2023), and Anthropic's sleeper agents work (2024).

**[interpretability-toolkit](https://github.com/MaxwellCalkin/interpretability-toolkit)** &mdash; Practical mechanistic interpretability tools: activation caching, linear probes, activation patching, and circuit discovery for transformer models. Built for researchers who want to understand what's actually happening inside the network.

**[prompt-injection-benchmark](https://github.com/MaxwellCalkin/prompt-injection-benchmark)** &mdash; Rigorous benchmark for LLM robustness to prompt injection attacks. Formal taxonomy of 6 attack categories, 14+ vectors, and multi-dimensional scoring that balances resistance with helpfulness.

**[llm-circuit-visualizer](https://github.com/MaxwellCalkin/llm-circuit-visualizer)** &mdash; Interactive visualization for exploring internal circuits, attention patterns, and activation flows in language models.

### Research Interests

- **Mechanistic interpretability** &mdash; Understanding the interior of models: activation patching, circuit discovery, and linear probes as tools for building a genuine theory of *what the model is*, not just what it does.
- **Alignment evaluation methodology** &mdash; Measuring observable behavior rigorously. Developing metrics robust to Goodharting, where the evaluation captures real alignment rather than surface compliance.
- **Scalable oversight & coordination** &mdash; How do the humans and teams around AI systems maintain shared understanding as capabilities scale? Alignment isn't just a property of the model &mdash; it's a property of the sociotechnical system.
- **AI governance & institutional design** &mdash; Building external structures (regulatory frameworks, deployment protocols, feedback loops) that keep AI systems safe even when individual technical measures are insufficient.
- **AI safety for space & defense** &mdash; Applying lessons from aerospace safety culture (formal verification, fault trees, defense in depth, and organizational risk management) to AI deployment in high-stakes environments.
- **Developmental risk** &mdash; AI capabilities evolve through stages. A model that is incapable of causing harm is not the same as a model that is genuinely aligned. Safety approaches must evolve *with* the system, not be bolted on after the fact.

### Approach

I believe alignment is fundamentally a *multi-dimensional* problem. You can't solve it by looking at behavior alone, or internals alone, or governance alone. You need all four perspectives &mdash; the interior of the model, its observable behavior, the shared understanding of the people around it, and the institutional structures constraining it &mdash; working together. When any one dimension is neglected, the others eventually fail.

This is why I build open tools that bridge these dimensions: interpretability tools that connect internal representations to observable behavior, evaluation frameworks that inform governance decisions, and benchmarks designed to be useful to both researchers and policymakers. Everything is open-source because safety research behind closed doors doesn't make anyone safer.

### Tech

Python &middot; PyTorch &middot; HuggingFace Transformers &middot; TypeScript &middot; React &middot; NumPy &middot; CUDA &middot; Docker &middot; Linux

---

<p align="center"><em>If you're working on alignment, interpretability, or AI governance &mdash; I'd love to collaborate. Reach out.</em></p>
