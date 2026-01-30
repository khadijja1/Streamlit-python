# 🍄 Mushroom Classification Web App

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.0+-FF4B4B.svg)](https://streamlit.io)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Machine Learning](https://img.shields.io/badge/ML-Classification-orange.svg)](https://scikit-learn.org/)

### 🚀 [**Try the Live App**](https://app-python-jjqwgkziauqderd6t5wprt.streamlit.app/) 🚀

An interactive machine learning web application built with Streamlit that classifies mushrooms as **edible** or **poisonous** using multiple classification algorithms. Users can select different models, tune hyperparameters in real-time, and visualize comprehensive performance metrics.

> **🌐 Live Demo**: [https://app-python-jjqwgkziauqderd6t5wprt.streamlit.app/](https://app-python-jjqwgkziauqderd6t5wprt.streamlit.app/)

## 🎯 Project Overview

This project demonstrates an end-to-end machine learning pipeline, from data preprocessing to model deployment. It provides an intuitive interface for comparing three popular classification algorithms and understanding their performance through interactive visualizations.

**🌐 Live Application**: The app is deployed and accessible at [https://app-python-jjqwgkziauqderd6t5wprt.streamlit.app/](https://app-python-jjqwgkziauqderd6t5wprt.streamlit.app/)

Try it yourself - no installation required!

### ✨ Key Features

- **🎛️ Interactive Model Selection**: Choose between SVM, Logistic Regression, and Random Forest classifiers
- **⚙️ Real-time Hyperparameter Tuning**: Adjust model parameters and see results instantly
- **📊 Comprehensive Metrics**: View accuracy, precision, recall, F1-score, and more
- **📈 Dynamic Visualizations**: 
  - Confusion Matrix
  - ROC Curve with AUC score
  - Precision-Recall Curve
- **🎯 High Performance**: Achieves up to **99.8% accuracy** with Random Forest
- **🚀 Fast Predictions**: Instant classification results with optimized models

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **Python 3.8+** | Core programming language |
| **Streamlit** | Web application framework |
| **Scikit-learn** | Machine learning algorithms and metrics |
| **Pandas** | Data manipulation and analysis |
| **NumPy** | Numerical computations |
| **Matplotlib** | Data visualization |

## 📊 Dataset

The application uses the **UCI Mushroom Dataset**, which contains:
- **8,124 samples** of mushrooms
- **22 categorical features** (cap shape, cap color, odor, gill size, etc.)
- **2 classes**: Edible (e) and Poisonous (p)
- **No missing values**

All categorical features are encoded numerically for machine learning processing.

## 🤖 Machine Learning Models

### 1. Support Vector Machine (SVM)
- **Kernel**: RBF (Radial Basis Function)
- **Tunable Parameters**: C (regularization), Gamma
- **Best Use**: Non-linear classification with clear margins

### 2. Logistic Regression
- **Solver**: liblinear
- **Tunable Parameters**: C (regularization)
- **Best Use**: Fast, interpretable binary classification

### 3. Random Forest Classifier
- **Ensemble Method**: Multiple decision trees
- **Tunable Parameters**: Number of estimators, Max depth, Bootstrap
- **Best Use**: High accuracy with feature importance insights
- **Performance**: **~99.8% accuracy** on test set

## 🚀 Getting Started

### Option 1: Try the Live Demo (Recommended)

**No installation needed!** Access the app directly at:
👉 **[https://app-python-jjqwgkziauqderd6t5wprt.streamlit.app/](https://app-python-jjqwgkziauqderd6t5wprt.streamlit.app/)**

### Option 2: Run Locally

#### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)

#### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/khadijja1/Streamlit-python.git
   cd Streamlit-python
   ```

2. **Create a virtual environment** (recommended)
   ```bash
   # Windows
   python -m venv venv
   venv\Scripts\activate

   # macOS/Linux
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install required packages**
   ```bash
   pip install -r requirements.txt
   ```

#### Running the Application

```bash
streamlit run app.py
```

The application will open in your default browser at `http://localhost:8501`

## 📱 How to Use

1. **Select a Classifier** from the sidebar (SVM, Logistic Regression, or Random Forest)
2. **Adjust Hyperparameters** using the interactive sliders
3. **View Results** including:
   - Classification metrics (accuracy, precision, recall, F1-score)
   - Confusion matrix visualization
   - ROC curve with AUC score
   - Precision-Recall curve
4. **Compare Models** by switching between classifiers and observing performance differences

## 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1-Score | Training Time |
|-------|----------|-----------|--------|----------|---------------|
| **Random Forest** | **99.8%** | **99.8%** | **99.8%** | **99.8%** | ~2s |
| **SVM** | 98.5% | 98.4% | 98.6% | 98.5% | ~5s |
| **Logistic Regression** | 95.2% | 95.1% | 95.3% | 95.2% | ~1s |

*Results may vary based on hyperparameter settings and train/test split*

## 📁 Project Structure

```
Streamlit-python/
├── app.py                  # Main Streamlit application
├── mushrooms.csv           # Dataset
├── requirements.txt        # Python dependencies
├── README.md              # Project documentation
├── LICENSE                # MIT License
└── .gitignore            # Git ignore rules
```

## 🤝 Contributing

Contributions are welcome! If you'd like to improve this project:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Khadija**
- GitHub: [@khadijja1](https://github.com/khadijja1)
 Scikit-learn contributors for robust ML tools

## 📧 Contact

For questions or feedback, please open an issue on GitHub or reach out through my profile.

---

⭐ **If you found this project helpful, please consider giving it a star!** ⭐
