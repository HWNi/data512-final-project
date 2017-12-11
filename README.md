# DATA512 - A2: Bias in data

# Abstract
In this project, we saw an exploratory data analysis to the Yelp data from the Yelp Dataset Challenge by using correlation analysis and visualizations. The research question is about finding correlations between restaurant overall rating and varioius restaurant attributes. My hypotheses was verified that some aspects of restaurant are more likely to determine the overall rating of restaurant than other attributes, but most attributes barely have correlation (i.e. correlation coefficient is between 0.3 and -0.3) with restaurant overall rating. This might be due to the large amount of null values in the dataset and unbalanced data. In genearl, the Yelp rating appears to be normal distributed, but we do need to be cautious when interpreting the restaurant rating because Yelp ratings may suffer from bias due to stereotype or customers' psychological suggestions.

# Getting Started
You will need Python 3.X and Jupyter notebook installed to reproduce this project by running _hcds-a2-biasn.ipynb_. 
To install Python 3, see [download](https://www.python.org/downloads/) and [beginner's guide](https://www.python.org/about/gettingstarted/)
To install Jupyter Notebook, follow [installation](http://jupyter.readthedocs.io/en/latest/install.html)

Addtionally, you will need following packages:
* [numpy](http://www.numpy.org)
* [Pandas](http://pandas.pydata.org)
* [Matplotlib](https://matplotlib.org)

# Data Source Information and Usage

This project will use datasets from [Yelp Dataset Challenge](https://www.yelp.com/dataset/challenge). The datasets are available in both JSON and SQL files. (See the documentation from here). I will mainly use **business** dataset in JSON format for my project:

* Businesss.json

The business dataset contains business data including location data, attributes, and categories.

For categories,

// an array of strings of business categories

    "categories": [

        "Mexican",

        "Burgers",

        "Gastropubs"

    ],

which has a variety of tags. It’s impossible to get all restaurants in the data by simply searching “restaurant” for category. Thus, I will need to do some explorations to the category in business data and figure out the set of applicable categories to my research.

# License 
Yelp provides a [guideline](https://s3-media2.fl.yelpcdn.com/assets/srv0/engineering_pages/e926cc12796d/assets/vendor/yelp-dataset-license.pdf) regarding the dataset license.


This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/HWNi/data512-final-project/blob/master/LICENSE) file for details