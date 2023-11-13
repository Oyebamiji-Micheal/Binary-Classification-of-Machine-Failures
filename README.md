<h1 style="text-align: center;">Binary Classification of Machine Failures</h1>

[![Language](https://img.shields.io/badge/Python-darkblue.svg?style=flat&logo=python&logoColor=white)](https://www.python.org)
[![Framework](https://img.shields.io/badge/sklearn-darkorange.svg?style=flat&logo=scikit-learn&logoColor=white)](http://www.pytorch.org/news.html)
[![Framework](https://img.shields.io/badge/Streamlit-red.svg?style=flat&logo=streamlit&logoColor=white)](https://github.com/Oyebamiji-Micheal/Employee-Status-Prediction-Web-App/tree/main)
![hosted](https://img.shields.io/badge/Streamlit-Cloud-DC143C?style=flat&logo=streamlit&logoColor=white)
![build](https://img.shields.io/badge/build-passing-brightgreen.svg?style=flat)
![reposize](https://img.shields.io/github/repo-size/Oyebamiji-Micheal/Binary-Classification-of-Machine-Failures)

<h3>A machine leanring web app which involves predicting whether a machine fails or not</h3>

You can view the live demo <a href="#">here</a>

<img src="images/repo_cover.jpeg">

<h2>Table of Contents</h2>

- [Overview and Objective](#overview_objective)
- [Dataset](#data)
- [Insights from EDA](#insights)
- [Models and Evaluation Metrics](#model)
- [Model Selection - Conclusion](#conclusion)
- [Resources and References](#reference)

<a id="overview"></a>
<h2>Overview</h2>
<p align="justify">

</p>

<a id="data"></a>
<h2>Dataset</h2>
<p align="justify">
The dataset used in this project contains the information of 10000 samples of vehicles. Key features of the dataset include attributes related to various aspects of a vehicle such as <strong>rotation speed</strong>, <strong>tool wear</strong>, and so on. The link to the dataset as well as the description can be found on <a href="https://www.kaggle.com/datasets/dineshmanikanta/machine-failure-predictions">Kaggle.</a>
</p>

<a id="insights"></a>
<h2>Insights from EDA</h2>
<p align="justify">
My primary aim is not to build the 'perfect model' by performing extensive analysis and feature engineering. Rather, my aim is to get started with some MLOps practices. In this vein, this project contains the minimal EDA and data preprocessing - I hope to gradually build and extend my knowledge as I complete more tasks. However, below are some of the insights drawn from the data due to the little EDA I have performed</p>

- The proportion of faulty to non-faulty machines is highly imbalanced

<p align="center"><img src="images/machine_proportion.jpeg"></p>

- Faulty machines seem to have a <code>Process Temperature [K]</code> of around 308 - 312.

<p align="center"><img src="images/process_temp_dist.jpeg"></p>
