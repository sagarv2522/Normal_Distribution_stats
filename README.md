# Normal Distribution Analysis

<div align="left">

[![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/pandas-%23150458?style=flat-square&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-%23013243?style=flat-square&logo=numpy&logoColor=white)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-%2300768B?style=flat-square&logo=matplotlib&logoColor=white)](https://matplotlib.org/)
[![SciPy](https://img.shields.io/badge/SciPy-%230C55A5?style=flat-square&logo=scipy&logoColor=white)](https://www.scipy.org/)

<a href="https://colab.research.google.com/drive/1SWRf2pocN0nTmjtElMgRD64YG86dd7gk#scrollTo=7CbBgCm3x3-D">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Code">
</a>

</div>


 ## **Normal Distribution** : 
 A continuous probability distribution that is symmetrical on both sides of the mean and bell-shaped. Also is used to analyze data when there is an equally likely chance of being above or below the mean for continuous data whose histogram fits a bell curve. Statisticians refer to the normal curve as the Gaussian Probability Distribution, named after Gauss.

# Steps of Normal Distribution

1. Plot the Histogram
2. Apply the Empirical Rule
3. Calculate the Z-score
4. Report the Insights

## **Histogram** 📈 :
A histogram is a graphical representation of the distribution of data. It is a type of bar chart that shows the frequency of data points within a range of values. The bars of a histogram are typically of equal width, and the height of each bar represents the number of data points that fall within that range.

In below image is the distribution of our data using Seaborn library

![normal distribution-graph](https://github.com/sagarv2522/Normal_Distribution_stats/assets/109810639/c38ef606-21ba-4827-b901-dbe9ab709fbc)

## **Empirical Rule** :
The empirical rule states that, for every normal distribution

1. 68% of the data fall within 1 standard deviation of the mean
2. 95% of the data fall within 2 standard deviations of the mean
3. 99.7% of the data fall within 3 standard deviations of the mean

![Empirical rule](https://github.com/sagarv2522/Normal_Distribution_stats/assets/109810639/05259c72-81a8-42b3-aa66-94fe66c02106)

## **Z-score** :
A measure of how many standard deviations below or above the population mean a data point is

 * The Z-score is 0 if the value is equal to the mean
 * The Z-score is positive if the value is greater than the mean
 * The Z-score is negative if the value is less than the mean

Mathematical Formula is below

![z-score-formula](https://github.com/sagarv2522/Normal_Distribution_stats/assets/109810639/eebf7713-b772-42fd-b9bd-a7b17fcfd142)

But, we can use a Pre-defined function using Scipy Library

For more visit the documentation [scipy.stats.zscore](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.zscore.html)

## **Description**
**Scinario**
Imagine you are a member of an analytics team for the United States Environmental Protection Agency (EPA). The data includes information about more than 200 sites, identified by state, county, city, and local site names. One of your main goals is to determine which regions need support to make air quality improvements. Given that carbon monoxide is a major air pollutant, you will investigate data from the Air Quality Index (AQI) with respect to carbon monoxide.

## **License** :
This Repository is under BSD 3-Clause License


  
