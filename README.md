# CBR Pidana Penadahan

## Project Description

This project implements a simple Case-Based Reasoning (CBR) system to retrieve similar criminal court decisions related to the crime of receiving stolen goods (Pidana Penadahan) using TF-IDF and Cosine Similarity.

Dataset consists of 30 Indonesian Supreme Court (Mahkamah Agung) decisions.

---

## Folder Structure

```
CBR_Pidana_Penadahan/
│
├── data/
│   ├── raw/
│   ├── processed/
│   ├── results/
│   └── eval/
│
├── notebooks/
│   ├── 01_case_base.ipynb
│   ├── 02_case_representation.ipynb
│   ├── 03_case_retrieval.ipynb
│   ├── 04_case_solution_reuse.ipynb
│   └── 05_evaluation.ipynb
│
├── logs/
├── README.md
└── requirements.txt
```

---

## Installation

Clone repository

```bash
git clone https://github.com/USERNAME/CBR_Pidana_Penadahan.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Running Pipeline

Run notebooks sequentially:

1. 01_case_base.ipynb
2. 02_case_representation.ipynb
3. 03_case_retrieval.ipynb
4. 04_case_solution_reuse.ipynb
5. 05_evaluation.ipynb

---

## Methods

- OCR Text Processing
- Text Cleaning
- TF-IDF Vectorization
- Cosine Similarity
- Case-Based Reasoning

---

## Output

The project generates:

- processed dataset
- retrieval results
- reuse solution
- evaluation report

---

## Author

Amanda Rachma Wijayanti
Informatics
Universitas Muhammadiyah Malang