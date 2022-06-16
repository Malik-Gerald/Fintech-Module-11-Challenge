# Fintech-Module-11-Challenge


# Forecasting Net Prophet

Analyze the company's financial and user data to help the company grow. This is accomplished by evaluating the data to predict whether search traffic can translate into the ability to successfully trade the stock.

## Technologies

This project leverages Python 3.9.7 ((default, Sep 16 2021, 16:59:28) [MSC v.1916 64 bit (AMD64)] :: Anaconda, Inc. on win32) with the following packages:
 
 * [python](https://www.python.org/) - Official documentation for Python 3.10.5. 
  
 * [holoviews](https://holoviews.org/) - HoloViews is an open-source Python library designed to make data analysis and visualization seamless and simple. 

 * [fbprophet](https://facebook.github.io/prophet/docs/quick_start.html) - Prophet follows the sklearn model API. We create an instance of the Prophet class and then call its fit and predict methods.

 * [pystan](https://pystan.readthedocs.io/en/latest/) - PyStan is a Python interface to Stan, a package for Bayesian inference.

* [jupyterlab](https://jupyterlab.readthedocs.io/en/stable/user/urls.html#managing-workspaces-ui) - For information about the jupyter lab remote workspace hosted by a local computer.

* [numpy](https://numpy.org/doc/stable/) - Source repository. 
NumPy is the fundamental package for scientific computing in Python. It is a Python library that provides a multidimensional array object, various derived objects (such as masked arrays and matrices), and an assortment of routines for fast operations on arrays, including mathematical, logical, shape manipulation, sorting, selecting, I/O, discrete Fourier transforms, basic linear algebra, basic statistical operations, random simulation and much more.
 
* [pandas](https://pandas.pydata.org/docs/) - Source repository. 
pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.


---

## Installation Guide

Before running the application first install the following dependencies.

```
# Install the required libraries
pip install pystan
pip install fbprophet
pip install hvplot
pip install holoviews
```

# Import the required libraries and dependencies
```
import pandas as pd
import holoviews as hv
from fbprophet import Prophet
import hvplot.pandas
import datetime as dt
%matplotlib inline
```
---

## Usage

The detailed instructions are divided into the following parts:


    Step 1: Find unusual patterns in hourly Google search traffic

    Step 2: Mine the search traffic data for seasonality

    Step 3: Relate the search traffic to stock price patterns

    Step 4: Create a time series model with Prophet

    Step 5 (optional): Forecast revenue by using time series models

---

## Contributors

Gerald Cortright and Berkeley Fintech support staff
---

## License

MIT License

Copyright (c) [year] [fullname]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
