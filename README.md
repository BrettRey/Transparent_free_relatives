# Transparent Free Relatives in SBCG

**A collaborative linguistic project analyzing the syntax and semantics of "Transparent Free Relatives" (TFRs) using Sign-Based Construction Grammar (SBCG).**

## Project Overview

Transparent Free Relatives (e.g., *what they call a foreigner*) present a challenge for constraint-based grammar because the "internal" predicate (*a foreigner*) appears to determine the "external" morphosyntactic properties of the clause (e.g., agreement, determination).

This project aims to model this "transparency effect" within the **Sign-Based Construction Grammar (SBCG)** formalism, developed by Sag, Boas, and Kay. Specifically, it investigates how the feature geometry in SBCG can account for the percolation of morphosyntactic features while maintaining the correct semantic composition.

## Key Files

*   **`sem-syn.tex`**: The main paper drafting the SBCG analysis of TFRs.
*   **`whose-what.tex`**: A companion note investigating similar "inside-out" determination in independent relative *whose* clauses.
*   **`NOTES.md`**: Working notes detailing the linguistic data, cross-linguistic parallels, and theoretical arguments.
*   **`refs.bib`**: Project bibliography.

## Collaboration Structure

This project is a **Human-AI-Human** collaboration in linguistic theory:

1.  **Primary Author**: Brett Reynolds (Humber Polytechnic & University of Toronto).
2.  **Collaborator**: Jong-Bok Kim (Kyung Hee University) – Providing expertise on SBCG and HPSG.
3.  **AI Agents**: Creating, drafting, and editing content as part of an experimental "Advanced Agentic Coding" workflow.

## Build

The project uses a standard LaTeX `make` workflow:

```bash
make        # Full build
make quick  # Single pass build
```
