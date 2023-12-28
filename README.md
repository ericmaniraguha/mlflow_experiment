# MLflow Experiments

MLflow is a comprehensive solution designed to address challenges in the dynamic landscape of machine learning (ML). It provides a set of tools and simplifies processes to streamline the ML lifecycle, fostering collaboration among ML practitioners.

## Core Components

For a detailed understanding of MLflow's core components, refer to the [official documentation](https://mlflow.org/docs/latest/introduction/index.html).

## Why Use MLflow?

The machine learning process involves various stages, from data preprocessing to model deployment and monitoring. Ensuring productivity and efficiency throughout this lifecycle presents several challenges. MLflow addresses these challenges and offers the following benefits:

- **Configurations:** Create the MLflow environment using the following steps:

    ```bash
    conda create --name mlflow-env python=3.9 -y
    conda activate mlflow-env
    ```

    Create a `requirements.txt` file and install dependencies:

    ```bash
    New-Item -Path .\requirements.txt -ItemType File
    notepad .\requirements.txt
    conda activate mlflow-env
    pip install -r .\requirements.txt
    ```

- **Tutorials and Examples:** Explore MLflow through tutorials and examples [here](https://mlflow.org/docs/latest/search.html?q=tutorial+example&check_keywords=yes&area=default). An example tutorial is available [here](https://mlflow.org/docs/2.5.0/tutorials-and-examples/tutorial.html).

## Power of MLflow

Discover the power of MLflow and its capabilities in managing your machine learning projects. Experiment, track, and reproduce results efficiently.

## DagsHub Integration

Consider exploring [DagsHub](https://dagshub.com/), a platform that complements MLflow by providing enhanced collaboration features and version control for ML projects.

For a comprehensive guide on MLflow, refer to the [official documentation](https://mlflow.org/docs/latest/).

Watch the [MLflow tutorial video](https://www.youtube.com/watch?v=qdcHHrsXA48) for a visual walkthrough of MLflow in action.

## MLflow Tracking -- from DagsHub (`https://dagshub.com/ericmaniraguha`) 

export MLFLOW_TRACKING_URI=https://dagshub.com/ericmaniraguha/mlflow_experiment.mlflow \
export MLFLOW_TRACKING_USERNAME=ericmaniraguha \
export MLFLOW_TRACKING_PASSWORD=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx \
python script.py

Happy experimenting with MLflow!
