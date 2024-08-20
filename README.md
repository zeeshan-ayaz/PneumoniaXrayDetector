
# **Comprehensive Analysis of CNN, VGG16, VGG19, DenseNet121, and DenseNet169 for Pneumonia Detection from Chest X-ray Images**

## **Project Overview**

This project aims to detect pneumonia from chest X-ray images using a range of Convolutional Neural Network (CNN) architectures. Specifically, it explores the performance of five different models: a custom CNN, VGG16, VGG19, DenseNet121, and DenseNet169. The goal is to determine which model is most effective in identifying pneumonia, ultimately aiding in quicker and more accurate diagnosis in a clinical setting.

## **Dataset**

The dataset used in this project consists of chest X-ray images categorized into two classes:
- **NORMAL**: X-ray images without signs of pneumonia.
- **PNEUMONIA**: X-ray images showing signs of pneumonia.

The dataset is publicly available and widely used for pneumonia detection research.

## **Models Used**

### **1. Custom CNN**
- A basic CNN model built from scratch, including multiple convolutional and pooling layers followed by fully connected layers.
- Serves as a baseline model for comparison.

### **2. VGG16**
- A pre-trained CNN architecture with 16 layers known for its effectiveness in image classification.
- Fine-tuned on the chest X-ray dataset to adapt it to the pneumonia detection task.

### **3. VGG19**
- An extension of VGG16 with 19 layers, offering additional depth and capacity for feature extraction.
- Fine-tuned similarly to VGG16 for pneumonia detection.

### **4. DenseNet121**
- A pre-trained CNN with 121 layers, characterized by its dense connections that improve learning efficiency.
- Fine-tuned on the dataset to leverage its deep architecture.

### **5. DenseNet169**
- A deeper version of DenseNet with 169 layers, providing more complex feature extraction capabilities.
- Fine-tuned to enhance its performance in pneumonia detection.

## **Objective**

The main objectives of this project are:
- To compare the performance of the custom CNN, VGG16, VGG19, DenseNet121, and DenseNet169 models in detecting pneumonia.
- To evaluate the models based on metrics such as accuracy, precision, recall, and overall effectiveness.
- To identify the most suitable model for practical deployment in medical diagnostics.

## **Results**

The results section should summarize the performance of each model, highlighting the best-performing architecture based on the evaluation metrics.

## **How to Use**

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/zeeeshan-ayaz/pneumonia-detection.git
   ```
2. **Install Required Dependencies:**
   Make sure you have Python installed, then install the required packages using:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Notebook:**
   Open the Jupyter notebook and execute the cells to train and evaluate the models:
   ```bash
   jupyter notebook pneumonia_detection.ipynb
   ```
4. **Model Inference:**
   Use the trained models to predict pneumonia on new chest X-ray images.

## **Conclusion**

This project demonstrates the effectiveness of different CNN architectures in detecting pneumonia from chest X-rays. The insights gained can contribute to the development of automated systems for early and accurate diagnosis of pneumonia.

## **Contributing**

Contributions are welcome! If you have ideas or improvements, feel free to submit a pull request.

## **License**

This project is licensed under the MIT License. See the `LICENSE` file for details.

## **Contact**

If you have any questions or feedback, feel free to contact me through my [GitHub profile](https://github.com/zeeeshan-ayaz).
