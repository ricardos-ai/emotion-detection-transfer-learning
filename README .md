# 🧠 Facial Emotion Recognition with Transfer Learning

This project demonstrates an AI model capable of detecting **human emotions from facial images** using **transfer learning**.  
It applies modern deep learning techniques to classify images into seven emotion categories: *anger, disgust, fear, happiness, sadness, surprise, neutral.*

---

## 🚀 Overview
- **Framework:** PyTorch
- **Task:** Image classification (Computer Vision)
- **Dataset:** ~12,000 labeled facial emotion images
- **Classes:** 7 emotions
- **Approach:** Fine-tuned pretrained CNN (ResNet18/VGG16) with custom classification head

---

## 🧩 Key Features
- Efficient use of **transfer learning** for small datasets  
- Modular **PyTorch pipeline** (Dataset, DataLoader, training loop)  
- Real-time performance and solid generalization  
- Visual analysis of predictions and accuracy

---

## 🧠 Model Highlights
| Metric | Result |
|---------|--------|
| Training Accuracy | ~90% |
| Validation Accuracy | ~85% |
| Framework | PyTorch |
| Optimizer | Adam |
| Loss | CrossEntropyLoss |

---

## 🧪 Run the Project

```bash
git clone https://github.com/<yourusername>/emotion-recognition.git
cd emotion-recognition
pip install -r requirements.txt
jupyter notebook Facial_Emotion_Recognition.ipynb
```

---

## 📂 Structure

```
emotion-recognition/
│
├── Facial_Emotion_Recognition.ipynb   # Main notebook
├── requirements.txt                   # Dependencies
├── README.md                          # Project overview
└── models/                            # (optional) Saved model weights
```

---

## 📈 Future Improvements
- Integrate **data augmentation** and **class balancing**
- Try **EfficientNet**, **MobileNet**, or **Vision Transformers**
- Build an **interactive demo** (Streamlit / Gradio)

---

## 👨‍💻 Author
**Ethan Lopin**  
AI Engineer — Deep Learning | Computer Vision | MLOps  
📫 [LinkedIn](https://www.linkedin.com/in/ethanlopin) | 💻 [GitHub](https://github.com/elopin)

---

## 🪪 License
Released under the **MIT License**.
