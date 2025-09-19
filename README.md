# LDA from Scratch: Visualization & Classification

This project provides a complete, from-scratch implementation of Linear Discriminant Analysis (LDA) in Python. The code is presented in a Jupyter Notebook that demonstrates both of LDA's primary use cases:
1.  **Exploratory Data Visualization**: Applying LDA to the entire Iris dataset to visualize its powerful class-separation capabilities.
2.  **Machine Learning Preprocessing**: Using LDA as a dimensionality reduction step in a formal classification pipeline, including a train-test split, model training, and performance evaluation.

---

### Workflow Overview 

The `Assignment-1.ipynb` notebook is structured in two main parts:

**Part 1: Exploratory Visualization**
* The LDA algorithm is implemented from scratch in a Python class.
* The algorithm is applied to all 150 samples of the Iris dataset.
* A 2D scatter plot is generated to visualize how effectively LDA projects the 4D data into a space where the three classes are linearly separable.

**Part 2: Classification Pipeline & Evaluation**
* The projected data is split into training (80%) and testing (20%) sets.
* A Logistic Regression classifier is trained on the 2D training data.
* The trained model makes predictions on the unseen test data.
* The model's performance is thoroughly evaluated using:
    * **Confusion Matrix**: To see the breakdown of correct and incorrect predictions per class.
    * **Classification Report**: To analyze precision, recall, and F1-score.
    * **Test Set Visualization**: A scatter plot of the test data that highlights any misclassified points.

---

### How to Run the Code

**1. Prerequisites**
You need Python 3 and a Jupyter environment (like JupyterLab or VS Code with the Jupyter extension).

**2. Dependencies**
The project requires the following libraries:
* `numpy`
* `pandas`
* `matplotlib`
* `seaborn`
* `scikit-learn`

You can install them all using pip:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyterlab
```

**3. Execution**

1.  Clone this repository.
2.  Navigate to the project directory in your terminal.
3.  Launch JupyterLab:
    ```bash
    jupyter lab
    ```
4.  Open the `Assignment-1.ipynb` file and run the cells sequentially.

