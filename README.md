# Welcome  
Welcome to the **TravelTide** project!  
This repository represents the culmination of my advanced education in **Data Analytics & Science** at [Masterschool](https://de.masterschool.com/). The primary objective is to use **Machine Learning (ML)** methods to perform **Customer Segmentation** on the, publicly available, Traveltide Dataset.

This project implements various techniques for data preprocessing, KMeans for unsupervised clustering and visualization to derive actionable insights into customer behaviors. All files necessary to run the segmentation algorithm and explore the results are included in this repository.

---

# Table of Contents  
- [Installation](#installation)  
  - [Running the Project Interactively](#how-to-run-interactively)  
  - [Dependencies](#dependencies)  
- [Project Objectives](#goals-for-this-notebook)  
  - [Data Handling](#data-handling)  
  - [Data Analysis](#data-analysis)
- [License](#license)  

---

# Installation  

To recreate the project environment and explore the notebook interactively, you can follow these steps:  

### How to Run Interactively  

1. **Clone or Download the Repository**  
   - Download this repository as a ZIP file and extract it to your desired location.  
   - Alternatively, run the following command in your terminal to clone the repository:  
     ```bash  
     git clone https://github.com/kohlmeiv/TravelTide.git  
     ```

2. **Set Up a Python Environment**  
   - Install Python (preferably version 3.8 or later) from [python.org](https://www.python.org).  
   - Create a virtual environment to avoid dependency conflicts. Use the following commands:  
     ```bash  
     python -m venv traveltide_env  
     source traveltide_env/bin/activate      # For MacOS/Linux  
     traveltide_env\Scripts\activate         # For Windows  
     ```  

3. **Install Required Dependencies**  
   - Navigate to the directory where the repository is saved:  
     ```bash  
     cd TravelTide  
     ```  
   - Install all dependencies listed in the `requirements.txt` file:  
     ```bash  
     pip install -r requirements.txt  
     ```  

4. **Open the Jupyter Notebook**  
   - Install Jupyter Notebook if it’s not already installed:  
     ```bash  
     pip install notebook  
     ```  
   - Open the notebook `traveltide_project.ipynb` in your default editor. If you use VS Code (recommended):  
     - Open VS Code.  
     - Navigate to the **Explorer** view (Ctrl+Shift+E).  
     - Click "Open Folder" and select the folder containing this repository.  
     - Install the **Python Extension** if prompted.  
     - Open `traveltide_project.ipynb` directly in VS Code.  

5. **Run the Notebook**  
   - Ensure the kernel is set to the Python environment you created earlier.  
   - Run the cells sequentially to execute the code, analyze data, and visualize results.  

---

### Dependencies  

The following libraries and frameworks are required:  

#### **Basic Operations & Mathematics**  
- `numpy`  
- `pandas`  
- `sqlalchemy`  
- `datetime`  
- `scipy`  

#### **Visualizations**  
- `matplotlib`  
- `seaborn`  
- `plotly`  

#### **Preprocessing**  
- `sklearn.preprocessing` (StandardScaler, LabelEncoder, OneHotEncoder, MinMaxScaler, RobustScaler)  
- `sklearn.decomposition` (PCA)  

#### **Machine Learning**  
- `sklearn.cluster` (KMeans)  
- `sklearn.metrics` (silhouette_score, accuracy_score, confusion_matrix, roc_auc_score)  

All dependencies are listed in the `requirements.txt` file and can be installed with a single command (see above).  

---

# Goals for This Notebook  

### **Data Handling**  
- Import and load data using **Pandas**.  
