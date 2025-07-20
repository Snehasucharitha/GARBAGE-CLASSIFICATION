# GARBAGE-CLASSIFICATION
EfficientNet-based garbage classification model using deep learning and transfer learning in Python.
# Garbage Classification using EfficientNet

This project uses deep learning (EfficientNetB0) and transfer learning to classify garbage into multiple categories (plastic, glass, metal, etc.) using TensorFlow.

---

## 📂 Dataset

The dataset is not included in this repo due to size limits.  
➡️ [Click here to download it from Google Drive](https://drive.google.com/file/d/1dEew1Hv-IWv9KFNkMw0c8ncYY_l8d_Dz/view?usp=drive_link)

After downloading, place `garbage-dataset.zip` in the same folder as the notebook and unzip it using the provided code.

---

## 🚀 How to Run

1. Install the required libraries:
    ```bash
    pip install tensorflow gdown matplotlib
    ```

2. Run `CODE.ipynb` step by step.

3. The notebook will:
   - Download and unzip the dataset
   - Train EfficientNetB0 on the dataset
   - Evaluate the model
  
## Sample Output screenshots:


IMAGE 1 :


<img width="1885" height="1000" alt="Screenshot 2025-07-05 201932" src="https://github.com/user-attachments/assets/fef2fde7-7707-4c72-a8af-4bf3951771f4" />


IMAGE 2 :


<img width="1893" height="1045" alt="Screenshot 2025-07-05 202051" src="https://github.com/user-attachments/assets/02db9e82-3c8e-4b53-88d2-46b46d08142d" />




---

## 🧠 Model Summary

- **Base Model:** EfficientNetB0 (ImageNet weights)
- **Architecture:** Transfer Learning with Global Average Pooling
- **Accuracy:** Trained and validated on 6 classes

---

## 🧾 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
