# ISIC-2019-Classification

This project focuses on building a deep learning model for skin lesion classification based on dermoscopy images, using the dataset provided in the ISIC 2019 Challenge. It includes data preprocessing, model training, and evaluation.

## 📁 Project Structure

- `prepare_data.ipynb`: Preprocessing notebook that loads and organizes the ISIC 2019 dataset for model training.
- `task1.ipynb`: Trains a deep learning model using only image data.
- `task2.ipynb`: Enhances classification by incorporating additional metadata (e.g., age, gender, anatomical site).

## 🧪 How to Use

1. **Download Dataset**  
   Download the ISIC 2019 dataset from the [official ISIC website](https://challenge2019.isic-archive.com/). Ensure the directory structure is as follows:

2. **Preprocess Data**  
Run `prepare_data.ipynb` to prepare the dataset for training.

3. **Train Model**  
Open and run `task1.ipynb` to train a classification model using image data.  
Optionally, use `task2.ipynb` to include metadata in the model.

4. **Evaluate Model**  
Use the evaluation code in the notebooks to compute accuracy, sensitivity, specificity, and other metrics.
