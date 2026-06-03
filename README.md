# Smart Resume Search Engine

## Overview

This project implements a semantic resume search engine using Gemini Embeddings and FAISS.

A recruiter can enter a job description in plain English and the system retrieves the most relevant candidates based on semantic similarity rather than exact keyword matching.

## Features

- Gemini Embeddings (gemini-embedding-001)
- Resume Embedding Storage
- NumPy-based Cosine Similarity Search
- FAISS Vector Search
- Semantic Candidate Matching
- Threshold-based Filtering
- Multiple Job Description Testing

## Dataset

20 candidate resumes containing a mix of:

- Software Developers
- Machine Learning Engineers
- Data Analysts
- HR Executives
- Business Analysts
- Designers
- Marketing Professionals

## Technologies Used

- Python
- Google Gemini API
- NumPy
- FAISS
- Google Colab

## Files

- smart_resume_search.ipynb
- resumes.npy
- resumes_meta.json

## Example

Job Description:

Looking for a Machine Learning student with Python, pandas, scikit-learn and predictive analytics experience.

Top Match:

Shweta Gaikwad
Machine Learning and Software Development Student

## Semantic Search Advantage

Traditional keyword search relies on exact words.

Semantic search uses embeddings and can identify relevant candidates even when different terminology is used in the resume and job description.