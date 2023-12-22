Network-Security-with-ML
A solution that should able to predict whether the domain is real or fake.

## Dataset

```
https://data.mendeley.com/datasets/72ptz43s9v/1

link: https://prod-dcd-datasets-cache-zipfiles.s3.eu-west-1.amazonaws.com/72ptz43s9v-1.zip

```


## Workflows

The generic workflow for any project follows this steps:

1. Start with templete.py file
2. Create custom log
3. Create requirements.txt file and execute (update later)
4. Write common useful functions in src/{project_name}/utils/common.py

Project Specific worflow:

1. Update config.yaml
2. Update secrets.yaml [optional] (for database credentials)
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. update the components
7. Update the pipeline
8. Update the main.py
9. Uodate the dvc.yaml

