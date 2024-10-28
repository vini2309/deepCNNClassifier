# deepCNNClassifier project

Developed a CNN application using the VGG 16 architecture and transfer learning to classify images as cats or dogs. 

## workflow

1. update config.yaml
2. update secrets.yaml [optional]
3. update params.yaml
4. update the entity
5. update the configuration manager in src config
6. update the components
7. update the pipeline
8. test run pipeline stage
9. run tox for testing the package
10. update the dvc.yaml
11. run "dvc repo" for running all the stages in pipeline

![img](https://raw.githubusercontent.com/vini2309/deepCNNClassifier/main/docs/images/Data%20Ingestion%402x%20(1).png)


STEP 1: Set the env variable | Get it from dagshub -> remote tab -> mlflow tab

MLFLOW_TRACKING_URI=https://dagshub.com/c17hawke/FSDS_NOV_deepCNNClassifier.mlflow
MLFLOW_TRACKING_USERNAME=c17hawke
MLFLOW_TRACKING_PASSWORD=<> \

STEP 2: install mlflow

STEP 3: Set remote URI

STEP 4: Use context manager of mlflow to start run and then log metrics, params and model

Sample data for testing-
https://raw.githubusercontent.com/c17hawke/raw_data/main/sample_data.zip
