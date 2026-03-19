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

### Human-in-the-Loop (HITL) Protocol

As documented in the attached images, all ChatGPT Plus generated outputs underwent:
1. **Quantitative Cross-Check:** All values (e.g., r = -0.624) were manually verified against the FULLjapanese.csv master file.
2. **Logic Verification:** Architectural decisions (Batch vs. Streaming) were debated by the team before implementing LLM-suggested scaffolds.
3. **Correction Ledger:** Any unsupported generalizations regarding profit uplift were re-classified as inferred estimates to maintain academic integrity.
