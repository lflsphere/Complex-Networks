# NET 4103/7431: Complex Networks

#### Documentation  
* [Intoduction à la programmation avec le language Python](doc/IntroPython.pdf)
* [Python for data Analysis](doc/Python-for-Data-Analysis.pdf)

## Install virtual environement

#### With virtualenv
```bash
$ python -m venv netenv
$ source netenv/bin/activate
$ pip install --upgrade pip
$ python -m pip install -r requirements.txt  
```

#### with conda 
```bash
$ conda create -n netenv python=3.8    
$ conda activate netenv
$ pip3 install --upgrade pip
$ pip install -r requirements.txt  
```

## Create the jupyter kernel
```bash
$ python -m ipykernel install --user --name=netenv
```

#### Data
* Comtrade: The [UN Comtrade](https://comtrade.un.org/) Database houses detailed global trade data.
* Game Of Thrones: [Kaggle Game of Thrones: Network Analysis](https://www.kaggle.com/mmmarchetti/game-of-thrones-network-analysis/notebook)
* Wikipedia: Small subset of wikipedia articles in form : Page Id, Page Title, Keywords 
* Facebook: this dataset consists of 'circles' (or 'friends lists') from Facebook. Facebook data was collected by [1] from survey participants using this Facebook app. The dataset includes node features (profiles), circles, and ego networks.

_[1]_ the J. McAuley and J. Leskovec. [Learning to Discover Social Circles in Ego Networks](http://i.stanford.edu/~julian/pdfs/nips2012.pdf). NIPS, 2012.

#### Other Python resources online 
* [Jake VanderPlas, Python Data Science Handbook,  O′Reilly  (2016)](https://jakevdp.github.io/PythonDataScienceHandbook/)
* [Wes McKinney, Python for Data Analysis: Data Wrangling with Pandas, NumPy, and IPython, O′Reilly (2017)](https://bedford-computing.co.uk/learning/wp-content/uploads/2015/10/Python-for-Data-Analysis.pdf)
* [Scipy Lecture Notes](http://www.scipy-lectures.org/)
* [Une introduction à Python 3](http://hebergement.u-psud.fr/iut-orsay/Pedagogie/MPHY/Python/courspython3.pdf).

## Recomended Python distribution 
* [Download Anaconda pour OSX/Windows/Linux](https://www.anaconda.com/products/individual)
* [Google Colab](https://colab.research.google.com/)
