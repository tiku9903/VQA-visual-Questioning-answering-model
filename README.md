Visual Question Answering Models
Overview
This project implements two separate Visual Question Answering (VQA) models: one utilizing the BLIP-CLIP architecture and the other leveraging BERT with Vision Transformer (ViT). The objective of this project is to compare the performance of these two models in answering questions based on image content, providing insights into their strengths and weaknesses.

Models
1. BLIP-CLIP Model
Architecture: Combines vision and language processing using the BLIP-CLIP framework.
Image Processing: Uses pretrained BLIP and CLIP components for effective feature extraction and understanding.
Training: Trained on a relevant dataset to respond accurately to visual questions.
2. BERT-ViT Model
Architecture: Integrates BERT for textual understanding and Vision Transformer (ViT) for image processing.
Image Processing: Employs ViT to extract visual features and BERT to process and analyze the questions.
Training: Developed and trained from scratch with a focus on optimizing performance in VQA tasks.
Comparative Analysis
Metrics: Evaluated the performance of both models based on accuracy, F1 score, precision, recall, and response time.
Results: Analyzed the strengths and weaknesses of each model, providing insights into their effectiveness in various scenarios.
Technologies Used
Python: The primary programming language for implementation.
Deep Learning Frameworks:
PyTorch for model building and training.
Transformers library for BERT and ViT integration.
BLIP-CLIP for combined vision and language processing.
Libraries:
NumPy and Pandas for data manipulation.
Matplotlib and Seaborn for data visualization.
OpenCV for image processing.
