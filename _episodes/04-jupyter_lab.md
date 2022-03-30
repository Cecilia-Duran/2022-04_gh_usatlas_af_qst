---
title: "Jupyter Lab"
teaching: 00
exercises: 00
questions:
- "What is JupyterLab?"
objectives:
- "Learn: number of GPU instances, selecting a Docker image and GPU memory"
keypoints:
- "Check JupyterLab documentation"
---

To support machine learning code development, our users can deploy one or more private JupyterLab applications.

To encourage fair sharing these applications are time limited. We also ask users to request only the resources that they need.
Selecting a number of GPU instances

The AF cluster has four NVIDIA A100 GPUs. Each GPU can be partitioned into seven GPU instances. This means the AF cluster can have up to 28 GPU instances running in parallel. When creating a Jupyter notebook, a user can select anywhere from 0 to 7 GPU instances as resources for the notebook.
Selecting a Docker image

Users can choose between two images: One with full anaconda (ivukotic/ml_platform:conda) and one with NVidia GPU and ROOT support (ivukotic/ml_platform:latest). The later has most of the ML packages (Tensorflow, Keras, ScikitLearn,...) preinstalled, and a small tutorial with example codes in /ML_platform_tests/tutorial. For software additions and upgrades please contact ivukotic@uchicago.edu.
Selecting GPU memory

Select 40,836 MB for an entire A100 GPU. Select 4864 MB for a MIG instance.

You can learn more about in its documentation link <a href="https://jupyterlab.readthedocs.io/en/stable/user/interface.html">JupyterLab</a>

{% include links.md %}

