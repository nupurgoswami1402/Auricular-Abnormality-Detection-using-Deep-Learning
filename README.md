# Auricular Abnormality Detection

This repository contains the experimental implementations for classifying auricular abnormalities using state-of-the-art Vision Transformers (ViT). Ear image classification plays a crucial role in diagnosing congenital and acquired auricular defects. 

The project evaluates different transformer-based architectures for medical image analysis to determine the most effective approach for detecting abnormalities.

## 🧠 Architecture & Workflow

Here is a high-level view of the data preprocessing, model selection, and evaluation workflow used in this project:
<img width="1024" height="1024" alt="auricular_architecture_1784092516200" src="https://github.com/user-attachments/assets/88fe526a-3331-4712-a5fc-059e68dd2e58" />


## 📁 Repository Structure

The experiments are divided into three individual Jupyter notebooks, each implementing a distinct Vision Transformer architecture:

- `deit-transformer.ipynb`: Implementation using **Data-efficient Image Transformers (DeiT)**.
- `swin-transformer.ipynb`: Implementation using **Swin Transformers (Shifted Window)** for hierarchical feature extraction.
- `vit-transformer.ipynb`: Implementation using the standard **Vision Transformer (ViT)**.

## 🚀 Getting Started

1. Clone this repository.
2. Ensure you have the necessary deep learning libraries installed (`torch`, `torchvision`, `transformers`, etc.).
3. Open any of the Jupyter Notebooks (`.ipynb`) in your local Jupyter Server, Google Colab, or VS Code.
4. Run the cells to preprocess the data, train the respective model, and evaluate the results.

## 📊 Models Used

- **ViT (Vision Transformer):** Applies standard transformer architecture to image patches.
- **Swin Transformer:** Introduces a hierarchical architecture with shifted windows, reducing computational complexity while retaining global context.
- **DeiT (Data-efficient Image Transformers):** Employs a distillation token for better data efficiency, enabling high performance even without massive datasets.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
