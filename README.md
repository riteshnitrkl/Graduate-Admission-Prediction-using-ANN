 Graduate Admission Prediction using Artificial Neural Networks (ANN)

In this project, we leverage the power of **Artificial Neural Networks (ANN)** to predict the chances of a student getting admitted to a graduate program based on their academic and profile scores.

By learning from historical data—including GRE scores, TOEFL scores, CGPA, and more—the model captures hidden patterns and delivers predictive insights that can help students gauge their admission chances.



Problem Statement

Goal:
Predict the probability of admission to a graduate program using various input features like:
- GRE Score
- TOEFL Score
- University Rating
- Statement of Purpose (SOP)
- Letter of Recommendation (LOR)
- Undergraduate CGPA
- Research Experience (0 or 1)

Tech Stack & Concepts

- **Python**  
- **TensorFlow / Keras**  
- **Pandas, NumPy**  
- **Matplotlib / Seaborn (for visualization)**  
- **Sklearn (for preprocessing & evaluation)**  
- Artificial Neural Networks  
- Regression Metrics (MSE, MAE, R² Score)



 Dataset

The dataset used is the [Graduate Admissions dataset](https://www.kaggle.com/mohansacharya/graduate-admissions) from Kaggle. It contains profiles of students and their respective chances of admission.

 How It Works

### Model Architecture:
- **Input Layer**: 7 features  
- **Hidden Layers**: 1–2 Dense layers with ReLU activation  
- **Output Layer**: 1 neuron with sigmoid or linear activation (for probability or score prediction)  

### Steps:
1. Load and preprocess the data
2. Normalize features
3. Build and compile the ANN
4. Train the model on historical data
5. Evaluate performance on test set


Credit to CampusX Learning
