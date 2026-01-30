# Diabetic Retinopathy Detection
Automated Diabetic Retinopathy Detection Using Deep Learning and Image Analysis

This project focuses on the detection of Diabetic Retinopathy (DR) from retinal images using a deep learning approach. Diabetic Retinopathy is a complication of diabetes that affects the eyes, and early detection is crucial for preventing vision loss. This repository presents a solution for binary classification, distinguishing between 'Diseased' and 'Healthy' retinal images.

<img width="1295" height="754" alt="image" src="https://github.com/user-attachments/assets/887eadc1-3ca6-4ee3-86b7-5204b77603d3" />

The project employs a fine-tuned ResNet50 model as the base for feature extraction. The base model's weights are initialized with 'imagenet' and its top layers are removed (include_top=False). A custom classification head is added on top of the ResNet50 base.

<img width="1290" height="573" alt="image" src="https://github.com/user-attachments/assets/4dcdbb6e-6923-401d-9437-1918aaeffd1a" />

The final accuracy of the model is recorded as 94.2%.

<img width="1101" height="590" alt="image" src="https://github.com/user-attachments/assets/ec0b3739-ad08-4b7e-8b56-9c118e3c4643" />
