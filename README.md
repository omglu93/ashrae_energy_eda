# Great Energy Predictor - EDA

This notebook contains an exploratory data analysis of the Great Energy Predictor competition held by ASHRAE. It aimed to do a deep dive into the dataset provided, find possible correlations, mistakes and lay the groundwork for a machine learning model.

The complete notebook can be accessed [here](https://nbviewer.jupyter.org/github/omglu93/ashrae_energy_eda/blob/master/the-great-energy-predicator-eda.ipynb).

![img](/images/img1.jpg)

Retrospectively, the dataset contained almost every mistake imaginable for a building energy dataset (from energy usage on buildings that weren't even constructed at the time to kVa units given as kWa). The team in ASHRAE provided an amazing dataset with a real-world feel to it that helped create some very robust machine learning models. 

The end goal of the whole competition was to create a machine learning model that is capable of asking a what-if question. To simplify with an example, imagine investing a large sum of money into a refurbishment of a building to improve its energy efficiency, sustainability, etc. However, looking at the energy bill after the remodelling shows no clear improvement to the reduction of costs compared to the same month last year. Situations like these can be very discouraging to clients and hinder the possibility of future investments in green projects. At that moment, we input the parameters into the machine learning model (temperature, wind speed, direction, humility, etc.) and the algorithm displays to us how much the building would have consumed without the improvements. This allows for a clear comparison between the two costs
  


# Dataset

The data is provided by ASHRAE

# Requirements
- Python 2.7 or Python 3.6
- Jupyter Notebook

# License
MIT. See the LICENSE file for the copyright notice.

# References
https://www.energy.gov/sites/prod/files/2016/09/f33/Building%20Data%20Analysis-09222016-Final.pdf
https://www.dropbox.com/sh/yk9rvcef7fikv01/AADPt09uCWXc9VM0CFUaIsrNa?dl=0&preview=R-ESL-PA-94-06-01.pdf
https://www.dropbox.com/sh/yk9rvcef7fikv01/AADPt09uCWXc9VM0CFUaIsrNa?dl=0&preview=R-ESL-PA-96-07-03-1.pdf
