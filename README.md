# Risk Modelling for Renal Post Transplant Complications
![REnal-Transplantation_Banner-1](https://user-images.githubusercontent.com/108168115/214647915-4f90e138-6cea-4945-b19e-99dea55e74b1.png)

<br>


## Project sopnser
<br>

<br>

![image](https://user-images.githubusercontent.com/108168115/215900285-f5dbc3ce-b2eb-4f7d-b766-647748a0ecab.png)

<br>


## Code and Resources Used :

* __Python Version:__ 3.9

* __Packages:__ pandas, numpy, matplotlib, seaborn, sklearn.

* __Requirements:__  `!pip install pandas`
`!pip install numpy` `!pip install matplotlib` `!pip install seaborn` `!pip install scikit-learn`


### Dataset :


### Problem Statement:

Renal transplantation is a common procedure for patients with end-stage renal disease, however, post-transplant complications such as graft rejection, infection, and chronic allograft nephropathy can occur. Early detection and prevention of these complications can greatly improve the success rate of renal transplantation. The goal of this project is to build a machine learning model that accurately predicts the risk of renal post-transplant complications, allowing medical professionals to take proactive measures to prevent or mitigate these complications. The model will be trained on historical patient data, including demographic information, medical history, and post-transplant monitoring data, to identify key risk factors and accurately predict the likelihood of complications. The goal is to provide a tool that can be used in clinical practice to improve patient outcomes and increase the success rate of renal transplantation.

### Goals: 
* The project Aims to predict graft survival using various technique our aim is to compare the Performance of the models:

 
### Objective: -
* minimize to the Renal post-transplant complications
* Specifications: -
   * The Survival monogram will developed using model with the best prediction performance. A Concordance index (for discrimination), a Brier Score (For Calibration),    * and Decision curve analysis (for net benefit and clinical usefulness will be applied as model evaluation metrics
   
### Machine learning algorithms used:-

* Random Survival Forest (RSF) 

* Elastic Net-Based Cox (ENBC) (to consider Sprsity and Correlation)

* standard Cox

### Evaluation metrics used to assess the model:
 * C- index :- The concordance index or c-index is a metric to evaluate the predictions made by an algorithm. It is defined as the proportion of concordant pairs divided by the total number of possible evaluation pairs.
 
 * Brier score :-  Brier score calculates the mean squared error between predicted probabilities and the observed values (actuals). The value of the Brier score is always between 0.0 and 1.0, where a model with perfect skill has a score of 0.0 and the worst has a score of 1.0.
   
<br>
<br>
<div class="text-center">
  <img src="https://user-images.githubusercontent.com/108168115/215897245-6b9aab03-be09-4dc6-a185-c86d5584ff68.png" class="img-fluid" alt="" />
</div>


### EDA - Exploratory Data Analysis

* Platelets, Hemoglobin level and White blood cell counts are basic elements of immune system in our health.

* This case clearly meant that, however if elements of immune system is decrease then most of the renal complications will occur in future. Which reflect to graft survival time and graft survival indicator at the end

* Platelets, Hemoglobin level and White blood cell counts are directly proportional to each other. If this elements increase then graft survival time is also increased.

### Post transplantcomplications 

* Non adherence, Urological complications, Vascular & Cardiovascular complications, Diabetes, Hyper tension, Acute rejection, Chronic rejection, Gastro intestine




### Note:- 
