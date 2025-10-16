#  Phishing Website URLS Detection using XGBoost Classifier

This project implements a high-accuracy machine learning model to classify website URLs as either **benign (legitimate)** or **malicious (phishing)**.  
The core of the project is an **XGBoost Classifier** trained on features engineered from raw URL strings.



##  Features

-  High-Accuracy Classification:  
  Utilizes an XGBoost model achieving approximately **97% accuracy** on unseen test data.

-  Comprehensive Feature Engineering:  
  Extracts **30 distinct features** from URL strings to identify phishing patterns.

-  Real-Time Prediction System:  
  Includes an **interactive command-line interface** to test live URLs and get instant predictions with confidence scores.

-  Detailed Performance Evaluation:
  Provides a **confusion matrix** and a **classification report** for model analysis.

---

  Dataset

The model was trained on the **`phishing.csv`** dataset, which contains **11,054 URL samples**.

- ~55% URLs labeled as **malicious**
- ~45% URLs labeled as **benign**
- All features are binary (**1** **0** or **-1**)

---

 ### Installation and Setup

Follow these steps to set up and run the project on your local machine.

###  1 Clone the Repository
```bash
git clone https://github.com/PesuMithun/SPAM_URL_DETECTION.git
cd SPAM_URL_DETECTION
``` 

### 2 Create a requirements.txt File
pandas
scikit-learn
xgboost
tldextract
matplotlib
seaborn

### 3️ Install Dependencies
pip install -r requirements.txt

### 4 Verify the Dataset
```
SPAM_URL_DETECTION/
│
├── phishing.csv
├── XGBOOSTER_CLASSIFIER.py
├── requirements.txt
└── README.md
```

### 5️ Run the Project
python XGBOOSTER_CLASSIFIER.py



