# Alzheimers



# Using CNN to Classify Alzheimers
![alt text](/notebooks/report/figures/readmepic1.jpg)

# Table of Contents

<!--ts-->
 * [General Setup Instructions](https://github.com/howen7/Alzeimers#general-setup-instructions)
 * [Context of Project](https://github.com/howen7/Alzeimers#Context)
 * [Definitions](https://github.com/howen7/Alzeimersw#Definitions)
 * [Data](https://github.com/howen7/Alzeimers#Data)
 * [Process](https://github.com/howen7/Alzeimersmodels-used--methodology)
 * [Results](https://github.com/howen7/Alzeimers#Results)
 * [Next Steps](https://github.com/howen7/Alzeimers#Future-Investigations-and-Recommendations)
<!--te-->

```
.
├── README.md     
├── environment.yml
├── notebooks
│   ├── exploratory
│   │   ├── 
│   │   ├── 
│   │   ├── 
│   │   ├── 
│   │   ├── 
│   │   ├── 
│   │   ├── 
│   │   ├──
│   │   ├── 
│   │   ├── 
│   │   ├── 
│   │   ├── 
│   │   ├──
│   │   ├──
│   │   └── 
│   └── report
│       ├── figures
│       │   ├── 
│       │   ├── 
│       │   ├── 
│       │   ├── 
│       │   ├── 
│       │   ├── 
│       │   ├── 
│       │   ├──
│       │   ├──
│       │   └── 
│       └── 
├── reports
│   └── 
└── src
    ├── data
    │   ├── 
    │   ├── 
    │   └── 
    └──
    

```
#### Repo Navigation Links 
 - [Final summary notebook](https://github.com/howen7/Alzeimerstree/main/notebooks/report/final_notebook.ipynb)
 - [Exploratory notebooks folder](https://github.com/howen7/Alzeimers/tree/main/notebooks/exploratory)
 - [src folder](https://github.com/howen7/Alzeimerstree/main/src)
 - [Presentation.pdf](https://github.com/howen7/Alzeimerstree/main/reports)
 
# General Setup Instructions 

Ensure that you have installed [Anaconda](https://docs.anaconda.com/anaconda/install/) 

### `housing` conda Environment

This project relies on you using the [`environment.yml`](environment.yml) file to recreate the `housing` conda environment. To do so, please run the following commands *in your terminal*:
```bash
# create the housing conda environment
conda env create -f environment.yml
# activate the housing conda environment
conda activate housing
# if needed, make housing available to you as a kernel in jupyter
python -m ipykernel install --user --name churn --display-name "Python 3 (alzeimers)"
```
# Context:

This projects goal was to provide to create a convolutional neural network to identify 4 different stages of alzheimer

# Aims:

This project aims to:<br>

- Investigate what the model is picking up on when its classifying these images<br>
- Classify degree of Alzheimer with high accuracy.<br>
- Create an online version using flask that will allow user to submit a ct scan of the brain and it classifies how <br>
    
# Definitions:



# Data:

This project uses dataset from Kaggle found [here](https://www.kaggle.com/tourist55/alzheimers-dataset-4-class-of-images).<br>
The data set compromises of 4 stages of alzeimers labeled: Mild Demented, Moderate Demented, Non Demented, Very Mild Demented


# Models used + Methodology:

This project Uses CNN to classify:<br>



    
# Results:
![alt text](/notebooks/report/figures/Model_performance.png)


### Best model: Prophet Model



#### Future Investigations and Recommendations:

