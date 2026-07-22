# Analysis Summary

Generated from `customer_support_response_evaluation_dataset.xlsx` using the repo's Python analysis workflow.

## Dataset Snapshot

- Total evaluation rows: 100
- IAA sample rows used: 20
- Inter-annotator agreement: 14/20 (70.0%)

## Preferred Response Counts

- A: 50
- B: 50

## Hallucination Flags

- N: 75
- Y: 25

## Safety Flags

- N: 100

## Category Breakdown

- Account: 20
- Billing: 20
- General Inquiry: 20
- Shipping: 20
- Technical Issue: 20

## Average Scores

- Accuracy A: 3.20
- Accuracy B: 3.32
- Helpfulness A: 3.31
- Helpfulness B: 3.46

## Notes

- Preferred responses split evenly between A and B in this dataset.
- Hallucination labels appear in 25 of 100 rows.
- The IAA worksheet includes footer content, so only valid ticket rows are counted.
- Example hallucination-marked tickets: T001, T004, T017, T019, T028, T030, T034, T036
