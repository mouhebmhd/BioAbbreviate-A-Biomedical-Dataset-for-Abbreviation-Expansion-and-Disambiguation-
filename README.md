# BioAbbreviate: A Biomedical Dataset for Abbreviation Expansion and Disambiguation

![License](https://img.shields.io/badge/license-CC%20BY%204.0-blue)
![Dataset Version](https://img.shields.io/badge/version-1.0-green)
![NLP Task](https://img.shields.io/badge/task-Abbreviation%20Expansion-orange)

**BioAbbreviate** is a large-scale, curated dataset for abbreviation detection, expansion, and disambiguation in biomedical texts. It is designed to support NLP tasks such as text simplification, translation, information retrieval, and health literacy enhancement.

---

## 📌 Overview

Medical abbreviations are pervasive in biomedical literature but introduce ambiguity, translation issues, and comprehension barriers for non-experts. This dataset addresses these challenges by providing:

- **923,336** research papers from PubMed, PLOS, and PMC Europe
- **269,319** PLOS documents with structured abbreviation sections
- Automatically extracted abbreviation–expansion pairs
- Rich contextual information (sentence-level co-occurrence, text position)
- Support for training and evaluating NLP models (e.g., BioBERT, BERT, RoBERTa)

---

## 📂 Dataset Structure

The dataset is organized as follows:

### 📊 Key Statistics

- **Abbreviation length**: 67% are 2–3 characters
- **Expansion length**: 74% are derived from 2–3 token phrases
- **Ambiguity**: 36.5% of abbreviations have ≥2 expansions
- **Sources**: PubMed, PLOS, PMC Europe

---

