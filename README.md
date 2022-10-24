# Genre Classification
End-to-end Reproducible Machine Learning Pipeline for Music Genre Classification

![image](https://user-images.githubusercontent.com/32045137/197345178-bcf24c27-dad7-4408-9817-8d28c0a9798c.png)

This project contains an integration of a series of tools to create a end-to-end reproducible pipeline that includes:
1. Weights and Biases: for data version control and experiment tracking
2. MLFlow and Conda: for enviroment isolation and command centralization
3. Hydra: for parameter configuration and hyperparameter tuning
4. GitHub: for code versioning

## Instructions:
You can run the entire pipeline with a configured Weights and Biases account and installing Python, Conda and MLFlow.

To run use on the root of the project:
```console
mlflow run .
```
