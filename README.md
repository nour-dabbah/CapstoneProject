# Authorship Attribution of Arabic Texts using the Deep Impostors Method

## 📌 Project Overview
This project presents a research framework for **authorship attribution of Arabic texts** using the **Deep Impostors methodology**.  
The goal of authorship attribution is to identify the most likely author of a given text by analyzing stylistic writing patterns rather than topical content.

The proposed framework adopts an **extrinsic, impostor-based approach**, where authorship is inferred through **relative stylistic comparison** instead of direct multi-class classification. Texts are analyzed at the **segment level**, allowing the system to capture stylistic variation across long documents.

This repository accompanies **Final Project – Phase A** at Braude College of Engineering and focuses on the **research design and methodological framework**.

---

## 👩‍💻 Authors
- **Nour Dabbah**  
- **Nuwar Dabbah**

---

## 🎓 Academic Information
- **Institution:** Braude College of Engineering  
- **Department:** Software Engineering  
- **Course:** Final Project – Phase A (61998)  
- **Project ID:** 26-1-R-15  

### Advisors
- **Dr. Renata Avros**  
- **Prof. Zeev Volkovich**

---

## 🧠 Research Motivation
Authorship attribution in Arabic poses significant challenges due to:
- Rich morphology and clitic attachment  
- Orthographic variation and lack of diacritics  
- Stylistic diversity across authors and historical periods  

Most existing computational approaches rely on closed-set classification and are often optimized for modern Arabic texts. This project explores the suitability of the **Deep Impostors framework** for Arabic authorship attribution, aiming to provide a more robust and stylistically focused alternative.

---

## 🏗️ Methodology Summary
The proposed research framework follows these main stages:

1. Arabic text preprocessing and normalization  
2. Segmentation of texts into fixed-length batches  
3. Contextual embedding extraction using **AraBERT**  
4. Impostor-based binary classifier training  
5. Segment-level stylistic decision generation  
6. Stylometric signal construction  
7. Signal comparison using **Dynamic Time Warping (DTW)**  
8. Anomaly detection and clustering for authorship attribution  

The final authorship attribution decision is based on the consistency of stylistic signals relative to impostor authors.

---

## 📂 Repository Structure
