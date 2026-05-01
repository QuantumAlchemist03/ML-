# Security Policy

## Project Scope

This repository is a machine learning project for ECG arrhythmia classification using the MIT-BIH dataset. It is intended for academic and research purposes only, not for deployment in clinical or production environments.

The code includes Jupyter notebooks and reports that demonstrate:
- Data preprocessing
- Model training and evaluation, including SVM, Random Forest, and MLP approaches
- Performance comparison using accuracy, precision, recall, and F1 score

---

## Supported Versions

| Version or Branch | Supported |
| ----------------- | --------- |
| `main` (latest)   | Yes |
| Older branches or forks | No |

Only the `main` branch is actively maintained. Experimental or older forks may not receive updates.

---

## Reporting Security Issues

If you discover a vulnerability in this repository, please report it responsibly.

### How to Report

- Do not open a public GitHub issue for security reports.
- File a private security advisory if available, or contact the maintainer privately through GitHub.

### What to Include

Please include:
- A clear description of the issue
- Steps to reproduce, if applicable
- Potential risks, such as data handling or unsafe notebook execution
- Suggested fix or mitigation, if available

### Response Timeline

- Acknowledgement within 3-5 business days
- Assessment and fix, where applicable, as soon as practical based on severity

---

## Data and Model Safety

This repository uses the MIT-BIH Arrhythmia Dataset for educational classification tasks. Users should note:

- The dataset contains physiological data and should be handled with appropriate care
- Models from this repository are not intended for clinical decision-making
- Real patient data, credentials, API keys, and private environment files must not be committed
- Any accidental exposure of sensitive data should be reported and removed promptly

---

## Responsible Use

By using this repository, you agree not to:
- Deploy models for real-world medical diagnosis
- Use notebooks or scripts with sensitive data without proper consent
- Run untrusted notebooks, scripts, models, or data files without review

---

## Contribution Guidelines

Contributions are welcome. Please follow good practices:
- Keep code, notebooks, and data handling clear and reproducible
- Do not commit sensitive credentials or private datasets
- Document significant experiments, configurations, and results clearly
