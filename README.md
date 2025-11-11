# AVE-Hybrid-Anomaly-Detection
Official implementation of
# A New Hybrid Model for Improving Outlier Detection Using Combined Autoencoder and Variational Autoencoder (AVE)

**Authors:**  
Ahmed M. Daoud¹, Osama M. Elkomy¹, Walid I. Khedr¹, and Khalid M. Hosny¹*  
¹ Department of Information Technology, Faculty of Computers and Informatics, Zagazig University, Zagazig, Egypt  
📧 AMDaoud@fci.zu.edu.eg, omelkomy@fci.zu.edu.eg, wkhedr@fci.zu.edu.eg, *k_hosny@zu.edu.eg*

---

## Overview
This repository contains the source code, scripts, and supplementary materials for the paper:

> **"A New Hybrid Model for Improving Outlier Detection Using Combined Autoencoder and Variational Autoencoder"**

The proposed **AVE** architecture integrates the strengths of Autoencoder (AE) and Variational Autoencoder (VAE) to enhance outlier detection in high-dimensional datasets.  
AVE combines AE’s reconstruction capability with VAE’s regularized latent space to improve detection stability and robustness.

---

## 📊 Abstract
In this study, we propose a hybrid model, **AVE**, that fuses AE and VAE to achieve superior anomaly detection performance. The AVE model consistently outperformed the baseline AE, VAE, and several classical and deep anomaly detection models across **16 benchmark datasets**.

**Highlights:**
- Average **Precision:** 0.6925  
- Average **ROC-AUC:** 0.8902  
- Outperforms the second-best model by **+25.99% (Precision)** and **+5.47% (ROC-AUC)**  
- Achieves **best accuracy on 12/16 datasets** and **highest ROC-AUC on 5 datasets**

---

## ⚙️ Installation
To reproduce the results, install dependencies using pip:

```bash
pip install -r requirements.txt
