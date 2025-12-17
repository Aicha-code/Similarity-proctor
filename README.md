# Similarity Proctor

Similarity Proctor is a web-based machine learning system designed to detect semantic similarity in exam questionnaires. The system supports academic institutions in strengthening assessment quality and upholding exam integrity by identifying repeated, paraphrased, or closely matched exam questions before exams are administered.

---

## Problem Statement

While academic plagiarism detection tools are widely used to analyze student submissions, the validation of exam questionnaires themselves is often overlooked. This gap can lead to repeated questions across semesters, reduced assessment originality, and compromised academic standards.

Similarity Proctor addresses this problem by providing an automated, intelligent solution for exam questionnaire similarity detection using machine learning.

---

## System Overview

Similarity Proctor analyzes exam questionnaires by learning semantic patterns in text rather than relying on exact keyword matching. The system compares new questionnaires against previously submitted ones within the same academic module and generates actionable similarity reports for exam and quality assurance officers.

---

## Key Features

- Machine learning–based semantic similarity detection  
- Customizable similarity threshold set by administrators  
- Module-wise comparison to ensure domain relevance  
- Section-level similarity analysis and detection of recomposed past exams  
- Actionable similarity reports to support exam validation  
- Elastic and continuously evolving database   
- Two user interfaces: administrator and exam officer  

---

## Machine Learning Approach

The system’s similarity engine is built using a deep learning model based on a **Gated Recurrent Unit (GRU)**, selected for its efficiency in handling sequential text data and strong performance on smaller datasets. Word embeddings are used to capture semantic meaning, enabling detection of both exact and paraphrased similarities.

The model achieves an accuracy of approximately **81.69%** and a recall of **88.34%**.

---

## Technology Stack

- **Backend:** Python, Django  
- **Frontend:** JavaScript, HTML, CSS  
- **Machine Learning:** TensorFlow (GRU-based model)  
- **Database:** SQLite (elastic and continuously expanding)  

---

## Project Status

Similarity Proctor is currently at the **Minimum Viable Product (MVP)** stage and is ready for **pilot deployment** Future work includes large-scale deployment, continuous learning through real-world data, and further feature enhancements based on user feedback.

---

## Notes on Repository Content

This repository provides a **technical overview** of the project. The full implementation, trained models, and institutional data are not included, as they are part of an academic and institutional system. Additional details are available upon request.

---

## Author

**Aïchetou Abari Ilior**  
Computer Science Graduate, INES Ruhengeri  
Aspiring Machine Learning Engineer

