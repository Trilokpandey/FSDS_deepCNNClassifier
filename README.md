# deep Classifier project

## workflow

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config.
6. Update the components
7. Update the pipeline
8. Test run pipeline stage
9. run tox for testing your package
10. Update the dvc.yaml
11. run "dvc repro" for running all the stages in pipeline

 ![img](https://raw.githubusercontent.com/Trilokpandey/FSDS_deepCNNClassifier/master/docs/images/project_flow.png) 

STEP 1: Set the env variable | Get it from dagshub -> remote tab -> mlflow tab

MLFLOW_TRACKING_URI=https://dagshub.com/sonu.pandey1990/FSDS_deepCNNClassifier.mlflow \
MLFLOW_TRACKING_USERNAME=sonu.pandey1990 \
MLFLOW_TRACKING_PASSWORD=<> \

STEP 2: install mlflow

STEP 3: Set remote URI

STEP 4: Use context manager of mlflow to start run and then log metrics, params and model

## sample data for testing 
https://raw.githubusercontent.com/Trilokpandey/raw_data/main/sample_data.zip