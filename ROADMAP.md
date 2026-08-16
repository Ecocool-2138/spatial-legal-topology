# Roadmap

## Phase 0 — Define the experiment

- Freeze ontology v0.1 narrowly enough to test.
- Model *Project Blue Sky Inc v Australian Broadcasting Authority* [1998] HCA 28.
- Record every node and relationship with source and verification state.
- Produce one machine-readable graph file and one human-readable diagram.

## Phase 1 — Validate the representation

Ask independent reviewers from law, legal informatics and software/knowledge-graph backgrounds:

1. Does the graph preserve what the High Court actually did?
2. Does it expose relationships more clearly than ordinary linear notes?
3. Which relationships are misclassified or missing?
4. Which parts of the reasoning resist formal representation?

## Phase 2 — Add interpretive operators

Add one or two doctrines that operate on relationships rather than as ordinary substantive nodes, such as treaty-consistent interpretation and consequence-of-breach analysis.

## Phase 3 — Multi-jurisdiction stress test

Model a bounded problem involving several layers such as:

- international obligation;
- constitutional priority/allocation;
- Commonwealth legislation;
- State legislation;
- delegated or administrative power;
- policy/procedure;
- individual discretion;
- remedial mechanism.

## Phase 4 — AI-assisted extraction

Develop an ingestion workflow where AI:

1. identifies candidate legal propositions;
2. proposes nodes and relationships;
3. supplies source passages and pinpoints;
4. marks every proposition unverified;
5. submits candidates for human verification.

## Phase 5 — Prototype interface

Support queries such as:

- show everything that constrains node X;
- trace the authority path from X to Y;
- show contested/unverified edges;
- show the legal system at a selected date;
- show possible consequences if constraint X is breached.

## Success criterion

The project earns further development only if the model helps humans detect, explain or verify legally important structure that is materially harder to see in ordinary linear analysis.
