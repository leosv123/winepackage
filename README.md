# winepackage

## Workflow

1. Update config.yaml
2. Update schema.yaml
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the components


## cmd
- mlflow ui

## DagsFlow Tracking UI

MLFLOW_TRACKING_URI=https://dagshub.com/leosv123/winepackage.mlflow \
MLFLOW_TRACKING_USERNAME=leosv123 \
MLFLOW_TRACKING_PASSWORD=4d2cdefe97fd614c06a2f1e964167661d3329e05 \
python script.py


## bash

export MLFLOW_TRACKING_URI=https://dagshub.com/leosv123/winepackage.mlflow
export MLFLOW_TRACKING_USERNAME=leosv123
MLFLOW_TRACKING_PASSWORD=4d2cdefe97fd614c06a2f1e964167661d3329e05
