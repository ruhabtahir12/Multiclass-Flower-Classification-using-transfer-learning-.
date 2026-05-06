# Multiclass-Flower-Classification-using-transfer-learning-.
This project is a Deep Learning-based Image Classification system that identifies different categories of flowers using a pretrained Convolutional Neural Network (CNN) with Transfer Learning.

To improve model performance and generalization, Data Augmentation techniques are applied to increase dataset diversity and reduce overfitting.
Model Architecture
Pretrained Base Model (frozen layers)
Custom Classification Head:
Global Average Pooling / Flatten
Dense Layers
Dropout (for regularization)
Output Layer (Softmax for multi-class classification)
📂 Dataset
Dataset: Flower Classification Dataset
Contains multiple flower categories (e.g., daisy, rose, sunflower, tulip, dandelion)
Images are preprocessed using:
Resizing
Normalization
Augmentation
⚙️ Technologies Used
Python 🐍
TensorFlow / Keras
NumPy
Matplotlib
🏗️ Project Workflow
Data Loading & Preprocessing
Data Augmentation
Load Pretrained Model
Freeze Base Layers
Add Custom Layers
Model Training
Evaluation & Validation
Works well on unseen images
