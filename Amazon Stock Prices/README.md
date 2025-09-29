READEME.md

This project applies Big Data techniques using Scikit-learn and Apache Spark MLlib to predict stock price movements.
The dataset is based on Amazon (AMZN) stock historical data, and multiple machine learning models were implemented and compared.
BigData-StockPrediction/
│
├── AmazonData/             # Raw datasets (CSV files)
│   └── AMZN_*.csv
│
├── model_results/          # Saved results of models
│   ├── scikit_results.csv
│   ├── spark_results.csv
│   └── compare_results.csv
│
├── notebooks/              # Google Colab notebooks
│   └── Amazon.ipynb
│   └──│Amazon_scikit_learn.ipynb
│    
└── README.md               # Project documentation

Models Implemented
• Linear Regression
• Decision Tree Regressor
• Random Forest Regressor

Each model was trained and evaluated in two environments:
1- Scikit-learn
2- Apache Spark MLlib

Evaluation Metrics
The models were compared based on:
• RMSE (Root Mean Squared Error)
• R² Score
• Training/Inference Time (seconds)

Results Summary
• All results are stored in the model_results/ folder.
• Visual comparisons (plots) were generated to show differences between Scikit-learn and Spark environments.

How to Run
1- Open the notebook Amazon.ipynb in Google Colab.
2- Mount Google Drive to load datasets.
3- Run all cells to preprocess data, train models, and generate results.
