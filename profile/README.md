<div align="center">

# Spec-Driven Methodology

**Agent-first: AI agent does the work, humans keep control.**

Spec-Driven Methodology (SDM) — the methodology-as-specs approach to competency assessment and skills management. Instead of scattered job descriptions and one-off exams, SDM treats every competency as a *spec*: an ontology of skills, a content library, certification profiles, and a measurable coverage model — all versioned, all reviewable, all exportable.

![ontology → content → profiles → coverage → export](https://img.shields.io/badge/ontology-%E2%86%92%20content%20%E2%86%92%20profiles%20%E2%86%92%20coverage%20%E2%86%92%20export-cc7832)

</div>

---

## What is SDM?

A competency graph that lives in plain YAML and works with your tooling:

- **Ontology** — skills, topics, concepts, products, persons. Every node is a spec.
- **Content** — a library of questions, terms, and learning materials bound to the graph.
- **Profiles** — certification profiles and levels: who needs to master what, at which depth.
- **Coverage** — live calculation of certification coverage: green / yellow / red per skill.
- **Export** — tests, matrices, interview kits, Mermaid graphs, Confluence pages, learning packs.

## Repositories

| Repository | Purpose |
|---|---|
| [sdm-pages](https://github.com/spec-driven-methodology/spec-driven-methodology.github.io) | Organization site (GitHub Pages) — live examples, theme, brand |
| [methodology](https://github.com/spec-driven-methodology/methodology) | Methodology concept, ADRs, specification |
| [sdm](https://github.com/spec-driven-methodology/sdm) | Reference implementation: CLI, MCP server, npm package |

## Getting started

1. Explore the [live examples](https://spec-driven-methodology.github.io/examples/) — [Java Developer → Senior](https://spec-driven-methodology.github.io/examples/java-developer-senior.html), [AI Course Program](https://spec-driven-methodology.github.io/examples/ai-course.html), [Tech Conference Program](https://spec-driven-methodology.github.io/examples/tech-conference.html).
2. Read the methodology spec (`methodology` repo).
3. Bootstrap a slice: ontology → profile → coverage → export.

---

## License

All public content is licensed under the [Apache License 2.0](LICENSE) unless noted otherwise.