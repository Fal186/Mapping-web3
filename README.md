# Mapping-web3: A Three-Stage Framework for Analyzing Web3 Discourse

This repository contains the dataset, model training scripts, and reproducibility materials for the paper titled:

**"Extracting Strategic Insights from Web3 Discourse: A Transformer-Based Framework for Domain, Emotion, and Intent Classification"**

---

## 📂 Repository Structure

```
Mapping-web3/
│
├── dataset/
│   ├── web3_Stage1_industry_domain.csv
│   ├── web3_Stage2_emotional_tone.csv
│   └── web3_Stage3_communicative_intent.csv
│
├── codes/
│   ├── BERT/
│   │   ├── Stage 1/
│   │   ├── Stage 2/
│   │   └── Stage 3/
│   └── RoBERTa/
│       ├── Stage 1/
│       ├── Stage 2/
│       └── Stage 3/
```

---

## 📘 Project Overview

This project introduces a three-stage classification framework to analyze how Web3 is:

- **Discussed** (Stage 1: Industry Domain Classification)  
- **Felt** (Stage 2: Emotional Tone Classification)  
- **Communicated** (Stage 3: Communicative Intent Classification)  

Two transformer-based models (BERT and RoBERTa) were fine-tuned and evaluated across these tasks.

---

## 📁 Dataset

Labeled datasets are available in the `/dataset` folder, with one CSV file per classification stage:

- `web3_Stage1_industry_domain.csv`  
- `web3_Stage2_emotional_tone.csv`  
- `web3_Stage3_communicative_intent.csv`  

Each file contains anonymized, preprocessed social media data from X (formerly Twitter), Reddit, and YouTube.

---

## 🧠 Model Training Scripts

The `/codes` folder contains all scripts for fine-tuning both BERT and RoBERTa across three stages.  
Each model has a dedicated subdirectory, organized by classification stage.

- Use the files in `codes/BERT` or `codes/RoBERTa` for training or evaluation  
- Fine-tuning configurations (batch size, learning rate, epochs) follow the best-performing setups from the paper  

---

## 🔁 Reproducibility

- Data splits were stratified with a fixed random seed (43)  
- The models were trained using the Hugging Face Transformers library  
- For reproducibility, set environment seeds across Python, NumPy, and PyTorch as shown in the code  

---

## 📜 Citation

If you use this resource, please cite:

> Falaah. *Extracting Strategic Insights from Web3 Discourse: A Transformer-Based Framework for Domain, Emotion, and Intent Classification*. (2025) [Paper link pending]

---

## 🔗 Links

- 📄 [Paper (Coming Soon)](https://)  
- 📁 [GitHub Repository](https://github.com/Fal186/Mapping-web3)
