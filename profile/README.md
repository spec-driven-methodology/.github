<div align="center">

# Spec-Driven Methodology

**Agent-first: AI agent does the work, humans keep control.**

Spec-Driven Methodology (SDM) — the methodology-as-specs approach to competency assessment and skills management. SDM treats every competency as a *spec*: an ontology (nodes of any kind), certification profiles, and a measurable coverage model — all versioned, all reviewable, all exportable.

![Specification → Computation → Presentation](https://img.shields.io/badge/Specification-%E2%86%92%20Computation%20%E2%86%92%20Presentation-cc7832)

</div>

---

## Two views

| View | Question | Shape |
|---|---|---|
| **Layers (artifacts)** | What is the methodology made of? | Specification → Computation → Presentation |
| **Lifecycle (usage)** | How is it executed end to end? | Human Intent → Agent + LLM → CLI / MCP / Skills → SDM → Specs YAML |

### Layers (static)

| Layer | What | Changes |
|---|---|---|
| **Specification** | Ontology (nodes of any `kind`: skills, questions, terms, topics...) + Profile + Gap definition | Rarely |
| **Computation** | Coverage — gap nodes under a fixed measure | Iteratively |
| **Presentation** | Export (tests, matrices, kits, MCP, CLI, web — delivery mechanics) | Fully open |

Content (questions, terms) is **part of the ontology** — nodes with their own `kind`, not a separate layer.

### Lifecycle (dynamic)

> Human Intent → Agent + LLM → CLI / MCP / Skills → SDM → Specs YAML

The agent clarifies the intent, plans, confirms, executes within the SDM frame, and commits the result as versioned YAML specs.

## Repositories

| Repository | Purpose |
|---|---|
| [sdm-pages](https://github.com/spec-driven-methodology/spec-driven-methodology.github.io) | Organization site (GitHub Pages) — live examples, theme, brand |
| [methodology](https://github.com/spec-driven-methodology/methodology) | Methodology concept, ADRs, specification |
| [sdm](https://github.com/spec-driven-methodology/sdm) | Reference implementation: CLI, MCP server, npm package |

## Getting started

1. Explore the [live examples](https://spec-driven-methodology.github.io/examples/) — [Java Developer → Senior](https://spec-driven-methodology.github.io/examples/java-developer-senior.html), [AI Course Program](https://spec-driven-methodology.github.io/examples/ai-course.html), [Tech Conference Program](https://spec-driven-methodology.github.io/examples/tech-conference.html).
2. Read the methodology spec (`methodology` repo).
3. Bootstrap a slice: ontology → profile → coverage.

---

## License

All public content is licensed under the [Apache License 2.0](LICENSE) unless noted otherwise.