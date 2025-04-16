# 🚦 Road Signs Identification using a Neural Network

This project focuses on developing an intelligent road sign recognition system using Convolutional Neural Networks (CNNs). The goal is to help reduce road accidents and improve driver awareness by building an accurate, real-time traffic sign classification system. The model is trained on a traffic sign dataset and integrated into a simple GUI for user-friendly predictions.

---

## 🎯 Objectives

- Accurately classify traffic signs using deep learning (CNNs)
- Develop a user-friendly interface to display real-time predictions
- Assist in driver safety and support the development of autonomous driving systems
- Explore deployment potential in real-world vehicle environments

---

## 🧠 Methodology

1. **Data Collection & Preprocessing**
   - Image dataset of Indian road signs
   - Data visualization and label mapping
   - Normalization and resizing for CNN input

2. **Model Development**
   - Convolutional Neural Network built using Keras Sequential API
   - Layers: Conv2D, MaxPooling, Dropout, Flatten, Dense
   - The CNN model was trained on labeled images and evaluated using separate validation and test sets to ensure reliable and accurate performance on unseen data.

3. **Evaluation & Tuning**
   - Accuracy checked on unseen data
   - Model parameters (epochs, learning rate) tuned to reduce underfitting

4. **Deployment**
   - Integrated with a GUI using `tkinter` to classify signs from user-uploaded images
   - GUI tested with multiple signs to validate model output

---

## 📈 Results

- Model successfully classifies a wide range of traffic signs with high accuracy
- GUI provides real-time image selection and prediction display
- Robust against common variations in image quality and orientation

---

## 🚀 Future Scope

- Deploy the system on embedded hardware for in-vehicle usage
- Enhance model speed with dimension reduction techniques
- Improve recognition under harsh conditions (e.g., fog, glare)
- Expand the dataset to include global road sign standards

---

## 🧾 Reports

- [📊 Project Presentation](Road%20Signs%20Identification%20using%20a%20Neural%20Network.pptx)

---

## 📃 License

This project is for academic purposes and not intended for real-world deployment without further validation.
