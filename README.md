**Neural Networks and Fuzzy Logic project**

**Predicting Thyroid Cancer Risk Using Artificial Neural Networks**
Thyroid cancer is a common and increasingly diagnosed endocrine disorder. Early and accurate prediction of its risk is critical for improving patient outcomes and reducing the burden on healthcare systems. In this project, we leverage the power of Artificial Neural Networks (ANN) to predict the likelihood of thyroid cancer based on various patient features such as age, gender, TSH levels, and family history.
The dataset is preprocessed with appropriate encoding and normalization techniques. Exploratory Data Analysis (EDA) is performed using correlation matrices and statistical summaries to understand feature importance. The ANN model is built using TensorFlow and optimized using techniques such as Dropout regularization and various optimizers like Adadelta to enhance performance and prevent overfitting.

**Features in the Dataset:**
The dataset includes the following features:
Age: Age of the patient.
Gender: Male/Female.
TSH Level: Thyroid-stimulating hormone concentration.
T3/T4 levels: Triiodothyronine and thyroxine hormone levels.
Family history: Genetic predisposition to thyroid conditions.
Diagnosis: Risk label (Yes/No or Low/High Risk).
Nodule Size: feature for risk stratification and cancer diagnosis.
These features can help train classification models to assess risk levels.

Key techniques used in the project include:
- Feature-based model design with multiple dense layers  
- Dropout regularization to prevent overfitting  
- Learning rate tuning for performance optimization  
- Use of early stopping and validation strategies


