# ML-Project|Breast Cancer Subtyping Using CNN-based Interpretable Deep Learning Model (EffectiveNETV2B2)


# Project Overview: 
The project aim to develop an interpretable Deep Learning Model based on Convolutional neural networks, CNNs, to easily subtype breast cancer from the histopathological images integrated with an AI tool that interprets the model prediction. The model will subtype the breast cancer into one of the following types: Phyllodes tumor, fibroadenoma, adenosis, fibroadenoma, tubular adenoma, lobular carcinoma, carcinoma, papillary carcinoma, and mucinous carcinoma.

# Installation Instructions:
- Clone this repository.
- Install the required dependencies using the following command: pip install -r requirements.txt


# Usage:
# Dataset Preparation:
Ensure you have the BreakHis dataset or specify your dataset path. Modify the `dataset_directory` variable in `breast_histopathology.py` to point to your dataset location.

# Training the Classification Model:
Run `breast_histopathology.py` to load, preprocess, and train the classification model. View the console for training progress and evaluation metrics.

# Visualizing GradCAM Results:
Update the `dataset_path` variable in `gradcam_visualization.py` with your dataset path. Execute `gradcam_visualization.py` to generate GradCAM visualizations for model predictions on test images.

# Additional Information:
- This project utilizes TensorFlow, PyTorch, and OpenCV libraries for deep learning tasks.
- For detailed instructions and examples, refer to the documentation provided in this repository.



  
