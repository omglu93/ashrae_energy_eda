# Great Energy Predictor - EDA

This notebook contains an exploratory data analysis of the Great Energy Predictor competition held by ASHRAE. It aimed to do a deep dive into the dataset provided, find possible correlations, mistakes and lay the groundwork for a machine learning model.

Retrospectively, the dataset contained almost every mistake imaginable for a building energy dataset (from energy usage on buildings that weren't even constructed at the time to kVa units given as kWa). The team in ASHRAE provided an amazing dataset with a real-world feel to it that helped create some very robust machine learning models. 

The end goal of the whole competition was to create a machine learning model that is capable of asking a what-if question. To simplify with an example, imagine investing a large sum of money into a refurbishment of a building to improve its energy efficiency, sustainability, etc. However, looking at the energy bill after the remodelling shows no clear improvement to the reduction of costs compared to the same month last year. Situations like these can be very discouraging to clients and hinder the possibility of future investments in green projects. At that moment, we input the parameters into the machine learning model (temperature, wind speed, direction, humility, etc.) and the algorithm displays to us how much the building would have consumed without the improvements. This allows for a clear comparison between the two costs
  

The complete notebook can be accessed [here](https://nbviewer.jupyter.org/github/omglu93/energy_consumption_eda_prediction/blob/master/energy-consumption-eda-prediction.ipynb).

![los](/images/img1.jpg)


# Dataset

The data is provided by ASHRAE

- 2 features/columns
- 145,000 rows of data


# Requirements
- Python 2.7 or Python 3.6
- Jupyter Notebook

# License
MIT. See the LICENSE file for the copyright notice.

# References:

1. https://arxiv.org/pdf/1603.02754v1.pdf
2. https://en.wikipedia.org/wiki/Regional_transmission_organization_(North_America)
3. https://www.pjm.com/about-pjm.aspx
