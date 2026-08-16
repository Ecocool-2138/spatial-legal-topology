# Ontology v0.1

This is the first working vocabulary for Spatial Legal Topology. It is deliberately small and provisional.

## Node types

- `CONSTITUTIONAL_PROVISION`
- `STATUTE`
- `STATUTORY_PROVISION`
- `REGULATION`
- `TREATY`
- `COMMON_LAW_RULE`
- `INTERPRETIVE_CANON`
- `POWER`
- `DUTY`
- `DISCRETION`
- `RIGHT`
- `REMEDY`
- `POLICY`
- `DECISION`
- `FACT_PATTERN`

## Edge types

- `CONTAINS` — one legal rule defines the lawful space within which another operates.
- `CONSTRAINS` — limits the lawful exercise or meaning of another rule or power.
- `DISPLACES` — gives way to another rule where a valid priority rule requires it.
- `CONDITIONS` — makes the existence or exercise of one legal consequence dependent on another requirement.
- `INCORPORATES` — imports another text, norm or instrument into the operative legal scheme.
- `AUTHORISES` — creates or confers a legal power, jurisdiction or entitlement.
- `INTERPRETS` — affects the legally available meaning of another rule.
- `REMEDIES` — provides a mechanism capable of correcting breach or failure elsewhere in the graph.
- `TESTS` — supplies a standard against which another rule, decision or institutional process is assessed.
- `IMPLEMENTS` — gives domestic or operational effect to another norm.
- `APPLIES_TO` — connects a rule to a person, institution, class of conduct or fact pattern.

## Operator types

Operators are rules that alter how nodes or edges are resolved rather than simply adding another substantive obligation.

Initial candidates:

- treaty-consistent interpretation;
- principle of legality;
- harmonious construction;
- specific-over-general reasoning;
- jurisdictional-error consequence rules;
- consequence-of-breach analysis.

## Required metadata

Each node or relationship should, where applicable, carry:

- canonical identifier;
- title/short label;
- full source citation;
- jurisdiction;
- legal source type;
- effective-from date;
- effective-to date;
- authority level;
- proposition status: `RATIO`, `AUTHORITATIVE_DICTUM`, `OBITER`, `SECONDARY`, `PROPOSED`;
- verification state: `UNVERIFIED`, `AI_PROPOSED`, `HUMAN_VERIFIED`, `CONTESTED`;
- source passage or pinpoint;
- notes on conditions and exceptions.

## Design rule

No machine-generated legal relationship should silently become a verified rule.

**AI proposes; authorities support; humans verify.**
