
# Stock Price Prediction

# Introduction

In this project, a unidirectional multi-layer LSTM was trained on various stocks namely Google (GOOGL), Apple(AAPL), Amazon(AMZN), Microsoft(MSFT), Netflix(NFLX), and Nvidia(NVDA) to predict their closing prices. 

# DataSet

The dataset for this project originates from the [Yahoo Finance](https://ca.finance.yahoo.com/). 

**Features**
- `Open`
- `High`
- `Low`
- `Close`
- `Volume`
- `DateTime`

The details for the above mentioned featured were provide for every two minutes interval from 24th January 2020 to 4th March 2020.

# Dependencies

### Install

This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [pytorch](https://pytorch.org/docs/1.2.0/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

It's recommended to install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.



# Usage

Clone or download the repository

In a terminal or command window, navigate to the top-level project directory `finding_donors/` (that contains this README) and run one of the following commands:

```bash
ipython notebook finding_donors.ipynb
```  
or
```bash
jupyter notebook finding_donors.ipynb
```


# Results

### Google

Train Loss: 3.12 RMSE | Test Loss: 19.21 RMSE

![](google.jpg)


### Apple

Train Loss: 0.87 RMSE | Test Loss: 6.39 RMSE

![](google.jpg)


### Amazon

Train Score: 5.01 RMSE | Test Score: 7.12 RMSE

![](amazon.jpg)


### Microsoft

Train Score: 0.42 RMSE | Test Score: 0.89 RMSE

![](microsoft.jpg)


### Netflix

Train Score: 0.81 RMSE | Test Score: 1.44 RMSE

![](netflix.jpg)


### Nvidia

Train Score: 1.02 RMSE | Test Score: 1.45 RMSE

![](nvidia.jpg)





```python

```
