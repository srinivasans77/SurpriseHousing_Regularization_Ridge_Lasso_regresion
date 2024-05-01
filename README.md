# Regularization - Surprise Housing Data Analytics
> **Surprise Housing** , US=based housing company decided to enter Australian Market. Company wants to turnout a profit with good marginal, it uses a data analytics of existing data in Australia.Need to do Regularization for this using Ridge and lasso regression

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- **Provide general information about your project here.**
  As described above, Housing company need to analyse the data and move it into Australian market to extend their business.
- **What is the background of your project?**
- Using different data and parameters, the company needs to analyse the data for buying house properties at the lower rate and sell it into higher rate. There are many parameters including the area of houses , garages and other parameters exist in a sample data file.
  - It is do Regularization to chose parameters that affects sales price including EDA with feature selection done based RFE (Automated) and Manual (p-value, VIF).  
  - R-square, Adjusted R-square are identified for this model.
  - Finaly Ridge and lasso regression need to be used and finalize the model.
- **What is the business probem that your project is trying to solve?**
  Sine the company is new to Australia but has the experience in US it takes the data and strightaway go for analyse for the property market prediction.
- **What is the dataset that is being used?**
    Years built ranges from 1872 - 2010 housing properties taken for analysis .

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- **Conclusion 1 from the analysis**
- EDA and different models implemented
- **Conclusion 2 from the analysis**
-  Regression  as - 0.7305678786021826, 0.8222557634804333
-  Ridge as 0.7305677835613592, 0.8222184761073315
-  Lasso as 0.34427877798440887, 0.3577970304469219.
   training and test sets of x & y axis respectively.

   Further analysis, For ridge, at alpha 10000 it reaches zero. For Lasso it is alpha value of 1 it reaches 0

- Conclusion 3 from the analysis
- Conclusion 4 from the analysis

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Pandas version: 2.0.3
NumPy version: 1.24.4
Matplotlib version: 3.7.4
Seaborn version: 0.13.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
The project done based on upgrad lecture and materials

## Contact
Created by [@srinisprojects77] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
