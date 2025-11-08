# ViT Fine-Tuning on CIFAR-10

This project demonstrates how to fine-tune the **Vision Transformer (ViT)** model for **image classification** using the **CIFAR-10 dataset**.  
It includes two variants — full and partial fine-tuning — to compare model performance, efficiency, and accuracy.

---

## Project Overview
This repository explores **transfer learning with Vision Transformers (ViT)**, a powerful model architecture pretrained on **ImageNet-21k**.  
Using the **Hugging Face Transformers** library, the project fine-tunes ViT on CIFAR-10 and compares:

- **Full Fine-Tuning:** All model layers are updated.
- **Partial Fine-Tuning:** Most layers are frozen, and only the last few encoder layers and classifier are trained.

---

## Project Variants

| Folder | Description |
|---------|--------------|
| **`full_finetuning/`** | Fine-tunes **all ViT layers** on CIFAR-10 for maximum adaptation and accuracy. |
| **`partial_finetuning/`** | **Freezes early layers** and fine-tunes only the **last encoder blocks and classifier head**, improving training speed and generalization. |

Both versions use the same preprocessing pipeline and training configuration.

---

## Hello and Welcome

Thank you for visiting my GitHub page!  
I’m currently in the process of uploading my previous projects and doing my best to make them publicly available in an organized and clear manner.  

At the moment, I’m adding each project with some **light updates and clarifying adjustments**, and I plan to include more **comprehensive notes, explanations, and detailed READMEs** very soon — to help others better understand each project’s idea and usage.  

If you have any questions, suggestions, or would simply like to connect, I’d be delighted to hear from you:  
- [LinkedIn](https://www.linkedin.com/in/wajdalrabiah)  
- [X (Twitter)](https://x.com/wajdalrabiah)  

Thank you again for your time and interest.  
Your feedback and interaction are always appreciated

> _More updates coming soon — stay tuned!_  
