# Machine Learning Based Network Traffic Forensics for Cyber Crime Investigation

<p align="center">
  <img src="https://img.shields.io/badge/BTech-CSE%20AI%20%26%20ML-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/CyberSecurity-NetworkForensics-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/MachineLearning-ScikitLearn-orange?style=for-the-badge&logo=scikitlearn" />
  <img src="https://img.shields.io/badge/Research-Published-success?style=for-the-badge" />
</p>

---

# Published Research Paper

Research Paper Link:  
https://rsisinternational.org/journals/ijrias/view/machine-learning-based-network-traffic-forensics-for-cyber-crime-investigation

DOI:  
https://doi.org/10.51584/IJRIAS.2026.110400063

---

# Overview

This research focuses on applying Machine Learning techniques for Network Traffic Forensics and Cyber Crime Investigation using the UNSW-NB15 dataset.

The project investigates how supervised Machine Learning models can analyze network traffic, classify malicious activities, and support digital forensic investigations in modern cybersecurity environments.

The research mainly focuses on:

- Network Traffic Analysis
- Cyber Crime Investigation
- Intrusion Detection
- Digital Forensics
- Machine Learning Based Threat Detection
- Forensic Reliability & Interpretability

This project was developed as our B.Tech Final Semester Research Project 2022-2026 for Computer Science & Engineering (AI & ML) under the guidance of Dr. Avinash Kumar.

---

# My Contribution

I am the co-author and corresponding author of this published research paper. I contributed extensively to both the technical implementation and research development of this project.

### Responsibilities

- Research Methodology Design
- Literature Review
- Comparative Research Analysis
- Dataset Preprocessing
- Feature Selection
- Coding & Machine Learning Model Development
- Experimental Setup
- Performance Evaluation
- Result Visualization
- Documentation & Research Paper Writing

---

# Research Objective

The main objective of this research is to:

- Detect malicious network traffic using Machine Learning
- Improve cyber forensic investigation workflows
- Analyze intrusion detection performance
- Compare supervised Machine Learning algorithms
- Study interpretability and forensic reliability in cybersecurity systems

---

# Dataset Used

## UNSW-NB15 Dataset

The project uses the publicly available UNSW-NB15 benchmark dataset widely used in cybersecurity and intrusion detection research.

### Attack Categories Included

- DoS
- Exploits
- Fuzzers
- Reconnaissance
- Worms
- Shellcode
- Generic Attacks

The dataset contains both:

- Normal Network Traffic
- Malicious Traffic Records

---

# Workflow

## Data Loading

- Loaded UNSW-NB15 training dataset
- Loaded UNSW-NB15 testing dataset
- Combined preprocessing workflow for consistency

---

## Feature Selection & Preprocessing

Selected important network traffic features:

| Feature | Description |
|----------|-------------|
| dur | Connection Duration |
| proto | Protocol Type |
| spkts | Source Packets |
| dpkts | Destination Packets |
| sbytes | Source Bytes |
| dbytes | Destination Bytes |

### Preprocessing Steps

- Label Encoding
- Feature Scaling using StandardScaler
- Feature Matrix Generation
- Data Preparation for ML Models

---

# Machine Learning Models Implemented

The following supervised Machine Learning models were implemented and evaluated:

| Model |
|--------|
| Decision Tree (DT) |
| Random Forest (RF) |
| Linear SVM |

---

# Experimental Setup

| Parameter | Value |
|------------|-------|
| Programming Language | Python |
| ML Library | Scikit-learn |
| Data Handling | Pandas & NumPy |
| Scaling Method | StandardScaler |
| Encoding Method | Label Encoding |
| RF Estimators | 100 |
| Random State | 42 |
| SVM Variant | LinearSVC |

---

# Evaluation Metrics

The models were evaluated using:

| Metric | Purpose |
|---------|----------|
| Accuracy | Overall Classification Performance |
| Precision | Reliability of Threat Detection |
| Recall | Ability to Detect Actual Attacks |
| F1-Score | Balanced Model Performance |

---

# Experimental Results

| Model | Accuracy | Precision | Recall | F1-Score |
|--------|-----------|------------|---------|-----------|
| Decision Tree | 90.24% | 96.82% | 88.56% | 92.51% |
| Random Forest | 90.83% | 97.36% | 88.94% | 92.96% |
| Linear SVM | 76.83% | 77.32% | 93.33% | 84.57% |

---

# Best Performing Model

## Random Forest (RF)

### Performance

| Metric | Score |
|---------|-------|
| Accuracy | 90.83% |
| Precision | 97.36% |
| F1-Score | 92.96% |

### Why Random Forest Performed Best?

The Random Forest model demonstrated:

- Better generalization capability
- Strong resistance to overfitting
- Better handling of noisy network data
- Balanced classification performance
- Reliable forensic interpretation

This makes it highly suitable for:

- Intrusion Detection Systems
- Cyber Threat Detection
- Network Traffic Forensics
- Digital Investigation Systems

---

# Key Findings

## Decision Tree

- Highly interpretable
- Easy to visualize decision-making
- Useful for forensic traceability

## Random Forest

- Most balanced overall performance
- Better robustness across attack classes
- Superior ensemble learning capability

## Linear SVM

- High recall rate
- Detects malicious traffic effectively
- Generates comparatively more false positives

---

# Visualizations Included

The project includes:

- Overall System Architecture
- Feature Selection & Preprocessing Flow
- ML Pipeline Architecture
- Performance Comparison Charts
- Evaluation Metrics Visualization

---

# Technologies Used

| Technology | Purpose |
|-------------|----------|
| Python | Programming |
| Pandas | Data Processing |
| NumPy | Numerical Computing |
| Scikit-learn | Machine Learning |
| Matplotlib | Visualization |
| Jupyter Notebook / Colab | Development Environment |

---


```bash
git clone https://github.com/your-username/network-traffic-forensics-ml.git
