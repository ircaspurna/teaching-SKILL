# UIPR Framework: Structured Pedagogical Method for AI-Assisted Learning

A domain-agnostic teaching methodology that transforms large language models into effective, structured tutors for any subject.

## What is UIPR?

**UIPR** (Understand → Intuit → Practice → Reconstruct) is a research-based pedagogical framework designed for AI-assisted learning environments. It synthesizes established principles from learning science into a cohesive, repeatable system that can be implemented as instructional guidance for LLMs serving as personalized tutors.

Unlike typical AI tutor prompts that focus on *configuring output parameters* (depth, tone, style), this framework encodes **pedagogical methodology** — the specific sequences, decision rules, and adaptive patterns that make teaching effective.

### The Four Stages

```
U — Understand:   What problem does this solve? Why does it exist?
I — Intuit:       Build the mental model before formulas or procedures
P — Practice:     Implement immediately, hands-on
R — Reconstruct:  Explain it back, teach it, identify gaps
```

## Repository Contents

### 📘 [UIPR_Teaching_Framework.md](UIPR_Teaching_Framework.md)
The theoretical foundation and research grounding. Read this to understand:
- **Why** the framework is structured this way
- The research basis (Kolb, Bruner, Rosenshine, Kapur, Feynman, and more)
- How UIPR relates to existing learning theories
- Implementation guidance for LLM-based tutoring systems

**Best for:** Educators, instructional designers, researchers, and anyone wanting to understand the pedagogical principles.

### 🛠️ [UIPR_SKILL.md](UIPR_SKILL.md)
The practical implementation template. Use this to:
- **Configure** an AI tutor for any specific domain
- Get session-by-session teaching protocols
- Access ready-to-use explanation patterns and questioning strategies
- Implement the framework immediately

**Best for:** Practitioners building AI tutors, educators using LLMs for teaching, learners creating custom learning experiences.

## Quick Start

### For Educators & Instructional Designers

1. Read [UIPR_Teaching_Framework.md](UIPR_Teaching_Framework.md) to understand the methodology
2. Use [UIPR_SKILL.md](UIPR_SKILL.md) as a template — fill in the `[BRACKETED]` sections with your domain, learner profile, and curriculum
3. Provide the completed skill document to your LLM as system instructions

### For AI Researchers & Developers

- The framework provides a structured approach to prompt engineering for educational applications
- Section 10 of the Framework document includes an LLM instruction template
- The methodology is designed to be model-agnostic and works with any sufficiently capable LLM

### For Self-Directed Learners

- Customize UIPR_SKILL.md with your learning goals and preferred domain examples
- Use it to guide your conversations with AI tutors (ChatGPT, Claude, etc.)
- Follow the UIPR cycle for each concept you study

## Core Principles

The framework is built on five teaching calibration rules:

1. **Never give formulas without intuition first** — Build conceptual understanding before introducing formal representations
2. **Never show a procedure without explaining the "why"** — Every step connects to a reason
3. **Never introduce theory without a concrete anchor** — Start with problems or examples
4. **Always connect to the learner's domain** — Use the learner's context when illustrating concepts
5. **Embrace productive confusion** — Confusion is a learning signal; work through it, not around it

## The Explanation Stack

When introducing any concept, the framework follows this eight-step sequence:

1. What problem does this solve?
2. How would you solve it naively?
3. Why doesn't that work well?
4. What's the key insight?
5. How does the solution implement that insight?
6. What's the formal representation?
7. What does it look like in practice?
8. What are the edge cases and gotchas?

## Domain-Agnostic Design

The UIPR Framework can be applied to teaching:
- Technical subjects (programming, data science, mathematics)
- Humanities (literature, art history, philosophy)
- Professional skills (financial modeling, sentiment analysis, clinical reasoning)
- Creative disciplines (music theory, composition, design)

The methodology stays the same; only the domain-specific examples and anchor content change.

## Research Foundation

The framework integrates and builds upon:
- **Kolb's Experiential Learning Cycle** (1984)
- **Bruner's Concrete-Representational-Abstract** model (1966)
- **Rosenshine's Principles of Instruction** (2012)
- **Kapur's Productive Failure** research (2008, 2012)
- **The Feynman Technique** for learning through teaching
- **Vygotsky's Zone of Proximal Development** (1978)
- **Testing Effect** research (Roediger & Karpicke, 2006)

Full references available in [UIPR_Teaching_Framework.md](UIPR_Teaching_Framework.md).

## Example Use Cases

### Technical Education
```
Domain: Python & Machine Learning
Anchor examples: Product review classification, sentiment analysis
Practice format: Write and run code
Result: Learner builds working NLP tools for their domain
```

### Humanities
```
Domain: Art History
Anchor examples: Comparative analysis across periods
Practice format: Written analysis, visual interpretation
Result: Learner produces well-reasoned critical essays
```

### Professional Skills
```
Domain: Financial Modeling
Anchor examples: Public company valuations, 10-K analysis
Practice format: Build spreadsheet models
Result: Learner creates DCF models with sensitivity analysis
```

## Contributing

This framework is published as a **living document**. Practitioners are encouraged to:
- Adapt and extend the methodology for new domains
- Share examples of successful implementations
- Contribute improvements based on practical experience
- Report what works (and what doesn't) in real teaching contexts

## License

This framework is published under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

**You are free to:**
- Share — copy and redistribute the material
- Adapt — remix, transform, and build upon the material for any purpose

**Under these terms:**
- Attribution — Give appropriate credit, provide a link to the license, and indicate if changes were made

## Citation

If you use this framework in academic work, please cite:

```
UIPR Framework: A Structured Pedagogical Method for AI-Assisted Learning
Version 1.0 (2025)
https://github.com/[your-username]/uipr-framework
Licensed under CC BY 4.0
```

## Contact & Feedback

- **Issues**: Report bugs, suggest improvements, or ask questions via GitHub Issues
- **Discussions**: Share your implementations and experiences

---

*Developed through iterative practice in AI-assisted technical education and refined across multiple learning contexts.*
