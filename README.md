# Breast Cancer Cell Classification

This project implements a **Breast Cancer Cell Classification** using various machine learning algorithms on the **Breast Cancer Wisconsin (Diagnostic) dataset**. The goal is to classify tumors as **malignant** or **benign** based on extracted features.

---

## 📊 **Model Performance**

### 1. **Gaussian Naive Bayes**  
- **Accuracy**: **94.15%**

### 2. **Support Vector Machine (SVM)**  
- **Accuracy**: **95.74%**

### 3. **Linear Regression**  
- **Accuracy**: **69.11%** (Note: Linear regression is not ideal for classification tasks.)

---

## 📖 **How to Run the Project**

This project is implemented in a Jupyter Notebook called `Cancer Cell Classification.ipynb`. You can run the notebook step by step to understand the entire process.

### 🛠 **Installation Steps**

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Breast-Cancer-Cell-Classification.git


2. Navigate to the project directory:

   ```bash
   cd Breast-Cancer-Cell-Classification
   ```

3. Install required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `Cancer Cell Classification.ipynb` and run the cells.

---

## 🧑‍💻 **How It Works**

The notebook implements the following steps:

1. **Loading the Dataset**:
   The dataset is loaded from `sklearn.datasets.load_breast_cancer`.

2. **Data Preprocessing**:

   * Split the dataset into features (`X`) and labels (`y`).
   * Divide the dataset into **training** and **test** sets.

3. **Model Training**:

   * **Gaussian Naive Bayes** classifier is applied.
   * **SVM** classifier is trained on the dataset.
   * **Linear Regression** is used (although it’s not ideal for classification problems).

4. **Model Evaluation**:
   Each model’s performance is evaluated using **accuracy**.

---

## 📈 **Results**

* **Gaussian Naive Bayes**: Accuracy of **94.15%**.
* **SVM**: Accuracy of **95.74%**.
* **Linear Regression**: Accuracy of **69.11%**.

---

## 🛠 **Technologies Used**

* **Python**: Programming language used for implementing the models.
* **scikit-learn**: Machine learning algorithms and tools.
* **NumPy**: For numerical computations.
* **Pandas**: For data manipulation.
* **Matplotlib/Seaborn**: For data visualization.

---

## ⚙️ **Dependencies**

To install the required libraries, use the following:

```bash
pip install scikit-learn numpy pandas matplotlib seaborn
```

---

## 📩 **Contact**

Feel free to reach out with any questions or suggestions for improvements!

### Key Updates:
- **Notebook Mention**: I've updated the file to specifically mention that the project is done in a Jupyter Notebook (`Cancer Cell Classification.ipynb`).
- **Step-by-Step**: Added steps on how to open and run the Jupyter Notebook.
- **No Script Execution**: The instructions are focused on running the notebook rather than a standalone Python script.
  
This version should fit your project setup perfectly. Let me know if you need any more adjustments or additional sections!
```
