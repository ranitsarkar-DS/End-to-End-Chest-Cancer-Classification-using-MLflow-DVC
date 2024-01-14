# End-to-End-Chest-Cancer-Classification-using-MLflow-DVC
Deep Learning End to End project

## Workflows

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

MLFLOW_TRACKING_URI = https://dagshub.com/ranitsarkar/End-to-End-Chest-Cancer-Classification-using-MLflow-DVC.mlflow \
MLFLOW_TRACKING_USERNAME = ranitsarkar \
MLFLOW_TRACKING_PASSWORD = ae20a5c8d7fc72380987455496767d00d155d573\
python script.py

Run this to export as env variables:

```bash
export MLFLOW_TRACKING_URI=https://dagshub.com/ranitsarkar/End-to-End-Chest-Cancer-Classification-using-MLflow-DVC.mlflow

export MLFLOW_TRACKING_USERNAME=ranitsarkar

export MLFLOW_TRACKING_PASSWORD=ae20a5c8d7fc72380987455496767d00d155d573
```
