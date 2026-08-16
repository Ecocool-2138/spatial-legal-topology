# Vision

## Problem

Complex legal meaning may depend on many interacting rules across different sources and jurisdictions. Humans can usually reason through one or two interactions sequentially, but error risk rises when the operative meaning is produced by a larger network of differently ranked, differently related rules.

## Hypothesis

A useful representation of complex law is not only text. It is a **typed legal graph**:

- nodes represent legal objects;
- edges represent legally meaningful relationships between them; and
- operators represent doctrines that alter how those relationships are resolved.

The graph should preserve hierarchy, direction, authority, time, uncertainty and provenance.

## Goal

Build a system that can answer questions such as:

> What rules constrain this power in these facts?

> What higher-order rule changes the lawful operating space of this discretion?

> What interpretive doctrine changes how two otherwise independent nodes interact?

> What consequence follows if a legal constraint is breached?

The system should expose the chain of authority rather than ask users to trust a generated conclusion.

## What this project is not

This project is not intended to:

- replace judges or lawyers;
- turn all legal judgment into deterministic computation;
- treat AI output as legal authority; or
- flatten contested propositions into false certainty.

## Research proposition

The first proposition to test is modest:

> Can a verified typed graph preserve the legal structure of a known difficult statutory interpretation problem more clearly than ordinary linear representation?

If that works, later models can test multi-jurisdiction constellations involving international law, constitutional rules, Commonwealth law, State law, delegated powers, policies, discretions and remedies.
