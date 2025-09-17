# Endometriosis Ontology for LLM-Guided MRI Reporting

This repository accompanies the study *“Improving Reliability of GPT-5 MRI Reports with an Endometriosis Guideline Ontology: A Proof-of-Concept”*.  
It provides the ontology and example outputs used in the evaluation experiments.

---

## Contents

| File | Description |
|------|-------------|
| `endometriosis ontology.rdf` | The ontology encoding the ESHRE 2022 guideline for endometriosis. Includes recommendations, patient groups, metadata on evidence/strength, and mappings to SNOMED CT. |
| `Patient 1 Recs.csv` | CSV output from a SPARQL query for Case 1. Used in the SPARQL-RAG simulation to provide patient-specific recommendations. |
| `Patient 2 Recs.csv` | CSV output from a SPARQL query for Case 2. Used in the SPARQL-RAG simulation. |

---

## How This Relates to the Paper

- **SPARQL queries**: The full queries used to generate the CSVs are shown in the *Methodology* section and Figures 2–3 of the paper.  
- **Evaluation metrics**: Precision, recall, F1, coverage, subset adherence, traceability, hallucination rates, and other metrics are described in detail in the *Methodology*.  
- **Experimental setup**: The two patient cases are described in the *Methods* section, and the CSVs here represent the outputs fed into GPT-5 during the RAG condition.

---

## Usage

1. Open `endometriosis ontology.rdf` in Protégé or another ontology editor to explore the structure.  
2. Inspect the CSV files to see the exact recommendations retrieved for each test case.  
3. Cross-reference with the SPARQL queries in the paper to understand how these results were produced.  

---

## Citation

If you use the ontology or outputs, please cite:

> Margraf, A. (2025). Improving Reliability of GPT-5 MRI Reports with an Endometriosis Guideline Ontology: A Proof-of-Concept.

---
