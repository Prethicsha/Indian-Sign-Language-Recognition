# Indian Sign Language Recognition System

This project presents an advanced Indian Sign Language (ISL) recognition system using deep learning, graph-based learning, and hand landmark analysis for accurate real-time gesture recognition.

The system combines visual, structural, and spatial feature extraction techniques to recognize Indian Sign Language gestures with improved accuracy and robustness. The architecture integrates CNN-based visual learning, Graph Convolutional Networks (GCN), MediaPipe hand landmark extraction, attention mechanisms, and prototype-guided metric learning for enhanced gesture classification.

---

## Features

- Indian Sign Language gesture recognition
- Real-time hand landmark detection using MediaPipe
- CNN + GCN hybrid architecture
- Attention-based multimodal feature fusion
- Geometry-normalized landmark processing
- Prototype-guided metric learning
- Improved recognition of visually similar gestures
- Robust gesture classification and prediction

---

## Technologies Used

- Python
- PyTorch
- PyTorch Geometric
- OpenCV
- MediaPipe
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## Dataset

The model was trained on an Indian Sign Language dataset containing:
- 35 gesture classes
- Alphabets (A–Z)
- Digits (1–9)
- 42,000+ gesture images

The dataset also includes geometry-normalized hand landmark samples for enhanced spatial consistency and real-time recognition performance.

Dataset Source:  
:contentReference[oaicite:0]{index=0}

---

## Project Structure

```plaintext
Indian-Sign-Language-Recognition/
│
├── Model.ipynb
├── gmtc_architecture.png
├── training_curves.png
└── README.md
```
## Notes

- Large preprocessing cache files generated during SLIC superpixel segmentation are not included due to GitHub file size limitations.
- Landmark datasets and intermediate preprocessing files used during training are excluded from this repository for storage optimization.
---

## Model Architecture

The system integrates:
- CNN-based visual feature extraction
- Graph-based structural learning using SLIC superpixel segmentation
- MediaPipe hand landmark processing
- Multi-Head Self-Attention (MHSA)
- Feature fusion and refinement
- Prototype-guided gesture classification

This multimodal architecture improves feature discrimination, robustness, and classification reliability for Indian Sign Language recognition.

---

## Performance

The model demonstrated high recognition accuracy across 35 Indian Sign Language gesture classes under controlled experimental conditions.

Key strengths include:
- Improved class separability
- Stable training convergence
- High-confidence predictions
- Robust real-time gesture recognition

The current system performs best under controlled conditions and demonstrates reliable real-time recognition for a limited set of gestures. Performance in unconstrained real-world environments may vary due to dataset limitations, background variations, lighting conditions, and gesture diversity.

---

## Applications

- Assistive communication systems
- Accessibility technologies
- Human-computer interaction
- Real-time gesture recognition
- AI-based sign language interpretation

---

## Future Enhancements

- Continuous sign language recognition
- Temporal gesture modeling
- Mobile and edge-device deployment
- MediaPipe Holistic integration
- End-to-end sign language translation

---

## Author

**Prethicsha D**  
Integrated M.Tech – Computer Science and Engineering (Data Science)  
VIT University