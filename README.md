# Chest-Cancer-Classification-using-MLflow

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the dvc.yaml

## MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

run this to store in environment variables:
os.environ["MLFLOW_TRACKING_URI"]="https://dagshub.com/rohit180497/Chest-Cancer-Classification-using-MLflow.mlflow"
os.environ["MLFLOW_TRACKING_USERNAME"]="rohit180497"
os.environ["MLFLOW_TRACKING_PASSWORD"]="689dfcbaf1e20f8fcaf3a38624a5b87fe082969e"

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/rohit180497/Chest-Cancer-Classification-using-MLflow.mlflow 
export MLFLOW_TRACKING_USERNAME=rohit180497 
export MLFLOW_TRACKING_PASSWORD=689dfcbaf1e20f8fcaf3a38624a5b87fe082969e

```


### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag

## About MLflow & DVC

MLflow

 - Its Production Grade
 - Trace all of your expriements
 - Logging & taging your model


DVC 

 - Its very lite weight for POC only
 - lite weight expriements tracker
 - It can perform Orchestration (Creating Pipelines)

