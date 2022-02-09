# TAO with Synthetic Data
The ana_tao resource contains a Jupyter Notebook and supporting configuration files for training the FasterRCNN TAO model
using Rendered.ai synthetic imagery data.
The notebook is a tutorial that demonstrates the use of the Rendered.ai SDK in conjunction with the NVIDIA TAO toolkit
as described in the article, ["Using the Rendered.ai Synthetic Data Platform with NVIDIA TAO to Improve Training Data through Closed-Loop ML"](https://medium.com/renderedai/using-the-rendered-ai-f2f0ff92d619).

A user can access datasets on Rendered.ai and evaluate a production grade object detection models for various levels of object obstruction.
The process helps the user understand how CV models will perform on real-world datasets by enabling modification of data generation configurations,
or graphs, to test hypotheses gleaned from viewing inferences. For example, how object detection accuracy is affected by training data with
objects at different densities or obstruction levels.

[Register now](https://www.rendered.ai/waitlist.html) to get started with synthetic data!

## Using the ANA_TAO Resource
Extract the ana_tao resource files into a directory, e.g. `ana_tao`, and make a project based on that top level folder. The project will contain the obstruction_fasterrcnn experiment and will be the root location for Rendered.ai datasets collected when running the experiment.

The first few cells of obstruction_fasterrcnn.ipynb install the python environment dependencies. Optionally, if running locally, the notebook will run with the packages installed for your jupyter kernel.

The notebook concludes with the following results.

|![](https://renderedai-public-assets.s3.us-west-2.amazonaws.com/Accuracy_vs_Obstruction.png)|
|:---:|
|*Effect of number of objects in a Rendered.ai graph on OD performance*|

## About Rendered.ai
[Rendered.ai](https://rendered.ai) is a platform-as-a-service for synthetic data that enables data scientists to overcome the costs and challenges of acquiring and using real data
for training machine learning and artificial intelligence systems.

|![](https://renderedai-public-assets.s3.us-west-2.amazonaws.com/Rendered.ai_Dashboard.png)|
|:---:|
|*View of Rendered.ai GUI*|

## Other versions of ana_tao
Datasets are available for the 'sample_dataset' or 'datasets' versions.

The 'datasets' version contains 3 batches of annoteted images for download

`ngc registry resource download-version "isv-ngc-partner/renderedai/ana_tao:datasets"`

| Dataset | | Description |
| --- | --- | ----------- |
| 200runs_10objectScene | | 200 images with low object obstruction |
| 200runs_40objectScene | | 200 images with moderate object obstruction |
| 200runs_70objectScene | | 200 images with high object obstruction |

The 'sample_dataset' version contains 10 images for viewing here in the file browser:

| Item |Description |
| --- | ----------- |
| sample_dataset/ | A sample dataset of 50 objects per scene |
| 10 Object Scene.png | Sample of 10 objects per scene |
| 40 Object Scene.png | Sample of 40 objects per scene |
| 70 Object Scene.png | Sample of 70 objects per scene |
| 100 Object Scene.png | Sample of 100 objects per scene |
