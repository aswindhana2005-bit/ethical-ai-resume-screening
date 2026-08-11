# Ethical AI Resume Screening System

An AI-assisted resume screening project designed to support skill-oriented candidate evaluation while investigating fairness, transparency, and bias in automated recruitment.

## Project Overview

The system aims to match candidate resumes with job descriptions and generate job-relevance scores.

The project is being developed in multiple phases:

- **Phase 1:** TF-IDF-based resume-job matching baseline
- **Phase 2:** Semantic matching using Sentence-BERT (SBERT)
- **Future:** Fairness-aware evaluation and bias mitigation
- **Future:** Explainable AI and web application deployment

---

# Phase 1 - TF-IDF Resume Screening

Phase 1 establishes a baseline resume-job matching system using traditional NLP techniques.

## Workflow

```text
Resume + Job Description
          ↓
    Text Preprocessing
          ↓
         TF-IDF
          ↓
   Cosine Similarity
          ↓
 Resume-Job Match Score
          ↓
       Ranking
          ↓
       Evaluation
