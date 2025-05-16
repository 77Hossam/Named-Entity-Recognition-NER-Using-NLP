# Named Entity Recognition (NER) Using NLP

A Named Entity Recognition (NER) project using Conditional Random Fields (CRF) to classify words in text into categories such as names of people, organizations, locations, expressions of time, quantities, monetary values, percentages, and more.

**Made by:** Hossam Eldeen Anwer  
**Date:** July 21, 2024

---

## 📌 Project Overview

This project aims to build a CRF-based model for NER using a custom dataset. It includes a baseline model and an advanced experiment that incorporates Part-of-Speech (POS) tags as additional features.

---

## 📁 Dataset Description

The dataset is a preprocessed version of a larger annotated corpus. It contains:

- **47,959 instances**
- **2 columns**: 
  - `text` – raw text
  - `labels` – NER tags (space-separated)
- **17 named entity types**, plus `O` (for non-entity tokens)

Example:
```text
text:   "The NASA Missions ."
labels: "B-art I-art I-art O"
