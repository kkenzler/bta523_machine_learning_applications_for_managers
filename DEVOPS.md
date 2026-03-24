# DEVOPS.md - bta523_machine_learning_applications_for_managers

Course workspace for **BTA 523: Machine Learning Applications for Managers**.

---

## Purpose

- Preserve the BTA 523 term project and its supporting dataset in one course-local folder
- Keep the notebook as the source of truth for analysis while retaining export/readout artifacts
- Make the dataset-to-notebook relationship obvious for future reuse or review

---

## Current Layout

```text
bta523_machine_learning_applications_for_managers/
  BTA523 (W26) Timeless Minds Term Project.ipynb
  BTA523 (W26) Timeless Minds Term Project.pdf
  BTA 523 (W26) Group Timeless Minds Term Project.docx
  Online Retail.xlsx
  online_retail.zip
```

---

## Working Rules

- Prefer editing the `.ipynb` notebook for analysis changes
- Treat the PDF and DOCX as derived/submission-facing artifacts unless the assignment specifically requires direct edits there
- Keep the dataset files beside the notebook unless size or clutter later justifies a `data/` split

---

## Observed Project Theme

- Project label: `Timeless Minds`
- Course framing: term project
- Dataset: UCI Online Retail
- Likely use case: customer behavior / churn-style prediction and managerial interpretation

## Portfolio Relevance

- strongest fit for retention, lifecycle, and churn-sensitive businesses
- useful talking point for Netflix-, Amazon-, ecommerce-, or subscription-style roles
- supports a narrative around comparing ML approaches for business decision support, not just model fitting

---

## Dependency Notes

The notebook itself references these packages:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `openpyxl`
- `requests`

---

## Next Useful Improvements

- add a short project summary section to the notebook or a sidecar note describing the final model choice and results
- add dataset acquisition notes if the local `.zip` and `.xlsx` are not meant to be the only source path
- standardize future export naming only if you produce multiple revisions
