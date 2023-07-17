# Exploratory Data Analysis on Smart Home System 

This is an in-depth introspection on the data from a Smart Home System Dataset with weather Information. The acquired data file, 
stored in a CSV format, contains the readings with a time span of 1 minute of house appliances in kW from a 
smart meter and weather conditions of that particular region.

### ◘ Methodologies & Technologies applied
* Check and Clean data
* Diagnose and fix structural errors
* Address duplicates & outliers
* Univariate inspection
* Bivariate inspection
* Feature correlations
* Seaborn & Matplotplib visualizations

### ◘  Required Modules
* pandas 2.0.3
* missingNo 0.5.2
* matplotlib 3.7.0
* seaborn 0.12.2

### ◘ Jupyter core packages
* IPython          : 8.10.0
* ipykernel        : 6.19.2
* ipywidgets       : 7.6.5
* jupyter_client   : 7.3.4
* jupyter_core     : 5.2.0
* jupyter_server   : 1.23.4
* jupyterlab       : 3.5.3


## Project Organization
------------

    ├── LICENSE
    │
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    │
    ├── README.md          <- The top-level README for developers using this project.
    │
    ├── data set           <- Contains the primary data set suppressed inside a zip file.
    │
    ├── docs               <- Folder contains documentation about the features of the data set.
    │
    │
    ├── analysis           <- Jupyter notebooks, where the primary analysis is carried out.
    │
    ├── references         <- Data source links and references based on the observations.
    │
    ├── figures            <- All the generated graphs utilized for this study.
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    │


--------


<br/><br/>

### ◘ Installation (using pip)
In Jupyter, the console commands can be executed by the *‘!’* sign before the command within the cell. For example, If the following code is written in the Jupyter cell, it will execute as a command in CMD.
To intall any modules effectively, the sys python package is used and works as follows:
```
import sys
!{sys.executable} -m pip install [package_name]                               
```
1. For Pandas, run:
```
!{sys.executable} -m pip install pandas                                                  
```
2. To install missingNo:
```
!{sys.executable} -m pip install missingno                                                  
```
3. Matplotlib can be installed by running the following command:
```
!{sys.executable} -m pip install matplotlib
```
4. Lastly, for seaborn:
```
!{sys.executable} -m pip install seaborn
```

<br/><br/>

### ◘ Import Packages
To *import* the dependencies, simply open the preferred IDE or Notebook: 
1. For Pandas, run the following command:
```
import pandas as pd                                   
```
2. To use missingno, run:
```
import missingno as msn                                      
```  
3. Import matplotlib using:
```
import matplotlib.pyplot as plt                                     
```
4. Seaborn can be accessed by:
```
import seaborn as sns                                      
```
<br/><br/>

### ◘ Supplementary Resources
* https://pypi.org/project/pandas/
* https://pypi.org/project/matplotlib/
* https://pypi.org/project/seaborn/
* https://pypi.org/project/missingno/

<br/><br/>

### ◘ MIT License
Copyright (c) 2023 Shahriar Rahman

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

===========================================================================



