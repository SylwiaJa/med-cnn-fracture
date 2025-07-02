# Medical Diagnosis Support System with CNN

Engineering thesis project: classification of X-ray images using Convolutional Neural Networks (CNN) and transfer learning.

## Project Structure

- `notebooks/` – experiments and training notebooks (Colab)
- `models/` – saved models (.h5)
- `src/` – Python scripts (data preparation, training, evaluation)
- `app/` – GUI application (Streamlit)
- `plots/` – visualizations, Grad-CAM heatmaps
- `data/`, `drive/` – local datasets (ignored by Git)

## Requirements

Python 3.9–3.12

To install required libraries:

```
pip install -r requirements.txt
```

## How to Run the GUI

```
streamlit run app/app.py
```

## Architectures Used

The project uses the VGG16 and ResNet50 architectures with transfer learning, trained on the FracAtlas dataset from Kaggle (X-ray fracture classification).

## Evaluation Metrics

- Accuracy
- F1-Score
- AUC (ROC)
- Confusion Matrix
- Grad-CAM heatmaps

## Project Status

In development (June–August 2025)  
Engineering thesis project – AI in medical image analysis

