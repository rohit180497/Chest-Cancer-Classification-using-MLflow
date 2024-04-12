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

#### cmd
mlflow ui
### dagshub

run this to store in environment variables:
os.environ["MLFLOW_TRACKING_URI"]="https://dagshub.com/rohit180497/Chest-Cancer-Classification-using-MLflow.mlflow"
os.environ["MLFLOW_TRACKING_USERNAME"]="rohit180497"
os.environ["MLFLOW_TRACKING_PASSWORD"]="689dfcbaf1e20f8fcaf3a38624a5b87fe082969e"

# Run this to export as env variables in terminal:
'''bash

export MLFLOW_TRACKING_URI=https://dagshub.com/rohit180497/Chest-Cancer-Classification-using-MLflow.mlflow \
export MLFLOW_TRACKING_USERNAME=rohit180497 \
export MLFLOW_TRACKING_PASSWORD=689dfcbaf1e20f8fcaf3a38624a5b87fe082969e \

'''