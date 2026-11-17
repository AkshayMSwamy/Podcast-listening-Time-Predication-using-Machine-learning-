# 🎧 Podcast Listening Time Prediction Using Machine Learning

## 📌 Project Overview

Podcast Listening Time Prediction is a Machine Learning-based project that predicts how much time a user is likely to spend listening to a podcast episode.

The system analyzes different factors such as user age, podcast genre, episode length, listening platform, host popularity, episode number, and advertisements to estimate the expected listening time.

The project also provides an interactive **Streamlit Dashboard** to visualize podcast listening patterns, compare machine learning models, and generate predictions.

## 🎯 Objectives

- Predict podcast listening time using Machine Learning.
- Analyze user listening behaviour and preferences.
- Identify factors affecting podcast listening duration.
- Compare different Machine Learning algorithms.
- Develop an interactive and user-friendly dashboard.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Google Colab | Development Environment |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Plotly | Interactive Charts |
| Scikit-learn | Machine Learning |
| Streamlit | Interactive Dashboard |
| Ngrok | Public Demo Access |

## 📂 Machine Learning Algorithms

The project compares three Machine Learning algorithms:

1. **Linear Regression** – Predicts listening time using a linear relationship between input features and output.
2. **Decision Tree Regressor** – Predicts listening time using decision-based rules.
3. **Random Forest Regressor** – Combines multiple decision trees to generate predictions.

Random Forest Regressor is used as the main prediction model.

## 📊 Dataset Description

The project initially uses a synthetically generated dataset containing 5,000 podcast records.

### Dataset Features

| Feature | Description |
|---|---|
| Age | Age of the podcast listener |
| Episode_Length | Total episode duration in minutes |
| Genre | Podcast category |
| Listening_Platform | Platform used to listen |
| Episode_Number | Episode number |
| Host_Popularity | Popularity score of the host |
| Number_of_Ads | Number of advertisements |
| Age_Group | Listener age category |
| Listening_Time | Actual listening duration in minutes (target) |

**Note:** The initial dataset is synthetically generated for project demonstration and can be replaced with a real-world podcast dataset.

## ⚙️ Project Workflow

1. Dataset Generation
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Selection and Encoding
5. Machine Learning Model Training
6. Model Evaluation and Comparison
7. Listening Time Prediction
8. Streamlit Dashboard Development

## 📈 Model Evaluation

The models are evaluated using the following metrics:

- **R² Score:** Measures how well the model explains variations in listening time.
- **MAE:** Measures the average absolute prediction error.
- **RMSE:** Measures the square root of the average squared prediction error.

Actual evaluation values are generated when the notebook is executed.

## 🖥️ Dashboard Features

The Streamlit dashboard provides two main sections:

### 1. Analytics Dashboard
- Total podcast records.
- Average listening time.
- Average episode length.
- Listening time by genre.
- Listening time distribution.
- Episode length vs listening time.
- Machine Learning model comparison.
- Dataset preview.

### 2. Prediction Dashboard
- Enter listener age.
- Select podcast genre.
- Enter episode length.
- Select listening platform.
- Enter host popularity.
- Select advertisement count.
- Enter episode number.
- Predict expected listening time.
- Display predicted listening percentage.

## 🚀 How to Run the Project

### Step 1: Open Google Colab

Create a new notebook in Google Colab.

### Step 2: Install Required Libraries

```python
!pip install streamlit pyngrok plotly scikit-learn pandas numpy matplotlib seaborn
```

### Step 3: Execute the Notebook

Run the project code blocks in the following order:

1. Library installation
2. Dataset generation
3. Data preprocessing
4. Exploratory Data Analysis
5. Model training
6. Model evaluation
7. Dashboard charts
8. Streamlit application creation

### Step 4: Launch Streamlit

Run the Streamlit application using Ngrok
