# Security Policy

## Project Scope

This repository is a **machine learning project** for ECG arrhythmia classification using the MIT-BIH dataset. It is intended for **academic and research purposes only**, not for deployment in clinical or production environments. :contentReference[oaicite:2]{index=2}

The code includes Jupyter notebooks and reports that demonstrate:
- Data preprocessing
- Model training and evaluation (SVM, Random Forest, MLP)
- Performance comparison using accuracy, precision, recall, F1 score :contentReference[oaicite:3]{index=3}

---

## Supported Versions

| Version or Branch | Supported |
| ----------------- | --------- |
| `main` (latest)   | ✅ |
| older branches / forks | ❌ |

Only the `main` branch is actively maintained. Experimental or old forks may not receive updates.

---

## Reporting Security Issues

If you discover a vulnerability in this repository, please report it responsibly:

### How to Report
- **Do not** open a public GitHub issue.
- File a **private security advisory** or contact the maintainer via GitHub.

### What to Include
Please include:
- A clear description of the issue
- Steps to reproduce (if applicable)
- Potential risks (e.g., data handling, notebook execution issues)
- Suggested fix or mitigation (optional)

### Response Timeline
- Acknowledgement within **3–5 business days**
- Assessment and fix (where applicable) as soon as possible

---

## Data and Model Safety

This repository uses the **MIT-BIH Arrhythmia Dataset** (public ECG dataset) for educational classification tasks. Users of this repository should note:

- The dataset contains physiological data and should be handled with appropriate care
- Not intended for clinical decision-making
- Do not expose real patient data or credentials in the repo
- Any included `.env`, API keys, or private data **must be removed before publishing**

---

## Responsible Use

By using this repository, you agree not to:
- Deploy models for real-world medical diagnosis
- Use notebooks/scripts with sensitive data without proper consent
- Bypass security controls or run untrusted code without review

---

## Contribution Guidelines

Contributions are welcome. Please follow good practices:
- Keep code, notebooks, and data handling clean and readable
- Do not commit sensitive credentials or datasets
- Document significant experiments and results clearly
