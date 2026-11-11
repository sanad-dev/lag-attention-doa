# Graph Report - lag-attention-doa  (2026-11-10)

## Corpus Check
- Corpus is ~298 words - fits in a single context window. You may not need a graph.

## Summary
- 14 nodes · 14 edges · 2 communities
- Extraction: 79% EXTRACTED · 21% INFERRED · 0% AMBIGUOUS · INFERRED: 3 edges (avg confidence: 0.85)
- Token cost: 81,807 input · 0 output

## Community Hubs (Navigation)
- DoA Research Paper
- Graphify Tooling Setup

## God Nodes (most connected - your core abstractions)
1. `Learning Surrogate Covariances with Lag Attention for DoA Estimation under Coherent Multipath and Array Errors` - 7 edges
2. `graphify Knowledge Graph (graphify-out/)` - 5 edges
3. `Surrogate Covariance Learning` - 3 edges
4. `Lag Attention` - 2 edges
5. `DoA Estimation` - 2 edges
6. `graphify Skill` - 1 edges
7. `Query Graph Before Grep Rule` - 1 edges
8. `graphify update (AST-only rebuild)` - 1 edges
9. `GRAPH_REPORT.md` - 1 edges
10. `graphify wiki index.md` - 1 edges

## Surprising Connections (you probably didn't know these)
- `graphify Skill` --conceptually_related_to--> `graphify Knowledge Graph (graphify-out/)`  [INFERRED]
  .claude/CLAUDE.md → CLAUDE.md

## Hyperedges (group relationships)
- **Lag-attention surrogate covariance for robust DoA under coherent multipath and array errors** — readme_lag_attention, readme_surrogate_covariance, readme_doa_estimation, readme_coherent_multipath, readme_array_errors [EXTRACTED 1.00]

## Communities (2 total, 0 thin omitted)

### Community 0 - "DoA Research Paper"
Cohesion: 0.32
Nodes (8): Array Errors, Coherent Multipath, DoA Estimation, Frontiers in Signal Processing, Lag Attention, lag-attention-doa Repository, Learning Surrogate Covariances with Lag Attention for DoA Estimation under Coherent Multipath and Array Errors, Surrogate Covariance Learning

### Community 1 - "Graphify Tooling Setup"
Cohesion: 0.33
Nodes (5): graphify Skill, GRAPH_REPORT.md, graphify Knowledge Graph (graphify-out/), graphify update (AST-only rebuild), graphify wiki index.md

## Knowledge Gaps
- **8 isolated node(s):** `graphify Skill`, `graphify update (AST-only rebuild)`, `GRAPH_REPORT.md`, `graphify wiki index.md`, `lag-attention-doa Repository` (+3 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 9 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Are the 2 inferred relationships involving `Surrogate Covariance Learning` (e.g. with `Lag Attention` and `DoA Estimation`) actually correct?**
  _`Surrogate Covariance Learning` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `graphify Skill`, `graphify update (AST-only rebuild)`, `GRAPH_REPORT.md` to the rest of the system?**
  _8 weakly-connected nodes found - possible documentation gaps or missing edges._