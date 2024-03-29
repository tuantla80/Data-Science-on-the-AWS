# Coursera: Practical Data Science on the AWS Cloud Specialization  
## Course 1: Analyze Datasets and Train ML Models using AutoML  
### Tools  
  - AWS S3 (Simple Storage Service)  
  - Amazon SageMaker:  
    - Amazon SageMaker Data Wrangler:  
      - Python library to load and unload data from data lakes and databases.
      - Dataset - Viz - Transform - Statistical Bias Report - Feature Importance  
    - Amazon SageMaker Clarify: Statistical Bias Report - Model Bias Report - Explainability - Drift. Good for dataset with millions of rows.  
    - Amazon SageMaker Autopilot: data exploration & transformation - identify ML problem - selecting ML algos - training and performing hyperparameter tuning. Containing Notebooks and source codes.  
      
   - AWS Glue: a serverless data integration service that makes registering, discovering, preparing, and combining data (fully managed ETL: extract, transform, and load service).   
  - Amazon Athena: to run SQL queries on S3 using a distributed SQL engine called Presto.  
  - Amazon SageMaker Ground Truth: Data lanbeling
- Open source  
  - Feature Importance: SHAP (SHapley Additive exPlanation) https://shap.readthedocs.io/en/latest/     
    - Shaply values based on game theory (attrubute the outcome of the game (win or loss) to individual players involved in the game.
    - Explain predictions of a ML model:  
      - Each feature value of training data instance is a player in a game  
      - ML prediction is the payout (outcome of the game)  
     - Using SHAP framework: can get local (how an individual feature contribute to final outcome) and global explanations (how data in its entirely contributes to the final outcome from ML model)  
     - SHAP can guarantee consistency and local accuracy  
     - But SHAP can be very time consuming   
 ### Built-in algos  
   - Classification: XGBoost, k-NN  
   - Regression: Linear Learner, XGBoost  
   - Time-series forcasting: DeepAR Forecasting (RNN models)  
   - Clustering:  
      - Dimensional reduction: PCA  
      - Anomaly detection: Random Cun Forest - RCF
      - Clustering / Grouping: k-means  
      - Topic modeling: Latent Dirichlet Allocation (LDA), Neural Topic Model (NTM)  
   - Image processing  
      - Image classification: CNN
      - Object detection:   
      - Computer vision: Semantic Segmentation  
   - Text analysis:  
      - Machine translation: Sequence to Sequence  
      - Text summarization: Sequence to Sequence   
      - Speech to text: Sequence to Sequence   
      - Text classification: Blazing Text       
  
  


  
  
