# databricks_sample

 These sample notebooks make it easy to compare Azure Databricks with single node Virtual Machine.
 
 ## Environment
 ### Azure Databricks
 - XGBoost, scikit-learn, DataFrame sample
  - Runtime:  5.2ML Beta
  - Python: 3
  - Auto scaling: Enable
  - Worker type: Standard_D32s_v3
  - Driver type: Same as worker
  - Min workers: 2
  - Max workers: 8
  
  need to install xgboost and spark_sklearn library
  
 - PyTorch sample
  - Runtime:  5.2ML Beta(**GPU**)
  - Python: 3
  - Auto scaling: **Disable**
  - Worker type: Standard_NC6s_v3(beta)
  - Driver type: Same as worker
  - workers: 8
 
 ### Virtual Machine
 
 'Data Science Virtual Machine for Linux (Ubuntu)' is easy to use.
 
  - XGBoost, scikit-learn, DataFrame sample
   - Instance size: Standard_D32s_v3
  
 - PyTorch sample
  - Worker type: Standard_NC6s_v3(beta)

 
