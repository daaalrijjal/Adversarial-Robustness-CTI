# Adversarial-Robustness-CTI

## Project Overview

This repository documents a project focused on enhancing the security and trustworthiness of AI systems in cybersecurity. The work is divided into two phases:

1.  **Research & Framework:** A structured analysis of adversarial machine learning vulnerabilities and defenses from 2022–2025. This culminates in the proposal of a **Multi-Layered Adaptive Defense Framework** tailored for cybersecurity-oriented AI systems.
2.  **Implementation & Case Study:** A practical case study demonstrating the value of adversarial defenses by implementing and evaluating adversarial training on a **DistilBERT classifier** fine-tuned for Cyber Threat Intelligence (CTI) report classification.

---

## Repository Structure

| Folder/File | Description |
| :--- | :--- |
| **`Final-Paper.pdf`** | **The Research Paper:** *A Multi-Layered Adaptive Framework for Adversarially Robust AI in Cybersecurity Applications*. This document provides the literature review, vulnerability analysis, and the proposed defense framework. |
| **`Adversarial_Training_CTINL_Submit.ipynb`** | **The Implementation Notebook:** Contains the working code, data loading, training of both the baseline and adversarially trained DistilBERT models, and the final comparative evaluation of clean and robust accuracy. |
| `README.md` | This file. |

---

##  Live Presentation Link

You can view the interactive, published version of the slides here:

**[Live Project Presentation](https://ai-nlp-deep-dive.lovable.app)**

## Core Components & Key Contributions

### Phase 1: Multi-Layered Adaptive Defense Framework
* **Problem:** Existing AI defenses in critical infrastructure lack scalability, interpretability, and real-time adaptability against adversarial attacks.
* **Solution:** The proposed framework unifies three key elements into a closed feedback loop:
    1.  **Adversarial Detection:** Identifying subtle textual perturbations.
    2.  **Incremental Retraining:** Using detected attacks to continuously update the model.
    3.  **Explainable Auditing:** Maintaining transparency for security analysts by providing traceable rationales.

### Phase 2: Adversarial Training in CTI NLP
* **Model:** DistilBERT for sequence classification on Cyber Threat Intelligence (CTI) reports.
* **Defense Implemented:** Fast Gradient Sign Method (FGSM) adversarial training.
* **Evaluation:** The notebook compares the **Baseline Model** against the **Adversarially Trained Model** across crucial metrics:
    * Clean (Standard) Accuracy and Macro F1
    * Robust Accuracy under adversarial attack
    * Attack Success Rate (ASR)

---

## 📚 Data and External Resources

The reproducibility of this project relies on the following key external resources:

### Dataset

* **AnnoCTR Corpus:** The project uses the **AnnoCTR** dataset for training and evaluation of the CTI text classifier.
    * **Source:** [boschresearch/anno-ctr-lrec-coling-2024](https://github.com/boschresearch/anno-ctr-lrec-coling-2024)
    * **License:** CC-BY-SA 4.0
    * **Note:** The full dataset is not included in this repository due to size; please download it directly from the source repository above.
 
---

## Authors

* **Dana Alrijjal**
* **Jouri Aldaghma**
* **Dr. Naila Marir**
* **Course:** NLP Project – Effat University
