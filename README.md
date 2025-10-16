# Supplementary Data for "SCALE: Dialogical Cognition as the Algorithmic Engine of Far Transfer"

This repository contains the supplementary data for the manuscript by Zachary Robert Bennett.

**Paper Title:** SCALE: Dialogical Cognition as the Algorithmic Engine of Far Transfer
**Author:** Zachary Robert Bennett
**Preprint:** [coming soon]

---

## Description

This repository contains the data supporting the **Algorithmic Proof-of-Concept** (Section 4.5 of the manuscript). This includes:
1.  The **fine-tuning data** used to train a large language model (LLM) to emulate the five-stage SCALE framework.
2.  The **key model responses** from the fine-tuned model, which are analyzed in the paper to demonstrate structural fidelity, principle quality, cross-route transfer, and the scaffolding effect.

---

## Data Files

This repository contains the following files:

### 1. Model Outputs (Primary Evidence)

This is the most important file for verifying the claims made in the paper. It contains the specific outputs from the *already fine-tuned* model.

*   **[finetuned-model-responses.md](./finetuned-model-responses.md)**: A human-readable Markdown file containing the detailed model outputs that are discussed in the "Key Findings," "Cross-Route Transfer," and "Scaffolding Discovery" sections of the manuscript.

### 2. Fine-Tuning Data

These are the prompt-completion pairs that were used to train and validate the model.

*   **[finetune-data.md](./finetune-data.md)**: A human-readable Markdown version of the 12 primary prompt-completion pairs used as the core training and validation set.

*   **[finetune-data.json](./finetune-data.json)**: The raw, machine-readable JSON file containing the 12 primary prompt-completion pairs. This file is intended for researchers who may wish to replicate the fine-tuning process.

*   **[bonus-finetune-data.json](./bonus-finetune-data.json)**: An additional set of prompt-completion pairs that were part of the broader training data but not explicitly detailed in the manuscript. This is provided for researchers interested in the full training set.

---

## Usage & Licensing

This data is made available under the [Creative Commons Attribution 4.0 International (CC-BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license. You are free to share and adapt this material for any purpose, provided you give appropriate credit to the original author and paper.

For any questions, please contact Zachary Robert Bennett at [z@motionabstract.org](mailto:z@motionabstract.org).
