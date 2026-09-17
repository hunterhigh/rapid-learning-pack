---
name: rapid-learning-pack
description: Research, prioritize, and assemble complete source-backed knowledge packages with a high-value fast path and unrestricted access to the full material. Use when a user asks for a rapid domain primer, crash course, practical knowledge pack, or reusable learning resource; do not use for ordinary one-off explanations or certification-specific curricula.
---

# Rapid Learning Pack

Build a navigable knowledge product, not a teacher-controlled course. Give the user the information, evidence, priorities, and paths needed to learn at their own pace.

## Invariants

- Do not infer, test, grade, or manage the user's ability to understand or retain information unless the user explicitly requests assessment or adaptation.
- Make the complete package available immediately. A recommended sequence is navigation, never a release schedule or prerequisite gate.
- Treat a time target as a prioritization constraint, not a content cap. Unless the user specifies otherwise, make the highest-value 50–60% of the package reachable in a three-day fast path while retaining the rest as extended and reference material.
- Do not add homework, quizzes, exercises, spaced repetition, progress tracking, or motivational devices unless requested. Real examples and worked applications may appear inside the material.
- When requested subjects have independent bodies of knowledge or outcomes, create separate packages. They may share presentation infrastructure, not a blended curriculum.
- Optimize for useful breadth and transferable judgment rather than terminology count, academic completeness, or one project's architecture.

## Operating modes

- **Design:** Define the package architecture, evidence plan, priority rules, and delivery format without producing all content.
- **Build:** Research and deliver the populated package.
- **Update:** Recheck time-sensitive claims and sources, then revise priorities or content affected by new evidence.

Infer the mode from the request. Do not build the complete package when the user asks only for analysis or design.

## 1. Define the knowledge product

Establish:

- the domain boundary and meaningful exclusions;
- the work, decisions, or understanding the package should support;
- whether the request contains multiple independent packages;
- the user's time-to-value target and desired fast-path coverage;
- the intended surface, such as chat, document, site, or another navigable artifact.

Do not ask about proficiency merely to decide what information the user is allowed to receive. Ask a targeted question only when an unresolved choice would materially change scope, evidence requirements, or artifact form. Otherwise state reasonable assumptions and proceed.

## 2. Build the evidence base

Use model knowledge to propose structure, terminology, and search directions—not as sole authority for current, disputed, safety-relevant, or implementation-specific claims.

Research selectively from:

1. primary standards, official documentation, specifications, and original research;
2. authoritative applied references, mature design systems, engineering handbooks, and credible postmortems;
3. representative real-world artifacts and cases that test practical usefulness.

Distinguish stable principles, current product behavior, research findings, practitioner heuristics, inferences, and teaching examples. Cite claims in proportion to how current, contestable, or consequential they are.

Read [research-and-sourcing.md](references/research-and-sourcing.md) when planning or performing source research.

## 3. Prioritize and architect

Evaluate candidate content by:

- **work leverage:** what new work or judgment it enables;
- **transfer:** how broadly it applies across projects and tools;
- **frequency:** how often it is likely to matter;
- **dependency:** how much other useful knowledge depends on it;
- **error cost:** the consequence of misunderstanding or omitting it;
- **durability:** whether it remains useful without constant updating.

Classify content into three visible tiers:

- **Fast path:** the highest-value 50–60% that gives a coherent operating model within the stated rapid-learning window.
- **Extended:** material needed for broader coverage, nuance, and less frequent work situations.
- **Reference:** deep, specialized, vendor-specific, or lookup-oriented information.

The fast path must be coherent rather than a collection of summaries. Preserve dependency order inside the recommended route while allowing direct access to every module. For each included topic, be able to explain the work it supports, why its depth is appropriate, and why it belongs in its tier.

Read [package-architecture.md](references/package-architecture.md) when structuring the deliverable or its interaction model.

## 4. Deliver and validate

A populated package should make it easy to find both the whole field and the shortest valuable route through it. Include only components justified by the topic, typically:

- a domain map and full index;
- a clearly marked fast path and estimated scope coverage;
- modular explanations with mechanisms, boundaries, failure modes, and worked cases;
- decision aids, comparison tables, or checklists where they improve real work;
- a glossary and a source ledger;
- diagrams for sequences, structures, states, or relationships that prose would obscure.

Support natural-language questions. Answer directly first, then expose mechanism, application, boundaries, and evidence at the depth requested. Never force the user into a prescribed question format.

Before delivery, verify that:

- the package boundary matches the requested domain;
- independent subjects were not blended for convenience;
- the fast path contains the most consequential transferable knowledge, not merely the easiest material;
- every important current or contestable claim has suitable support;
- full content is accessible without passing a test or waiting for a schedule;
- the package explains what is primary, secondary, and reference material;
- examples illuminate the domain without narrowing it to one project;
- format and visuals reduce search and comprehension cost rather than decorate the output.
