# Oral_Cancer_DP
Multi-modal AI model that classifies oral cancer cases using histopathology images and patient history. Easy to use website for doctors that integrates deep learning (Transformers,CNN) to predict cancerous and non-cancerous cases, further tumor developments/effects of  different cancer treatments (simulation on digital twin of patient).

## Features

-  **Cancer Classification**:
  - Multi-class classification model (e.g., Healthy, Stage I, II, III, IV)
  - Transformer-based architecture for robust accuracy on images and patient data

-  **Relapse Prediction & Survival Estimation**:
  - Predicts relapse probability based on medical history and initial diagnosis
  - Calculates estimated 5-year survival rate using regression and clinical insights

-  **Digital Twin**:
  - Simulates tumor progression over time
  - Tracks patient journey month-to-month/year-to-year

-  **Image Processing**:
  - Includes bounding box annotations (via Roboflow)
  - Preserves and augments annotated data using custom scripts

-  **Web Platform**:
  - Doctors can upload patient images and history via a React frontend
  - Flask backend processes and feeds data to the AI model
  - Results are stored and displayed in real-time

---

## Model Pipeline

1. **Preprocessing**:
   - Image augmentation with bounding box preservation (Albumentations)
   - Feature extraction from patient history

2. **Model**:
   - Transformer-based classifier for cancer stage

3. **Simulation**:
   - Progression modeling of tumor size/condition over time
   - Stored per patient in structured format

---

##  Datasets

- **Images**: 1500+ labeled and annotated images (Roboflow)
- **Patient Metadata**: Age, gender, symptoms, stage, diagnosis, etc.

---

## 🧰 Technologies Used

- **Frontend**: React, TailwindCSS
- **Backend**: Flask, Python
- **ML/AI**: PyTorch, Scikit-learn, Transformers, Albumentations
- **Visualization**: Matplotlib
- **Other Tools**: Roboflow, Pandas, NumPy, Seaborn, YOLO, CTGAN(sdv)

---


