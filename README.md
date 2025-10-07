Adversarial Examples in Neural Networks – Paper Replication & Implementation

This repository contains the implementation of the research paper **"Explaining and Harnessing Adversarial Examples"** by Goodfellow et al. ([arXiv:1412.6572](https://arxiv.org/pdf/1412.6572)). The paper investigates the vulnerability of deep neural networks to adversarial inputs and attributes it to the linear nature of these models in high-dimensional spaces. It introduces the **Fast Gradient Sign Method (FGSM)** for generating adversarial examples and explores **adversarial training** as a defense mechanism.

### Contents

*  **Paper Summary** – Brief overview and key insights from the base paper
*  **FGSM Implementation** – Code to generate adversarial examples using FGSM
*  **Model Training & Evaluation** – Experiments with clean vs adversarial inputs
*  **Result Analysis** – Comparison with original paper results and discussion of deviations



### Description of the paper:

*Explaining and Harnessing Adversarial Examples* 
(Goodfellow et al., 2015) argues that neural networks’ vulnerability to adversarial examples stems largely from their approximate linear behavior in high dimensions.  The paper introduces the **Fast Gradient Sign Method** to efficiently generate adversarial perturbations and shows that adversarial training can improve robustness and act as a form of regularization. 
