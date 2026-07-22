# Project 002 - Response Evaluation

This repository presents a standalone AI evaluation project focused on comparing paired customer-support responses, identifying the stronger answer, and documenting quality-review reasoning in a portfolio-ready format.

## Included Files

- `customer_support_response_evaluation_dataset.xlsx`
- `Annotation_Guidelines.docx`
- `QA_Checklist.docx`
- `Project_Summary.docx`
- `Project_Reflection.docx`
- `Application_Blurb.md`
- `analyze_dataset.py`
- `analysis_summary.md`
- `requirements.txt`

## Project Focus

The project evaluates paired customer-support responses using evidence-based criteria:
- factual accuracy
- helpfulness
- hallucination detection
- annotation rationale quality
- QA consistency

## Python Component

The repo includes a lightweight Python script that reads the Excel workbook and produces a Markdown summary of:
- preferred-response counts
- hallucination and safety-flag totals
- category distribution
- average scoring patterns
- inter-annotator agreement for the QA sample

Run it with:

`python analyze_dataset.py`

## Key Dataset Facts

- The main evaluation sheet contains 100 rows.
- Preferred responses are split evenly between A and B.
- Hallucinations are flagged in 25 rows.
- Safety flags remain `N` across the dataset.
- The IAA sample contains 20 valid ticket rows with 70.0% agreement.

## Portfolio Positioning

This is presented as a standalone evaluation project that combines annotation documentation with a small Python-based reporting workflow for customer-support response analysis.
