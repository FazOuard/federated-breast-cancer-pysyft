# Federated Breast Cancer (PySyft)

Demonstration of a simple federated learning workflow using PySyft and the scikit-learn breast cancer dataset. This repository contains notebooks and notes used to explore privacy-preserving model training and audit workflows between an organisation and external researchers.

## Contents
- `datascientist.ipynb` — exploratory notebook with training/experiments.
- `organisation.ipynb` — project notes and process documentation.

## Goals
- Show a minimal example of a federated workflow using PySyft.
- Provide reproducible notebooks for experimenting with the `breast_cancer` dataset from `scikit-learn`.

## Prerequisites
- Python 3.10+ recommended
- Git (optional)

## Quick start (PowerShell)

1. Create and activate a virtual environment:

```powershell
python -m venv venv
& .\venv\Scripts\Activate.ps1
```

2. Install dependencies:

```powershell
pip install -r requirements.txt
```

3. Start Jupyter Notebook and open `datascientist.ipynb`:

```powershell
jupyter notebook
```

## Notes
- The project uses the `breast_cancer` dataset provided by `scikit-learn`. No external patient data is included.
- `requirements.txt` currently lists the main dependencies; for reproducibility consider pinning versions or running `pip freeze > requirements.txt` in your project venv.
- The repository `.gitignore` excludes `venv/`, `.ipynb_checkpoints/`, large data files, and model checkpoints — do not commit large datasets or model artifacts.

## Contributing
- Feel free to open issues or pull requests. Add clear reproduction steps and tested code when proposing changes.

## License
- Add a license file (e.g., `LICENSE`) if you intend to make this project public.

---

If you want, I can:
- Pin dependency versions in `requirements.txt`.
- Run `pip freeze` in your active venv and update `requirements.txt` for you.
- Commit and push these changes to GitHub.
# Federated Learning Breast Cancer with Pysyft
This project is a testing for the Pysyft package which is an Open Source framework that let Data Scents\researches do their work while maintaining privacy!
Pysyft comes as a middle between an organisation and a researcher.
The organisation load the metadata into the server:Datasite, it creates an account for external researcher and then goes to drink their coffee.

In the other hand, the researcher log into their account, get answers and allow questions: a code for example in the mock data created by the organisation which is a synthetic artificial version of the dataset and then download the answers.

Next step is the organisation which review the audit code, execute it and submits results.

So for this specific project I used a well known dataset Breast Cancer from sklearn and then made the magical cycle.
