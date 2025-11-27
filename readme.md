# Federated Learning Breast Cancer with PySyft

This project is a test playground for the PySyft package, an open‑source framework that lets data scientists and researchers do their work while keeping data private.

PySyft sits in the middle between an organisation and a researcher:

- The **organisation** loads the metadata and real data into the server (Datasite), creates an account for the external researcher, sets up some mock data (a synthetic version of the real dataset)… and then goes to drink their coffee.

- On the other hand, the **researcher** logs into their account, runs code on the mock data created by the organisation, and downloads the results and logs.

- Next step: the **organisation** reviews the audit code, executes it on the real data, and submits the results back to the researcher.

For this specific project, I used the well‑known Breast Cancer dataset from scikit‑learn and ran it through this “magical” PySyft cycle.

---

## Contents

- `datascientist.ipynb` — training, experiments and playing with the model.
- `organisation.ipynb` — project notes and the organisation-side process.


