# Lizardon

Lizardon is DataScience Environment for Local Machine.

# Usage

```zsh
% cd Lizardon
% docker-compose up -d
% open http://localhost:8080
% open http://localhost:5000
```

# Overview

- kaggle-images/python
    - Jupyter Lab
- mlflow

# Customize

You can install pip packages in Dockerfile

```
FROM gcr.io/kaggle-images/python
RUN pip install mlflow

# Add pip install package here
```
