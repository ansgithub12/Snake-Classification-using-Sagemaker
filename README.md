# Snake-Classification-using-Sagemaker

# XGBoost Classification Project

This project demonstrates **how to apply XGBoost — a powerful, scalable, and popular algorithm — to solve a classification problem**.  

Using a real-world tabular dataset, we:
- Prepare and clean the data
- Split it into training and testing sets
- Train an XGBoost classifier to learn patterns
- Evaluate its performance on the test set

The notebook highlights:
✅ This project focuses on building a machine learning pipeline for the classification of snake images. It uses a pretrained ResNet18 model to extract deep learning features from images stored in an Amazon S3 bucket. The extracted features are then used to train a highly efficient XGBoost model. The pipeline is deployed and executed using AWS cloud services, ensuring scalability, ease of access, and faster processing.
✅ The proposed solution involves two key stages:
1.	Feature Extraction:
A pretrained ResNet18 convolutional neural network (CNN) model is used to extract high-dimensional feature representations from snake images stored in an S3 bucket. These features, capturing essential patterns and visual clues, are compiled into a structured dataset.
2.	Classification Model:
Using the extracted features, an XGBoost classifier is trained to predict the class labels of snake species. XGBoost, known for its speed and accuracy, efficiently handles the structured feature data, achieving high performance.


---

## 🟣 Why XGBoost?

✅ **Boosted trees outperform many models on tabular data.**  
✅ **Scalable and fast.**  
✅ Naturally handles missing values.  
✅ Allows for flexible hyperparameter tuning.

---

## 🟣 Tech Stack

- **Python 3.x**
- **XGBoost**
- **Cloud services**
 
---


