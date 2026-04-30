# Graph Report - .  (2026-04-28)

## Corpus Check
- Corpus is ~13,739 words - fits in a single context window. You may not need a graph.

## Summary
- 44 nodes · 46 edges · 6 communities detected
- Extraction: 85% EXTRACTED · 13% INFERRED · 2% AMBIGUOUS · INFERRED: 6 edges (avg confidence: 0.79)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Economic Impact|Economic Impact]]
- [[_COMMUNITY_OpenAI Governance|OpenAI Governance]]
- [[_COMMUNITY_Responsible AI Controls|Responsible AI Controls]]
- [[_COMMUNITY_Automation Methodology|Automation Methodology]]
- [[_COMMUNITY_AI Ethics Practice|AI Ethics Practice]]
- [[_COMMUNITY_Business Use Cases|Business Use Cases]]

## God Nodes (most connected - your core abstractions)
1. `Generative AI Productivity Value` - 5 edges
2. `Use Case Lens` - 5 edges
3. `Tech Ethics by Design` - 5 edges
4. `OpenAI Governance Interview` - 5 edges
5. `Responsible AI Risks` - 4 edges
6. `Labor Market Disruption` - 4 edges
7. `Productivity Growth Boost` - 4 edges
8. `Generative AI` - 3 edges
9. `Workforce Transformation` - 3 edges
10. `Task Automation` - 3 edges

## Surprising Connections (you probably didn't know these)
- `Tech Ethics by Design` --semantically_similar_to--> `Responsible AI Risks`  [INFERRED] [semantically similar]
  graphify-out/transcripts/yt_87d60db59e61.txt → raw/The economic potential of generative AI The next productivity frontier.md
- `Tax on Capital` --conceptually_related_to--> `Labor Market Disruption`  [INFERRED]
  graphify-out/transcripts/yt_a1753a01ab1b.txt → raw/The Potentially Large Effects of Artificial Intelligence on Economic Growth (BriggsKodnani).md
- `Generative AI` --semantically_similar_to--> `Generative AI`  [INFERRED] [semantically similar]
  raw/The Potentially Large Effects of Artificial Intelligence on Economic Growth (BriggsKodnani).md → raw/The economic potential of generative AI The next productivity frontier.md
- `Productivity Growth Boost` --semantically_similar_to--> `Generative AI Productivity Value`  [INFERRED] [semantically similar]
  raw/The Potentially Large Effects of Artificial Intelligence on Economic Growth (BriggsKodnani).md → raw/The economic potential of generative AI The next productivity frontier.md
- `Labor Market Disruption` --semantically_similar_to--> `Workforce Transformation`  [INFERRED] [semantically similar]
  raw/The Potentially Large Effects of Artificial Intelligence on Economic Growth (BriggsKodnani).md → raw/The economic potential of generative AI The next productivity frontier.md

## Hyperedges (group relationships)
- **McKinsey Two-Lens Value Analysis** — mckinsey_productivity_value, mckinsey_use_case_lens, mckinsey_work_activity_lens [EXTRACTED 1.00]
- **IBM Tech Ethics by Design Flow** — ibm_tech_ethics_by_design, ibm_layers_of_effect, ibm_dichotomy_mapping, ibm_ethical_hacking [EXTRACTED 1.00]
- **Participatory AI Governance** — openai_government_guardrails, openai_equity_feedback_nudging, openai_value_consensus_governance, openai_love_humanity_alignment [INFERRED 0.80]

## Communities

### Community 0 - "Economic Impact"
Cohesion: 0.22
Nodes (10): Adoption Timeline Uncertainty, Global GDP Increase, Labor Market Disruption, New Job Creation, Productivity Growth Boost, Generative AI Productivity Value, Rationale for Two Complementary Impact Lenses, Work Activity Lens (+2 more)

### Community 1 - "OpenAI Governance"
Cohesion: 0.29
Nodes (8): OpenAI Governance Interview, Government and Society Guardrails, Love Humanity Alignment Goal, Nonprofit to For-Profit Structure, Rationale for For-Profit Structure, Scaling Research Capital Needs, AI for Scientific Discovery, Value Consensus Governance

### Community 2 - "Responsible AI Controls"
Cohesion: 0.29
Nodes (7): Role of AI in Enhancing Data Governance Strategies, Dichotomy Mapping, Ethical Hacking, Layers of Effect, Tech Ethics by Design, Rationale for Human-in-the-Loop Checks, Responsible AI Risks

### Community 3 - "Automation Methodology"
Cohesion: 0.29
Nodes (7): Generative AI, Job Exposure Estimates, O*NET Automation Methodology, Rationale for O*NET Automation Method, Task Automation, Foundation Models, Generative AI

### Community 4 - "AI Ethics Practice"
Cohesion: 0.29
Nodes (7): AI Ethics, Consent-Based AI, Design Thinking for AI, Diversity and Inclusivity, Rationale for Diverse AI Teams, Sociotechnical Trust in AI, Equity Nudging Through Feedback Loops

### Community 5 - "Business Use Cases"
Cohesion: 0.4
Nodes (5): Customer Operations, Marketing and Sales, Research and Development, Software Engineering, Use Case Lens

## Ambiguous Edges - Review These
- `Responsible AI Risks` → `Role of AI in Enhancing Data Governance Strategies`  [AMBIGUOUS]
  raw/View of The Role of AI in Enhancing Data Governance Strategies.md · relation: conceptually_related_to

## Knowledge Gaps
- **22 isolated node(s):** `Foundation Models`, `Customer Operations`, `Marketing and Sales`, `Software Engineering`, `Research and Development` (+17 more)
  These have ≤1 connection - possible missing edges or undocumented components.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What is the exact relationship between `Responsible AI Risks` and `Role of AI in Enhancing Data Governance Strategies`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **Why does `Responsible AI Risks` connect `Responsible AI Controls` to `Economic Impact`?**
  _High betweenness centrality (0.555) - this node is a cross-community bridge._
- **Why does `Tech Ethics by Design` connect `Responsible AI Controls` to `AI Ethics Practice`?**
  _High betweenness centrality (0.551) - this node is a cross-community bridge._
- **Why does `Workforce Transformation` connect `Economic Impact` to `Responsible AI Controls`?**
  _High betweenness centrality (0.527) - this node is a cross-community bridge._
- **What connects `Foundation Models`, `Customer Operations`, `Marketing and Sales` to the rest of the system?**
  _22 weakly-connected nodes found - possible documentation gaps or missing edges._