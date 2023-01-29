# deep Classifier project


## workflow

# How to start the project "Sofana's notes"
1. Create repo with licence MIT
1. Start with template.py
2. Fill setup.py
3. Fill setup.cfg
4. Fill tox.ini
5. Fill pyproject.toml
6. Fill init_setup.sh [This will do conda create, conda env activate and install -r requirements_dev.txt]
7. Run this command "bash init_setup.sh" ==> This only can get run in bash
8. Create and fill out Utilss and create init and common.py

Then ... [Those are Sunny's steps, but you need to then right after you do the above]
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

Then ... [Those are Sofana's steps, but you need to then right after 

12. Go to constant > in init.py add the essential



![img](https://raw.githubusercontent.com/c17hawke/FSDS_NOV_deepCNNClassifier/main/docs/images/Data%20Ingestion%402x%20(1).png)


STEP 1: Set the env variable | Get it from dagshub -> remote tab -> mlflow tab

MLFLOW_TRACKING_URI=https://dagshub.com/c17hawke/FSDS_NOV_deepCNNClassifier.mlflow \
MLFLOW_TRACKING_USERNAME=c17hawke \
MLFLOW_TRACKING_PASSWORD=<> \

STEP 2: install mlflow

STEP 3: Set remote URI

STEP 4: Use context manager of mlflow to start run and then log metrics, params and model


## Sample data for testing-
https://raw.githubusercontent.com/c17hawke/raw_data/main/sample_data.zip