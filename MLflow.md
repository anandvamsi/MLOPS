# MLFLOW
its a open source tool, that address the deploying of ML models from (experimentation,reproducibility,deployment and a central model registry)
## Features of MLOPS
- Creation:- Created by Databricks
- Compatability: compatiable  with numerous libs such tensor flow,pytorch,apache spark,Scikit learn
- Language Agnostic: Any programming language API-first approch
- Integration: Deploy modesl in docker contaienrs, K8s apache spark.

## Components of MLFlow
-  Tracking ::- Track experiment to record and compare paramters,results
  
### Challanges in Tradition model
Notes:: Traditional method is dev team tracks the different verion of the code like codeMode1.ipynb,codeMode2.ipynb,codeMode3.ipynb

### Features of Tracking 
- Using the Tracking feature, Allow you to track your expriments by recording the paramters,code versions and results of the experiments
- Allows to log and track ML experiments in central place using python,REST and R JAVA APIs
- Provides a web based UI for exploring runs,visualization metrics and paramters and compare experiments
- Supports different tracking servers,including local and remote serves, making easy to scale and share experiments across different teams

  
## Projects
Package code to ensure resuability and reproducebility

### Features of Project
- Designed to simplify the process of packaging,redproducbility and sharing of ML code
- Allow users to package their code and deps in a reproduciable format which is earlier to share


## Models 
Provide a std unit for packaging models
Designed to streamline and simplify the process of deploying ML mode to different env.
Allows users to package their trained modesl into std format which is supported by many downtream tools in the pipeline.
can be deployed using different deployment options such as REST APIs,Docker containers and serverless functions

## Registry
central model store for model versioning
Centrailized respository for managing ML models,version of these models and metadata.
search Interface allows users to search for model by name,metadata and other criteria,making it easy to find the right model
quickly

