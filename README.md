# example-package

## Virtual Environment

pdm is used to manage dependencies. To install dependencies, run the following command:

```bash
pdm install
```

podm uses venv to manage virtual environments. To activate virtual environment, run the following command:

```bash
source venv/bin/activate
```

## MLFlow

MLFlow is a tool for tracking and managing machine learning experiments. To run the MLFlow server, run the following command:

```bash
mlflow server --host 127.0.0.1 --port 8080
```