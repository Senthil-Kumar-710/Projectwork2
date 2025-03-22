## Fault Detection In 3D Printing Using CNN
Creating a **Convolutional Neural Network (CNN)** involves training the network with labeled image data, where the model learns to extract spatial features through convolutional layers and classify the images based on learned patterns. The CNN iteratively adjusts its weights during training to minimize prediction errors and improve accuracy in detecting defects.

## About
This project focuses on developing a **CNN-based defect detection system for 3D printing**. The primary goal is to create a tool capable of identifying defects in 3D printed objects by analyzing images of the printed parts. As 3D printing becomes more prevalent in manufacturing, defect detection is crucial to ensure product quality, reduce material wastage, and maintain structural integrity.

The project involves training a CNN model to recognize defects such as cracks, surface irregularities, layer shifts, or incomplete prints. The system’s workflow includes preprocessing input images, feeding them into the CNN model, and outputting a prediction indicating the presence or absence of defects along with confidence scores.

The final result is a **web-based application** where users can upload images of 3D printed objects for defect detection. This tool aims to assist manufacturers, engineers, and researchers in automating quality control and improving the reliability of 3D printed components.

## Features
Defect Detection Capabilities:
The CNN-based system can accurately detect various types of defects in 3D printed objects, such as cracks, surface inconsistencies, and layer shifts.

Automated Quality Inspection:
The system automates the inspection process, reducing the need for manual checking and ensuring faster and more reliable defect detection.

High Accuracy with Deep Learning:
By leveraging CNNs, the model learns intricate features and patterns from the images, resulting in high detection accuracy even for subtle defects.

Real-Time Prediction:
The system is designed to provide real-time defect predictions, enabling quick decision-making during or after the printing process.

Scalability and Modularity:
The defect detection system is scalable to handle large datasets and can be easily updated with new defect types or model improvements as required.

## Requirements
Hardware Resources:
Defect detection using CNNs requires powerful hardware resources such as GPUs or TPUs to handle large image datasets and perform intensive computations efficiently.

Software Frameworks:
Utilize deep learning frameworks like TensorFlow, PyTorch, or Keras for building, training, and testing the CNN-based defect detection model.

Dataset Preparation:
Collect and preprocess a diverse and high-quality dataset of 3D printed objects, including both defect-free and defective samples, to train the model effectively.

CNN Architecture Selection:
Select an appropriate CNN architecture (e.g., ResNet, VGG, MobileNet) based on accuracy requirements and computational constraints for optimal performance.

Loss Function Design:
Define suitable loss functions (e.g., cross-entropy loss) to guide the model’s learning process, ensuring accurate defect classification.

Hyperparameter Tuning:
Adjust hyperparameters such as learning rate, batch size, number of epochs, and regularization techniques to achieve optimal model performance and generalization.

Training Strategy:
Adopt effective training strategies like data augmentation, early stopping, and learning rate scheduling to prevent overfitting and improve the model’s stability and accuracy.

## System Architecture
![Architecture Diagram](https://github.com/user-attachments/assets/e2d7cd43-6302-4ea0-a7da-8622caa99169)

## Output

#### Output1 - Defect

![out1](https://github.com/user-attachments/assets/0928eb48-6693-48a1-950c-9aaee9fc2e53)

Confidence: 70.21%

#### Output2 - No Defect
![out2](https://github.com/user-attachments/assets/e7721add-c41c-4eb5-adbd-844acb9c5905)

Confidence: 97.73%

#### Output3 - Model Accuracy

![Graph](https://github.com/user-attachments/assets/ab35bb72-7dc4-492a-be6d-91395a409cab)


#### Output4 - Score

![Score](https://github.com/user-attachments/assets/75255a69-0775-444b-b1f7-9612667ef8c2)


## Results and Impact
Accurate Defect Detection:
The CNN-based defect detection system effectively identifies defects in 3D printed objects, enhancing quality control and reducing production errors.

Improved Manufacturing Efficiency:
By automating defect detection, the system minimizes manual inspection efforts, streamlining the 3D printing workflow and improving overall manufacturing efficiency.

Enhanced Product Quality:
The model ensures early detection of defects, leading to improved product quality, reduced material waste, and cost savings in the production process.

Real-Time Monitoring:
The system can be integrated into real-time monitoring setups, allowing continuous observation and immediate detection of defects during 3D printing.

Scalability and Adaptability:
The deep learning-based approach is scalable and adaptable to various types of 3D printers and materials, making it applicable across diverse industrial sectors.

Contribution to AI and Manufacturing:
This project demonstrates the potential of AI and deep learning in revolutionizing defect detection in additive manufacturing, contributing to smarter and more reliable production systems.

## Articles published / References
1. LeCun, Y., Bottou, L., Bengio, Y., & Haffner, P. (1998). Gradient-based learning applied to document recognition. Proceedings of the IEEE.
2. Krizhevsky, A., Sutskever, I., & Hinton, G. E. (2012). ImageNet Classification with Deep Convolutional Neural Networks. Advances in Neural Information Processing Systems (NeurIPS).






