**AI-CRISPR sgRNA Designer**

An AI-powered CRISPR sgRNA design tool that identifies and ranks candidate sgRNAs from DNA sequences using machine learning-based efficiency prediction.

**Project Overview**

This project takes a DNA sequence as input and:

Identifies potential sgRNA candidates
Extracts biological features
Predicts cutting efficiency using ML
Ranks Top sgRNA candidates
Visualizes results

This tool helps researchers design efficient CRISPR guide RNAs quickly and effectively.

**🔬 Features**

✅ DNA sequence input

✅ PAM sequence detection (NGG)

✅ sgRNA candidate extraction

✅ Feature engineering

✅ Machine learning prediction

✅ Ranking Top sgRNAs

✅ Visualization (Graph Output)

✅ Clean pipeline workflow

**Example Workflow**

Input DNA Sequence
        ↓
PAM Detection
        ↓
sgRNA Candidate Extraction
        ↓
Feature Extraction
        ↓
ML Prediction
        ↓
Ranking
        ↓
Visualization


## Results

![Results](Result Graph.png)

## Top sgRNA Candidates

![Top Candidates](Result N Rank.png)

## Pipeline Output

![Pipeline](Pipeline output.png)


**Example DNA Sequence**

You can test using this example:
GAGTCCGAGCAGAAGAAGAAGGGCTCCCATCACATCAACCGGTGGCGGCGGCGGCGGCGGCGG
CGGCGGCGGCGGCGGCGGCGGCGGCGGCGGCGGCGGCGGCGGCGGCGGCGGCGGCGGCGGCGG

**Installation**

Clone the repository:

git clone https://github.com/parthkhedu38-sudo/AI-CRISPR-sgRNA-Designer.git

Go to project folder:

cd AI-CRISPR-sgRNA-Designer

Install dependencies:

pip install -r requirements.txt

## How to Run
How to Run

Run the main script:

python main.py

**Machine Learning Model**

The model:

Extracts sgRNA features
Predicts efficiency
Ranks candidates

Model Type:

Random Forest / ML Regression Model

**Project Structure**

AI-CRISPR-sgRNA-Designer
│
├── main.py
├── requirements.txt
├── README.md
├── Result Graph.png
├── Result N Rank.png
└── Pipeline output.png

**Future Improvements**

Web Interface

Off-target prediction

Deep learning model

Genome integration

Batch sequence processing

## Author
Parth Khedu
