[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://fahad-neuro-gait.streamlit.app/)

# 🧠 Neuro-Gait Analyzer: Parkinson's Disease Detection

## 📌 Overview
This project utilizes Computer Vision and **YOLOv8-Pose** to analyze human gait patterns for the early detection of Parkinson's Disease. Based on the 2024 IEEE study regarding "turning phase" anomalies, this system tracks specific skeletal keypoints to identify hesitation and freezing of gait (FOG).

## 🚀 Key Features
- **Real-time Pose Estimation:** Uses YOLOv8 to track 17 skeletal keypoints.
- **Gait Analysis:** Calculates joint angles (Knee, Hip) to detect stiffness.
- **Turning Phase Detection:** Specifically monitors the subject during turning movements for stability analysis.

## 🛠 Tech Stack
- **Python**
- **Ultralytics YOLOv8**
- **OpenCV**
- **NumPy / Pandas**

## 📄 Research Context
This implementation focuses on **Inertial Spectral Entropy** concepts visualized through optical flow and skeletal tracking. It validates the hypothesis that gait irregularities are most prominent during non-linear movements (turning) rather than straight walking.

## 🤝 Contributing
Open to feedback on optimizing the gait tracking algorithm!
