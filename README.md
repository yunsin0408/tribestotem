# Tawu and Taiya Totem Identifier

**Disclaimer**: We are aware that the use of indigenous totems in this project may involve cultural and intellectual property rights, including copyright and traditional knowledge protections. Some totems may be subject to copyright laws, while others may represent cultural heritage that is collectively owned by indigenous communities. Throughout the development of this project, we have made efforts to respect these rights and recommend seeking proper authorization and engaging with relevant indigenous groups or cultural organizations to ensure lawful and respectful use of these symbols. This project aims to promote cultural awareness and preservation while honoring the rights of indigenous peoples.

## Introduction
This project uses AI to recognize and classify totems from the Tawu (達悟族) and Taiya (泰雅族) indigenous tribes of Taiwan. The goal of this project is to help preserve and promote Taiwanese indigenous cultures by developing a machine learning model capable of identifying these totems.

## Features

- **Totem Classification**: The AI model is trained to classify images as belonging to the Tawu or Taiya tribes.
- **High Accuracy**: The model achieves an accuracy rate of 90% in identifying totems from the two tribes.
- **Image Recognition**: It processes images of totems found in various contexts, including artwork on walls, clothing, and other surfaces.

To develop the model, we employed a custom Convolutional Neural Network (CNN) alongside a pre-trained ResNet50V2 model for transfer learning. The dataset included 93 images (63 from Tawu and 30 from Taiya), collected from books and Google. While the limited dataset presented challenges in capturing the full diversity of totem designs, we employed data augmentation techniques to expand the dataset and improve model robustness. We also used Gradio to deploy the model, making it accessible for real-time interaction and testing. 
Despite the limitations—such as focusing on only two tribes and struggling to generalize to other totem styles—this project highlights the potential of AI as a valuable tool for cultural conservation. Future improvements will focus on expanding the dataset, refining the model with new training techniques, and incorporating user feedback for continuous growth. The model has achieved an accuracy rate of 90% in classifying images, showcasing its effectiveness in this domain.
