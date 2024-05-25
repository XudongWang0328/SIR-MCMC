# Research on epidemic spreading model based on Markov Chain Monte Carlo method
# 基于马尔可夫链蒙特卡洛方法下的传染病传播模型研究
## Introduction
The SIR Model is used to simulate the spread of the disease in the population, and the MCMC method is used to estimate the parameters.
Data visualization to plot confirmed cases, deaths, and recoveries in Germany over time.  
1.SIR Model definition, using Python's Theano library to implement SIR Model.  
2.Prediction creation to predict future disease spread using the defined SIR Model.  
3.Probabilistic modeling was performed using PyMC3, and the probabilistic model was set using the data to estimate the parameters of the SIR Model.  
4.Simulation and forecasting, running simulations to predict where the epidemic will go under different scenarios using the estimated parameters.  
5.The results are visualized by plotting the effective reproduction number and the effective growth rate in different scenarios to assess the impact of the intervention.
## Environment
python 3.9  
jupyter 1.0  
pandas 1.4  
numpy 1.21  
matplotlib 3.5  
scipy 1.9  
pymc3 3.11  
theano 1.0  
arviz 0.12  
seaborn 0.11  
## Reference
https://github.com/Priesemann-Group/covid19_research  
https://github.com/Priesemann-Group/covid_bayesian_mcmc  
https://github.com/ada-k/ChangePointAnalysis_Covid19Interventions  
https://github.com/Jessie1024/COVID-19-U.S.-pandemic-prediction
## 🤩
