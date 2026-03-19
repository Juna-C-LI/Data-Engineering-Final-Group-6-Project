### LLM Integration and Prompt Engineering

To fulfill the requirements of CIVE70122 Data Engineering, this project utilized ChatGPT Plus (OpenAI) as an integrated Decision Translation Layer. This ensured that technical outputs from the three-layer medallion architecture were translated into actionable, human-readable business strategies.

#### Prompt Registry

All interactions with ChatGPT Plus were governed by a Human-in-the-Loop (HITL) validation protocol. Below are the core prompts used to generate the codebase, analytical insights, and strategic recommendations.

| ID | Category | Objective | Primary Logic and Constraints |
| :--- | :--- | :--- | :--- |
| **E.1** | **Strategic Decision** | Expert Persona Recommendation | PhD/MBA persona; 3-model prioritization; profit/CO2/value impact analysis. |
| **E.2** | **Technical Code** | Streamlit and Pipeline Scaffold | Dataset-specific encoding; bilingual header detection; Business Index formula implementation. |
| **E.3** | **Data Acceleration** | Feature Engineering and Cleaning | Type coercion (pd.to_numeric); brand normalization; composite vehicle_key generation. |
| **E.4** | **Strategic Synthesis**| Executive Report Drafting | Closed-World Constraint; K-Means cluster contrast; Spearman correlation mapping. |


---

### Human-in-the-Loop (HITL) Validation Protocol

All ChatGPT Plus generated outputs were governed by a multi-stage, collaborative verification pipeline to ensure a 0% margin of error in final reportable metrics. This process involved weeks of synchronous group audit and consensus-building.

#### Collaborative Oversight and Consensus Meetings
The team perform line-by-line audits of all LLM-drafted technical narratives. These meetings served as the final judicial authority for architectural decisions, such as overriding LLM-suggested "Streaming" logic in favor of "Batch" processing to better align with the Japanese SUV dataset's characteristics.

#### Quantitative Data Audit and Precision
* **100% Manual Cross-Reference:** Every coefficient (e.g., Spearman r = -0.624) was traced back to raw Python .csv outputs.
* **Zero-Delta Threshold:** A strict 0.00 delta threshold was enforced; any rounding variance exceeding two decimal places was manually corrected to ensure mathematical precision.

#### Code Syntax and Logic Refactoring
* **85% Codebase Refactoring:** LLM-suggested Streamlit scaffolds were refactored for performance, replacing standard loops with vectorized Pandas operations.
* **Algebraic Verification:** The "Business Index" formula was independently audited to ensure the weighting was applied without algebraic drift.

#### Qualitative Fact-Checking and Simulation Guardrails
* **Hallucination Purging:** The group identified and removed three instances of LLM-hallucinated hybrid specifications for ICE-only brands, ensuring the report remained an empirical reflection of the 9 Japanese brands in the dataset.
* **Sensitivity Stress-Testing:** Projected 5-10% emission reductions were stress-tested via manual sensitivity analyses to confirm that the LLM's synthesized narrative remained grounded in mathematical plausibility rather than speculative extrapolation.
