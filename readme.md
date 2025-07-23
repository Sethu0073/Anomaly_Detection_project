# 🔍 Anomaly Detection on MVTec Dataset

This project implements an anomaly detection system using deep learning, specifically designed to work with the **MVTec Anomaly Detection (MVTec AD)** dataset. The goal is to identify defects or anomalies in various industrial objects, which is crucial in quality inspection processes.

---

## 📋 Table of Contents

- [🌟 About the Project](#-about-the-project)
- [💾 Dataset](#-dataset)
- [🚀 Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [▶️ Usage](#️-usage)
- [📂 Project Structure](#-project-structure)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

## 🌟 About the Project

This repository contains code to **train and evaluate an anomaly detection model** using the MVTec AD dataset. The model is trained exclusively on *normal* (anomaly-free) images and is tested against both normal and anomalous samples. This mimics real-world industrial applications where anomalies are rare and diverse.

---

## 💾 Dataset

The [MVTec AD dataset](https://www.mvtec.com/company/research/datasets/mvtec-ad) includes over 5000 high-resolution images across **object** and **texture** categories.  

- **Training Set**: Contains only *good* (anomaly-free) samples.
- **Test Set**: Contains both *good* and *defective* samples.

**Note:** Download and organize the dataset manually as follows:
