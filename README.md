### End-to-End-MLOPs-TUTORIAL

## 01 Set up python environment

Install python
`conda create -n mlops-tutorial python=3.10`

Prepare for dependencies installation
```
pip cache purge
python -m pip install --upgrade pip
python -m pip install --upgrade setuptools
```

Install dependencies
`pip install -r requirements.txt`

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

## Dagshub setup

```
import dagshub
dagshub.init(repo_owner='comboonsong', repo_name='end-to-end-mlops-tutorial', mlflow=True)
```

