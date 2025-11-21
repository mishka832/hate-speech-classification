# Hate Speech Classification
# Fine-Grained Hate Detection

This repository contains code for **fine-grained hate speech classification** on social media comments. The project uses a **two-stage pipeline** combining zero-shot labeling with transformer-based models to categorize hateful content into specific subtypes.

---

## **Project Overview**
- **Objective:** Automatically classify hateful comments into subtypes such as:
  - Sarcasm-based hate
  - Humor-based hate
  - Metaphor-based hate
  - Political framing hate
  - Meme-language hate
- **Dataset:** [MetaHate Dataset](https://github.com/your-dataset-link) (extended with subtype pseudo-labels using zero-shot classification)
- **Methodology:**
  1. **Zero-Shot Labeling:** Using `facebook/bart-large-mnli` to assign hate subtypes.
  2. **Transformer Fine-tuning:** Models like RoBERTa, Twitter-RoBERTa, mobileBERT, and DistilBERT are fine-tuned for subtype classification.

---
## **Usage**
1. **Open the notebook in Google Colab**:
   - File → Open notebook → GitHub → Enter repo URL.
2. **Install dependencies** (if not already installed):
```bash
!pip install transformers torch scikit-learn pandas
```
3.Run cells step by step to train and evaluate the models.
## ** Collaborators **
Anjali 
Ishita Mangla
Kashish Singh
Mansi Manohar Khandare
Mishka Raheja
