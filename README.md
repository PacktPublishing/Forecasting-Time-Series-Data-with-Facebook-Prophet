# Forecasting Time Series Data with Facebook Prophet

<a href="https://www.packtpub.com/product/forecasting-time-series-data-with-facebook-prophet/9781800568532?utm_source=github&utm_medium=repository&utm_campaign=9781800565296"><img src="https://static.packt-cdn.com/products/9781800568532/cover/smaller" alt="Forecasting Time Series Data with Facebook Prophet" height="256px" align="right"></a>

This is the code repository for [Forecasting Time Series Data with Facebook Prophet](https://www.packtpub.com/product/forecasting-time-series-data-with-facebook-prophet/9781800568532?utm_source=github&utm_medium=repository&utm_campaign=9781800568532), published by Packt.

**Build, improve, and optimize time series forecasting models using the advanced forecasting tool**

## What is this book about?

Prophet enables Python and R developers to build scalable time series forecasts. This book will help you to implement Prophet’s cutting-edge forecasting techniques to model future data with higher accuracy and with very few lines of code.

You will begin by exploring the evolution of time series forecasting, from the basic early models to the advanced models of the present day. The book will demonstrate how to install and set up Prophet on your machine and build your first model with only a few lines of code. You'll then cover advanced features such as visualizing your forecasts, adding holidays, seasonality, and trend changepoints, handling outliers, and more, along with understanding why and how to modify each of the default parameters. Later chapters will show you how to optimize more complicated models with hyperparameter tuning and by adding additional regressors to the model. Finally, you'll learn how to run diagnostics to evaluate the performance of your models and see some useful features when running Prophet in production environments.

By the end of this Prophet book, you will be able to take a raw time series dataset and build advanced and accurate forecast models with concise, understandable, and repeatable code.

This book covers the following exciting features: 
* Gain an understanding of time series forecasting, including its history, development, and uses
* Understand how to install Prophet and its dependencies
* Build practical forecasting models from real datasets using Python
* Understand the Fourier series and learn how it models seasonality
* Decide when to use additive and when to use multiplicative seasonality
* Discover how to identify and deal with outliers in time series data
* Run diagnostics to evaluate and compare the performance of your models

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1800568533) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders.

The code will look like the following:
```
model = Prophet()
model.fit(df)
future = model.make_future_dataframe(periods=365)
forecast = model.predict(future)
fig = model.plot(forecast)
plt.show()
```

**Following is what you need for this book:**
This book will help you get to grips with the task of time series forecasting using the leading open source forecasting tool available to the public, Facebook Prophet. You will learn how to implement the advanced features of Prophet to build forecast models and understand why and how to modify each of the default parameters to improve results.	

To run the code examples in this book, you will need Python 3.x installed. All examples in this book were made using Prophet version 0.71 in Jupyter Notebooks. MacOS, Windows, and Linux are all supported. Although all examples in this book will be written in Python, everything is also fully compatible with R and you may use that language if you prefer, although this book will not cover R syntax. Please refer to the official [[Prophet documentation]](https://facebook.github.io/prophet/) for R syntax.

_Chapter 2_, _Getting Started with Facebook Prophet_ will walk you through installing Facebook Prophet, and installing either Anaconda or Miniconda is strongly recommended in order to correctly install all of Prophet's dependencies. It is possible to install Prophet without using Anaconda, but it can be very diffi cult depending upon the specific configuration of your machine, and this book will assume Anaconda will be used.

In order to follow the examples, you must at least be familiar with the pandas library for data processing and Matplotlib for making plots. In a few cases, the numpy library will be used to simulate random data but following the examples will not require that you know the NumPy syntax. All of these libraries will be installed automatically as Prophet dependencies, if not already installed. All datasets are hosted and can be downloaded from this repo. 

Prophet supports parallelization with Dask but, while setting Prophet up to run on a Dask cluster will be covered, installing and using Dask is beyond the scope of this book. Similarly, this book will cover how to build interactive Prophet visualizations in Plotly but putting those together into a Dash dashboard will be left up to the reader to learn elsewhere.

With the following software and hardware list you can run all code files present in the book (Chapter 1-13).

### Software and Hardware List

| Chapter  | Software required                                                                    | OS required                        |
| -------- | -------------------------------------------------------------------------------------| -----------------------------------|
|  1 - 13  |   Python 3 (Anaconda)/Google Colab                                                   | Windows, Mac OS X, and Linux (Any) |

We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://static.packt-cdn.com/downloads/9781800568532_ColorImages.pdf).


### Related products <Other books you may enjoy>
* Hands-On Time Series Analysis with R [[Packt]](https://www.packtpub.com/product/hands-on-time-series-analysis-with-r/9781788629157) [[Amazon]](https://www.amazon.com/dp/1788629159)

## Get to Know the Author
**Greg Rafferty** is a data scientist in San Francisco, California. With over a decade of experience, he has worked with many of the top firms in tech, including Google, Facebook, and IBM. Greg has been an instructor in business analytics on Coursera and has led face-to-face workshops with industry professionals in data science and analytics. With both an MBA and a degree in engineering, he is able to work across the spectrum of data science and communicate with both technical experts and non-technical consumers of data alike.



### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781800568532">https://packt.link/free-ebook/9781800568532 </a> </p>