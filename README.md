# End-to-End-Machine-Learning-Project-with-MLflow


## Workflows

1. Update config.yaml
2. Update schema.yaml
2. Update params.yaml
2. Update the entity
2. Update the configuration manager in src config
2. Update the components
2. Update the pipeline
2. Update the main.py
2. Update the app.py



# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/Suvojeet-Haldar/End-to-End-Machine-Learning-Project-with-MLflow
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n mlproj python=3.8 -y
```

```bash
conda activate mlproj
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up your local host and port
```



## MLflow

[Documentation](https://mlflow.org/docs/latest/index.html)


##### cmd
-mlflow ui

### dagshub
[dagshub](https://dagshub.com)

MLFLOW_TRACKING_URI=https://dagshub.com/Suvojeet-Haldar/End-to-End-Machine-Learning-Project-with-MLflow.mlflow \
MLFLOW_TRACKING_USERNAME=Suvojeet-Haldar \
MLFLOW_TRACKING_PASSWORD=cc57052f2e91393a2fbf0525ad9c93613d96bc85 \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/Suvojeet-Haldar/End-to-End-Machine-Learning-Project-with-MLflow.mlflow

export MLFLOW_TRACKING_USERNAME=Suvojeet-Haldar

export MLFLOW_TRACKING_PASSWORD=cc57052f2e91393a2fbf0525ad9c93613d96bc85

```