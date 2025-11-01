# 🌍 Language Identification Model

A high-precision, lightweight system for detecting **235 world languages**—powered by **Multinomial Naive Bayes** and **character n-gram** features.

---

## 📌 Overview

This model combines statistical elegance with linguistic insight to identify languages from even the briefest or noisiest text fragments. Trained on a meticulously balanced corpus of **235,000 paragraphs**—exactly **1,000 samples per language**—it achieves an impressive **91.93% top-1 accuracy** across a truly global set of languages, including major world tongues, regional dialects, and under-resourced scripts.

---

## 🧠 Key Characteristics

- **Algorithm**: Multinomial Naive Bayes  
- **Features**: Character-level n-grams (1–4 characters)  
- **Training Data**: 235,000 labeled paragraphs (1,000 per language)  
- **Language Coverage**: 235 languages across Latin, Cyrillic, Arabic, Devanagari, CJK, and many other writing systems  
- **Accuracy**: 91.93% on held-out test data  

---

## 🔍 Technical Insight

At its core, the model transforms raw text into a rich frequency profile of character sequences. These **character n-grams** act as linguistic fingerprints—capturing subtle patterns like:
- Common letter combinations (*e.g., "th" in English, "ch" in German*)
- Script-specific diacritics and glyphs
- Morphological rhythms unique to each language

By avoiding reliance on word-level semantics or large vocabularies, the approach remains robust for:
- **Short inputs** (tweets, headlines, search queries)  
- **Code-switched or mixed-script text**  
- **Low-resource languages** with limited digital presence  

The result is a model that is not only **fast** and **memory-efficient**, but also **interpretable** and **scalable**—ideal for real-time applications, edge devices, and multilingual pipelines.

---

> ✨ *Language is more than words—it’s rhythm, shape, and sound. This model listens to the silent music of characters.*