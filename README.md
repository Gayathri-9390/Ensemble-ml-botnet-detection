# Ensemble Machine Learning Model for Efficient Botnet Attack Detection in IoT Environments

## Overview

This project focuses on detecting botnet attacks in IoT (Internet of Things) environments using Machine Learning and Deep Learning techniques. The system analyzes network traffic data and classifies traffic as normal or malicious, helping improve IoT network security.

## Objectives

* Detect botnet attacks in IoT networks.
* Compare multiple Machine Learning algorithms.
* Improve detection accuracy using ensemble learning techniques.
* Provide a user-friendly interface for attack prediction.

## Dataset

**UNSW-NB15 Dataset**

The dataset contains both normal and malicious network traffic records with various network features used for attack detection.

Files used:

* UNSW_NB15_training-set.csv
* UNSW_NB15_testing-set.csv

## Technologies Used

* Python
* Machine Learning
* Deep Learning (LSTM)
* Pandas
* NumPy
* Scikit-learn
* TensorFlow / Keras
* SQLite
* Tkinter (GUI)

## Project Structure

├── LSTM.ipynb
├── Machine Learning Models.ipynb
├── home_page.py
├── login_page.py
├── register_page.py
├── user_home.py
├── main.py
├── db_manager.py
├── users.db
├── requirements.txt
├── UNSW_NB15_training-set.csv
├── UNSW_NB15_testing-set.csv
└── README.md

## Machine Learning Models Used

* Logistic Regression
* Random Forest
* Decision Tree
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Ensemble Learning Model
* LSTM Neural Network

## Features

* User Registration and Login System
* Dataset Processing and Feature Engineering
* Botnet Attack Detection
* Ensemble Machine Learning Classification
* Deep Learning Based Detection using LSTM
* Result Visualization
* Secure Data Storage using SQLite

## How to Run

### Clone Repository

```bash
git clone https://github.com/Gayathri-9390/Ensemble-ml-botnet-detection.git
cd Ensemble-ml-botnet-detection
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
python main.py
```

## Results

The proposed Ensemble Machine Learning Model improves botnet attack detection performance by combining multiple classifiers and leveraging deep learning techniques for enhanced accuracy.

## Future Enhancements

* Real-time IoT traffic monitoring
* Cloud-based deployment
* Advanced Deep Learning architectures
* Explainable AI for attack interpretation

## Author

**Kadiyala Gayathri**

MCA Graduate | Machine Learning Enthusiast | Cybersecurity Researcher

## License

This project is developed for academic and research purposes.
