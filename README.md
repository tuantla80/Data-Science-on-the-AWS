# Coursera: Practical Data Science on the AWS Cloud Specialization  
## Course 1: Analyze Datasets and Train ML Models using AutoML  
- Tools  
  - AWS S3  
  - Amazon SageMaker:  
    - Amazon SageMaker Data Wrangler: Dataset -> Viz -> Transform -> Statistical Bias Report -> Feature Importance  
    - Amazon SageMaker Clarify  
    
  - AWS Glue: a serverless data integration service that makes registering, discovering, preparing, and combining data (fully managed ETL: extract, transform, and load service).   
  - Amazon Athena: to run SQL queries on S3 using a distributed SQL engine called Presto.  
  - AWS Data Wrangler: Python library to load and unload data from data lakes and databases.    
- Open source  
  - Feature Importance: SHAP (SHapley Additive exPlanation) https://shap.readthedocs.io/en/latest/     
    - Shaply values based on game theory (attrubute the outcome of the game (win or loss) to individual players involved in the game.
    - Explain predictions of a ML model:  
      - Each feature value of training data instance is a player in a game  
      - ML prediction is the payout (outcome of the game)  
     - Using SHAP framework: can get local (how an individual feature contribute to final outcome) and global explanations (how data in its entirely contributes to the final outcome from ML model)  
     - SHAP can guarantee consistency and local accuracy  
     - But SHAP can be very tim consuming 
  


  
  
