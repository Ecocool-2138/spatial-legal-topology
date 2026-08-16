# Spatial Legal Topology

An open research and software project exploring whether complex legal interpretation can be represented as a **typed graph of rules, powers, constraints, authorities and interpretive operators**.

The core hypothesis is simple:

> Legal meaning in complex systems can be an emergent property of a network of interacting rules, not merely a property of one text read in isolation.

The project aims to make that network inspectable. AI may assist with extraction and candidate relationships, but **legal authority and human verification remain the source of truth**.

## First proof case

The first bounded test is *Project Blue Sky Inc v Australian Broadcasting Authority* [1998] HCA 28. The immediate question is whether a small graph can faithfully represent the relationship between statutory power, statutory constraint and incorporated international obligations before attempting harder multi-jurisdiction models.

## Initial model

We distinguish three basic objects:

- **Nodes** — legislation, provisions, constitutional rules, treaties, common-law rules, powers, duties, discretions, remedies and policies.
- **Edges** — typed relationships such as `CONSTRAINS`, `CONTAINS`, `DISPLACES`, `CONDITIONS`, `INCORPORATES`, `AUTHORISES`, `INTERPRETS`, `REMEDIES` and `TESTS`.
- **Operators** — doctrines or interpretive rules that affect how nodes and edges are resolved, such as canons of construction.

Every asserted relationship should carry its source, jurisdiction, temporal scope, authority status and verification state.

## Development principle

**AI proposes; authorities support; humans verify.**

The project is exploratory. It does not provide legal advice and does not assume that every aspect of legal reasoning can or should be formalised.

## Current stage

`v0.1` — ontology and first worked model.

See [VISION.md](VISION.md), [ONTOLOGY.md](ONTOLOGY.md), [ROADMAP.md](ROADMAP.md), and the first example under [`examples/project-blue-sky`](examples/project-blue-sky/).

## Contributing

Different disciplines are welcome: law, legal informatics, knowledge graphs, AI/NLP, software engineering, visualisation and jurisprudence. See [CONTRIBUTING.md](CONTRIBUTING.md).

## Licence

Apache License 2.0. See [LICENSE](LICENSE).
