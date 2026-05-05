# Assignment 2 — Federated Learning for Healthcare Analytics

**Course:** ITAI 4376 — AI Applications  
**Student:** Muhammad Umer  
**Semester:** Spring 2026

## Problem Statement

This assignment focused on designing and prototyping a privacy-preserving machine learning system for healthcare analytics. The core challenge was enabling model training across distributed hospital datasets without centralizing sensitive patient records.

## Approach and Methods

The project used a federated learning architecture implemented with TensorFlow Federated, where each participating node trains a local model on its own data and only shares model updates rather than raw records. A Flask-based backend coordinated the aggregation process, and a React frontend provided a dashboard for monitoring model performance across nodes. Synthetic EHR data generated through the Synthea platform was used to simulate realistic patient records for training and evaluation.

## Results and What They Mean

The prototype demonstrated that federated learning can produce models with competitive accuracy while keeping patient data local and protected. This approach directly addresses a critical gap in healthcare AI adoption, where data siloing between institutions has historically prevented collaborative model development. The results suggest that privacy-preserving architectures are not just ethically preferable but technically viable at meaningful scale.
