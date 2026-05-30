# Deep Learning-Based Threat Detection Against Zero-Day Attacks

## 📋 Project Overview

This project develops an advanced **Intrusion Detection System (IDS)** using machine learning and deep learning techniques to detect zero-day attacks in Industrial Internet of Things (IIoT) environments. The system combines multiple ML/DL methodologies to achieve high accuracy in real-time threat detection while minimizing false positives and false negatives.

### Key Features
- 🔍 **Advanced Threat Detection**: Identifies and adapts to evolving attack strategies
- ⚡ **Real-Time Detection**: Scalable and efficient detection of zero-day attacks
- 📊 **Reduced False Positives/Negatives**: Superior performance compared to conventional IDS
- 🧠 **Machine Learning & Deep Learning**: Combines ML and DL techniques for enhanced accuracy
- 🎯 **Efficient Feature Selection**: Optimized feature set ensuring high efficiency with minimal computational burden
- 📈 **Adaptable Architecture**: Designed for scalability and adaptability to evolving threats

### Datasets Used
- **NSL-KDD**: Network intrusion dataset
- **UNSW-NB15**: Comprehensive network-based attack dataset

---

## 🛠️ Setup & Installation

### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook
- Git

### Step 1: Clone the Repository
```bash
git clone https://github.com/debabrat321/Deep-learning-based-thread-detection-against-Zero-day-attack.git
cd Deep-learning-based-thread-detection-against-Zero-day-attack
```

### Step 2: Create a Virtual Environment (Recommended)
```bash
# Using venv
python -m venv venv

# Activate virtual environment
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
```

### Step 3: Install Dependencies
```bash
pip install -r requirements.txt
```

**Key Dependencies:**
- TensorFlow/Keras - Deep learning framework
- Scikit-learn - Machine learning algorithms
- Pandas - Data manipulation and analysis
- NumPy - Numerical computing
- Matplotlib/Seaborn - Data visualization
- Jupyter - Interactive notebooks

### Step 4: Launch Jupyter Notebook
```bash
jupyter notebook
```

Navigate to the notebook files and run the cells sequentially to train and evaluate the IDS models.

---

## 📁 Project Structure

```
Deep-learning-based-thread-detection-against-Zero-day-attack/
├── README.md                          # Project documentation
├── requirements.txt                   # Python dependencies
├── notebooks/                         # Jupyter notebooks
│   ├── data_exploration.ipynb        # Data analysis and visualization
│   ├── feature_engineering.ipynb      # Feature selection and extraction
│   ├── model_training.ipynb           # ML/DL model training
│   ├── model_evaluation.ipynb         # Performance evaluation
│   └── zero_day_detection.ipynb       # Zero-day attack detection
├── data/                              # Dataset directory
│   ├── NSL-KDD/                       # NSL-KDD dataset
│   └── UNSW-NB15/                     # UNSW-NB15 dataset
├── models/                            # Trained models
└── results/                           # Results and visualizations
```

---

## 🚀 Usage

### 1. Data Preparation
- Place your datasets (NSL-KDD, UNSW-NB15) in the `data/` directory
- Run `data_exploration.ipynb` to understand data characteristics

### 2. Feature Engineering
- Execute `feature_engineering.ipynb` to perform feature selection
- Optimize features for model efficiency

### 3. Model Training
- Run `model_training.ipynb` to train ML/DL models
- Supported models include:
  - Neural Networks (Deep Learning)
  - Random Forest
  - Support Vector Machines (SVM)
  - Gradient Boosting
  - Ensemble Methods

### 4. Model Evaluation
- Execute `model_evaluation.ipynb` to assess model performance
- Metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC

### 5. Zero-Day Attack Detection
- Run `zero_day_detection.ipynb` for real-time threat detection

---

## 📊 Performance Metrics

The proposed IDS achieves:
- **High Accuracy**: Significantly better than conventional IDS approaches
- **Reduced False Positives**: Minimized security alerts on benign traffic
- **Reduced False Negatives**: Effective detection of actual threats
- **Real-Time Performance**: Scalable for large-scale network monitoring
- **Adaptability**: Capable of detecting evolving attack patterns

---

## 🔐 Technologies & Frameworks

- **Deep Learning**: TensorFlow, Keras
- **Machine Learning**: Scikit-learn, XGBoost
- **Data Processing**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn, Plotly
- **Jupyter**: Interactive notebook environment

---

## 📈 Future Enhancements

- Integration with live network traffic
- Model deployment in production IIoT environments
- Real-time alerting system
- Advanced ensemble methods
- Federated learning for distributed IDS
- Explainability using SHAP/LIME techniques

---

## 👤 Author

**Debabrat**

---

## 📜 License

This project is open source and available under the MIT License.

---

## 🤝 Contributing

Contributions are welcome! Please feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📞 Support & Questions

For questions or issues, please:
- Open an issue on GitHub
- Contact the repository maintainer

---

## 🙏 Acknowledgments

- NSL-KDD Dataset: University of New Brunswick
- UNSW-NB15 Dataset: University of New South Wales
- Deep Learning community and open-source contributors

---

**Last Updated**: May 2026
