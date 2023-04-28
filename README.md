# FP06-volcano-seismology

## **Names:** Kieran Yanaway (@KieranTheYanaway) Zachary Mathias (@zmathias16)


### Summary
This project aims to analyze seismic data originating from volcanic eruptions in order to determine whether the onset of an eruption has any distinguishable seismic patterns that can be observed.

### How to use this Repository
This repository contains multiple Jupyter Notebook files. The WaveformsLocating.ipynb file contains code for opening and graphing waveforms of various events from the 2018 Kilauea eruption. The FP06-volcano-seismology.ipynb file contains the final product of the figures and analysis of the figures. The Map.ipynb file contains code for constructing the map of the island of Hawai'i with marked locations of stations that we looked at. The dev folder contains code used in the development of the final notebooks contained in the notebooks folder. 

### Background Information
Volcanic eruptions cause seismic activity, and we are looking to analyze the relationship between the eruptions and seismic activity. The files in this repository use data from the Hawaii network, acquired through the IRIS web service using the ObsPy library. The seismic data demonstrate various aspects of the 2018 Kilauea eruption, giving some insight into eruption and seismic mechanics.


### Problem Statement
#### Natural disasters can pose great dangers towards human civilization and infrastructure. The capacity to predict the onset of natural disasters, therefore, provides an opportunity to afford greater protection to those elements of the modern world. Therefore, our research goal is the following: Through analysis of volcanologically originating seismic data, are there discernible, significant, and common patterns of ground-movement present at the onset of volcanic eruptions? If so, how can systems be implemented to be able to detect these patterns and thus determine when an eruption has taken, or is about to take, place?


### Datasets
[Hawaii Network](https://www.fdsn.org/networks/detail/HV/) </br>
[USGS 2018 Kīlauea](https://www.sciencebase.gov/catalog/item/61a8fa27d34eb622f699a6a6) </br>


### Tools/Packages
- Python
  - Python will be the main tool for data visualization and processing. Some of the Python libraries will also be used
- MatPlotLib
  - This Python library will be utilized for graphing of data and creation of figures
- Numpy
  - This Python library will be utilized for processing of datasets and easier manipulation of data
- ObsPy
  - This Python library will provide seismic data from the Hawaii seismic network to allow for a wide array of data analysis options.


### Planned Methodology
- Start by researching the datasets, and think about how we can analyze these datasets.
- Form a plan for what we want to find.
  - What visualizations should we make?
  - How many different datasets should we analyze?
  - What constitutes significant similarities?
- Analyze the datasets with python.
  - Perform any operations on datasets needed.
  - Select correct ranges of data.
- Interpret and write up a report describing our results.

### Expected Outcomes
It is our expectation that we will be able to formulate a comprehensive analysis of eruption seismic data and generate a deeper and useful interpretation of the data such that our problem statement goals are met.

### Anticipated Challenges
We anticipate there may be some challenges procuring a sufficient quantity of data for a full, comprehensive analysis of our problem statement. Additionally, determining an appropriate standard for analysis of the data may be challenging. Finally, the process of analysis of the data will likely prove to be generally challenging, including processing the data, comparing datasets, and drawing conclusions about the data.
