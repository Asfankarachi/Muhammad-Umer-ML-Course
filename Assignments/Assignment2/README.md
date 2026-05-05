# Assignment 2 — Federated Learning for Healthcare Analytics

**Course:** ITAI 4376 — AI Applications
**Instructor:** Professor Patricia McManus
**Student:** Muhammad Umer | Team: Neural Spark
**Institution:** Houston City College | Spring 2026

## Problem Statement

Healthcare institutions hold valuable patient data that could train powerful predictive models, but sharing that data raises serious privacy concerns. This assignment addressed how machine learning models can be trained on distributed healthcare data without centralizing sensitive patient information.

## Approach and Methods

The Neural Spark team designed a privacy-preserving federated learning prototype. Rather than aggregating raw patient data centrally, the system trained local models at each simulated client node and shared only model weights with a central aggregation server.

The system used TensorFlow Federated for distributed learning, Flask for the backend API, and a React frontend for monitoring. Synthetic EHR data from Synthea served as the training dataset.

## Results and Interpretation

The prototype demonstrated that federated learning can achieve competitive model performance compared to centralized training while maintaining strict data locality. The federated approach introduced only a modest accuracy trade-off while providing substantially stronger privacy guarantees.

## Key Takeaway

Federated learning is a practical solution to one of the biggest barriers in healthcare AI — the tension between data utility and patient privacy.

## Technologies Used

TensorFlow Federated, Flask, React, Synthea, GitHub
