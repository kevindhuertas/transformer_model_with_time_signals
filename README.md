
# **Volcanic Signal Classification Using Transformers**

[![Estado del Proyecto](https://img.shields.io/badge/estado-en%20progreso-yellow)](#)  
[![Última Actualización](https://img.shields.io/github/last-commit/kevindhuertas/transformer_model_with_time_signals)](#)

## **Description**

This project tackles the challenge of classifying volcanic seismic signals using an advanced model based on **Transformers**, combining self-attention mechanisms with feature extraction through **Convolutional Neural Networks (CNNs)**. The proposed model is designed to capture complex temporal dependencies in raw seismic signals, making it particularly effective for identifying:

- **Long Period (LP) Events**: associated with fluid movements inside the volcano.  
- **Volcano-Tectonic (VT) Events**: linked to rock fractures.

### **Why is this important?**
Early detection and accurate classification of volcanic signals are critical for monitoring volcanic activity and mitigating natural disasters. Manual analysis of large seismic datasets is inefficient and prone to human error. This project leverages deep learning to automate and improve the accuracy of volcanic event detection. The results can be integrated into real-time monitoring systems, providing life-saving early warnings for communities near active volcanoes.

---

## **Model Architecture Visualization**

Below is a diagram of the proposed Transformer model architecture.  
![simple_architecture](https://github.com/user-attachments/assets/b82c8a9c-7006-4fda-bccd-292831642fb8)

---

## **How to Test the Model**

The `Final_architecture.ipynb` notebook is prepared to test the Transformer model. It includes:

1. **Model Training**:
   - Automatically splits the dataset into 80% for training and 20% for validation.
   - Includes an option to perform 10-fold cross-validation to evaluate model robustness.

2. **Model Saving**:
   - The trained model is saved in `.keras` format for future use.

### **Instructions**
- Open and run the `Final_architecture.ipynb` file in your Jupyter Notebook or Google Colab environment.  
- If memory issues occur, adjust the batch size (`batch_size`).  
  - **Current value**: `16`.  
  - **Suggestions**: Reduce to `8` or `4` to avoid memory errors.

### **Notes**:
- It is recommended to use GPU hardware to accelerate training.
- Ensure the dataset is preprocessed and located in the appropriate folder (`data/`).

---

## **Results**

### **Model Performance**
The best performance was achieved with the optimal model configuration:
- **Average Accuracy**: 95.6%
- **Average F1-Score (LP)**: 95.6%
- **Average AUC**: 95.8%

---

## **Contributions**

Contributions are welcome! If you have ideas or improvements, feel free to open an issue or submit a pull request.

## **Contact**

- **Kevin Huertas**  
  - [LinkedIn](https://linkedin.com/in/kevindanielop)  
