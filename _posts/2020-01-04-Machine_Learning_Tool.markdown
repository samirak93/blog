---
layout: post
title: Machine Learning Tool
date: 2020-01-04
description: This is a tool to get hands-on experience with Machine Learning concepts like Regression, Classification, Clustering.
img: projects/ml_tool/thumb.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [Python App, Bokeh, Machine Learning, Docker, Application]
---

- This is a tool to get hands-on experience with Machine Learning concepts like Regression, Classification, Clustering.
- There are pre-loaded datasets (open-source) available within each section of the application (**Note:** Adding custom datasets could a future update).
- Source of the sample datasets are mentioned in the `Data Exploration` tab within the application or can be found in the [Data sources](Data/data_sources.csv) file.
- The tool was built to make it as a medium to get hands-on visual experience to different aspect of data science like exploring/visualizing different data types, building models to make predictions, evaluating the models.
- **Note:** At this point, model optimization/selection is not an option since datasets are pre-built. This could be implemented as a future update.
- **Disclaimer:** As a data scientist, this is not the `only` way to learn/practice data science concepts. For someone with relatively less experience in coding/data-science concepts, this is a method to facilitate interest and give a brief idea about the concepts.

Link to tool: [Machine Learning Tool](https://github.com/samirak93/ML_Tool/)

<h2 align="center"> Running the application </h2>

### Clone this following epository

`$ git clone https://github.com/samirak93/ML_Tool.git`

### Locally

[![Python 3.7](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-370/)

Set the current directory to folder where `ML_Tool` (current repository) folder is downloaded (1 level above ML_Tool folder)

```py

# Optional - activate your virtualenv

$ pip install -r /ML_Tool/requirements.txt

# Once the packages are installed,

$ bokeh serve --show ml_tool

# The app should automatically open on your default browser or you can view it at http://localhost:5006/ml_tool

```

### Docker

### Setup

Install [Docker](https://docs.docker.com/install/) on your platform.

### Building

In the top level of this repository (where dockerfile is located), execute the command

`docker build --tag tag_name .`

### Running

Execute the command to start the Docker container:

`docker run --rm -p 5006:5006 -it tag_name`

Now navigate to `http://localhost:5006` to interact with the application.

---

<img src="https://raw.githubusercontent.com/samirak93/blog/master/assets/img/projects/ml_tool/exploration.png" width="700", height="700">
