# BhaasaNet : A Real-Time Neural Framework for Indian Sign Language Recognition

BhaashaNet aims to bridge the communication gap between hearing-impaired individuals and the wider population through a real-time sign language recognition platform. Leveraging a hybrid deep learning architecture that integrates MediaPipe for keypoint extraction and a stacked LSTM network for temporal modeling, the proposed system accurately interprets Indian Sign Language(ISL) gestures. The framework emphasizes lightweight architecture and real-time responsiveness, which are suitable for deployment on web and mobile platforms. By incorporating  spatial and temporal dependencies via CNN-LSTM pipelines, BhaashaNet delivers robust performance in noisy environments, as demonstrated by accuracy and loss convergence graphs. This research is supplemented by comparative analysis across existing frameworks and datasets, including OpenHands and ISL corpus, highlighting its versatility and domain generalization. BhaashaNet is envisioned not only as a recognition system but also as an educational platform to promote inclusivity, learning and awareness of sign language across digital domains.


🧩 Overview
This notebook-based implementation is intended for academic, research, or prototyping purposes. It demonstrates how deep learning techniques can be applied to image-based gesture classification, with a specific focus on ISL alphabets or symbols using two-hand poses.

📁 Contents
ISLmodel2Hands.ipynb: The primary notebook containing the step-by-step implementation, including:

-Data preprocessing and augmentation

-CNN model architecture

-Model training and evaluation

-Visualization of performance metrics

-Model export and saving

🛠️ Requirements
To run this project, ensure you have the following Python packages installed:

pip install numpy matplotlib opencv-python tensorflow

📊 Results and Visualization

1.Loss Graph

![WhatsApp Image 2025-04-17 at 19 39 38_1512d195](https://github.com/user-attachments/assets/52ea1f05-d355-45d6-8c66-5cab0a68c403)

2.Accuracy Graph

![WhatsApp Image 2025-04-17 at 19 39 37_cb85e12b](https://github.com/user-attachments/assets/79aa1f5e-6bc6-4f5f-ab46-46b6731181fe)

![WhatsApp Image 2025-04-29 at 17 29 22_c4dc5a81](https://github.com/user-attachments/assets/19093067-df0b-4b9d-8642-1580515b9632)

![WhatsApp Image 2025-04-29 at 17 29 22_4c056b10](https://github.com/user-attachments/assets/737f76db-c0d0-4704-aeae-f5ddcf0001c6)

