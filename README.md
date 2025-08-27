# Major-Project
🧑‍💻 Temporal and Spatial Deepfake Detection using Hybrid AI (CNN + LSTM)
📌 Overview

Deepfakes are AI-generated synthetic videos/images that can manipulate human faces and voices, making them appear authentic. With the increasing risk of misinformation and misuse, detecting deepfakes is a critical challenge.

This project implements a hybrid AI architecture that combines Convolutional Neural Networks (CNNs) for spatial feature extraction and Long Short-Term Memory (LSTM) networks for temporal sequence modeling. Together, they enable robust detection of manipulated video content.

🎯 Key Features

Spatial Analysis (CNN): Detects frame-level artifacts such as texture inconsistencies, lighting mismatches, and blending errors.

Temporal Analysis (LSTM): Captures unnatural motion patterns, abnormal blinking, and lip-sync mismatches across video frames.

Hybrid Model: CNN encodes per-frame features → LSTM models frame sequences for final classification.

Scalable Architecture: Can be extended with Transformers for improved temporal modeling.

🏗️ Architecture
Video Frames → CNN (Feature Extraction) → LSTM (Sequence Learning) → Dense Layer → Output (Real / Fake)


CNN → Learns spatial features from each frame.

LSTM → Learns temporal dependencies across frames.

Classifier → Outputs probability of video being Deepfake.

📂 Dataset

You can experiment with public datasets such as:

FaceForensics++

DFDC (DeepFake Detection Challenge)

🤝 Contribution

Contributions are welcome! Feel free to open issues or submit pull requests.
