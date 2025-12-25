# Hotel Booking Cancellation Prediction

## 📌 Project Overview
This project aims to predict whether a hotel booking will be canceled or not using machine learning techniques. By analyzing various features such as lead time, deposit type, and market segment, we can help hotels optimize their booking management and reduce revenue loss from cancellations.

## 📂 Dataset
The dataset used in this project is the **Hotel Booking Demand** dataset.
- **Source**: `data/hotel_bookings.csv`
- **Target Variable**: `is_canceled` (1 = Canceled, 0 = Not Canceled)
- **Features**: 33 features including booking details, customer information, and reservation status.

## 🛠️ Technologies Used
- **Python**: Primary programming language.
- **Pandas & NumPy**: Data manipulation and numerical analysis.
- **Matplotlib & Seaborn**: Data visualization.
- **Scikit-Learn**: Machine learning models and evaluation metrics.
- **Imbalanced-Learn**: Handling class imbalance (SMOTE).

## 🚀 Installation & Setup

You can run this project either on Google Colab or locally using VS Code.

### Option 1: Google Colab (Recommended for quick start)
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the `notebook/main.ipynb` file.
3. Upload the `data/hotel_bookings.csv` file to the Colab session storage or mount your Google Drive.
   - *Note: If using Google Drive, ensure the path in the notebook matches your Drive structure.*
4. Run the cells. The notebook handles library installation if needed (you might need to uncomment installation commands).

### Option 2: VS Code (Local Environment)
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Seifmakled/hotelProject.git
   cd hotelProject
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Open the project:**
   - Open the folder in VS Code.
   - Open `notebook/main.ipynb`.
   - Select the kernel (your virtual environment).

## 🧠 Methodology
1. **Data Cleaning**: Handling missing values and correcting data types.
2. **Exploratory Data Analysis (EDA)**: Visualizing correlations and distributions.
3. **Feature Engineering**: Encoding categorical variables and scaling numerical features.
4. **Handling Imbalance**: Using **SMOTE** (Synthetic Minority Over-sampling Technique) to balance the dataset.
5. **Model Training**:
   - Decision Tree
   - K-Nearest Neighbors (KNN)
   - Multi-Layer Perceptron (MLP)
   - Random Forest
6. **Evaluation**: Comparing models based on Accuracy, Precision, Recall, F1-Score, and ROC-AUC.

## 📊 Results
The project evaluates multiple models to find the best performer. The final notebook outputs the best model based on the **F1 Score**, providing a balance between precision and recall.

## 🏃‍♂️ How to Run
1. Open the notebook `notebook/main.ipynb`.
2. Run all cells to execute the data processing and model training pipeline.
