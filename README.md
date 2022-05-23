# Using the Rendered.ai SDK

This Jupyter notebooks repository is for learning how to use the Rendered.ai `anatools` SDK to access our powerful platform. 

Note that you must have a valid Rendered.ai account prior to running the notebooks. View the latest [SDK documentation here](https://sdk.rendered.ai/) and more guides at [the Rendered.ai Support Site](https://support.rendered.ai/)!

## Table of Contents

### 1. Getting Started
- [Generate Synthetic Data with Graphs and Datasets](./1_getting_started/Generate%20Synthetic%20Data%20with%20Graphs%20and%20Datasets.ipynb)


### 2. Administration
- [Organization and Workspace Administration](./2_administration/Organization%20and%20Workspace%20Administration.ipynb)
- [Channel and Volume Administration](./2_administration/Channel%20and%20Volume%20Administration.ipynb)


### 3. [`anatools` for ML](./3_anatools_for_ML)
Covering the Rendered.ai Microservices:
- Dataset Analytics
- Domain Adaptation
- Annotations


### 4. ML Integrations
- [Integrations with NVIDIA TAO](./4_integrations/nvidia-tao)


## Environment
Python 3 is required; 3.7 is preferred.

These notebooks depend on the Rendered.ai Python module [anatools](https://pypi.org/project/anatools/). Make sure you install it in your environment.

<code>pip install anatools</code>

Other Required Python Modules. These must be installed prior to running the notebooks.
- PyYAML
- json
- wget
- numpy
- matplotlib
- PIL