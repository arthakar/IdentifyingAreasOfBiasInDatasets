# IdentifyingAreasOfBiasInDatasets
The intent of this research is to explore different and potentially more intuitive methods of evaluating fairness of different datasets and the potential biases caused by certain features. 

Objectives:
The goals of this project were to:
1. Identify, analyze and understand the various softwares, analysis tools, and machine
learning models that can be used to assist the process of quantifying bias.
2. Identify a tool that is able to measure the amount of bias present in a given machine
learning model.
3. Test the tool with a known specific dataset that is known to have sensitive features and
hence the potential to have bias.

DataSets
One of the first tasks was to choose a dataset that was easily available and known to have
sensitive features, hence the potential to have bias.
* [1994 US Census Dataset](https://www.openml.org/search?type=data&sort=runs&id=1590&status=active) from Open ML: A sample dataset used with the guide that was
provided with FairLearn.
* [Heart Disease Cleveland UCI Dataset](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci?resource=download): A dataset that was analyzed using LIME in a
research paper about the intersection of Explainable AI and Healthcare.

Software Packages, Libraries
Azure VMs
Azure ML Dashboard
Libraries
* azureml-contrib-fairness
* fairlearn&gt;=0.6.2
* joblib
* liac-arff
* raiwidgets
* fairlearn 0.8.0
* lime · PyPI



