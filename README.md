# Chest-Cancer-Classification-using-MLflow-DVC


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

- [MLflow tutorial](https://youtube.com/playlist?list=PLkz_y24mlSJZrqiZ4_cLUiP0CBN5wFmTb&si=zEp_C8zLHt1DzWKK)

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/ibrahimkhalilCorp/Chest-Cancer-Classification.mlflow \
MLFLOW_TRACKING_USERNAME=ibrahimkhalilCorp \
MLFLOW_TRACKING_PASSWORD=19e5520ef8c6cad7f958bace3cb47dd5b6b98f98 \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/ibrahimkhalilCorp/Chest-Cancer-Classification.mlflow

export MLFLOW_TRACKING_USERNAME=ibrahimkhalilCorp 

export MLFLOW_TRACKING_PASSWORD=19e5520ef8c6cad7f958bace3cb47dd5b6b98f98

```

