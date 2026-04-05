# Pharmaceutical_interaction_engine
# 💊 Pharmaceutical Interaction Engine

## 🚀 Overview
The Pharmaceutical Interaction Engine is an intelligent system designed to detect dangerous drug interactions hidden within encrypted prescriptions. 

It solves a critical healthcare challenge by:
- Decrypting drug names using an age-based Caesar Cipher
- Identifying harmful drug combinations
- Visualizing interactions using a network graph
- Flagging high-risk patients automatically

---

## 🎯 Problem Statement
Prescriptions are encrypted using an age-relative Caesar Cipher, making drug identification difficult. 

The system must:
- Decrypt drug names in real-time
- Analyze interactions between drugs
- Identify severity levels (LOW, MEDIUM, HIGH)
- Prevent life-threatening combinations

---

## 🧠 Key Features

### 🔐 1. Cipher Decryption Engine
- Uses Caesar Cipher logic
- Shift value = Patient age
- Converts encrypted drug names → readable format

---

### ⚠ 2. Drug Interaction Detection
- Compares drug pairs
- Detects severity levels:
  - LOW
  - MEDIUM
  - HIGH

---

### 🕸 3. Medication Conflict Graph
- Built using NetworkX
- Nodes → Drugs
- Edges → Interactions
- Color-coded severity:
  - 🔴 Red → HIGH
  - 🟠 Orange → MEDIUM
  - 🟢 Green → LOW

---

### 📊 4. Drug Interaction Viewer
- Tabular format using Pandas
- Easy to interpret interaction details

---

### 🧪 5. Prescription Validation API
- Simulated API logic
- Returns:
  - Decrypted drugs
  - Interactions
  - Risk level (SAFE / CAUTION / DANGEROUS)

---

### 👥 6. High-Risk Patients Detection
- Automatically identifies patients with dangerous drug combinations

---

## 🛠 Tech Stack
- Python
- Streamlit (UI Dashboard)
- NetworkX (Graph Visualization)
- Matplotlib
- Pandas

---

## ▶️ How to Run

### 🔹 Option 1: Google Colab
1. Open Google Colab
2. Copy the notebook code
3. Run all cells

---
