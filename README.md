# Paradise MHP Analysis

For my Stanford Journalism master's thesis, I explored the status of the mobile home park rebuilds in Paradise, California, in the aftermath of the 2018 Camp Fire. To identify how important prevalent mobile home parks were in Paradise, I compared the town's number of mobile home park lots to other towns in California that had a similar population density pre-fire. 

I used three different data sources to answer this question:

* List of mobile home parks permitted by the California Housing and Community Development Department. [Source.](https://casas.hcd.ca.gov/casas/cmirMp/onlineQuery)
* ACS 2018 5-year population estimates by place in California. I accessed this data using a function to call from the Census API.
* California places geography. [Source.](https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.2018.html)

This project uses Python to wrangle and analyze data. The libraries that are necessary include pandas and requests.

## Setup

> Before using this project, please ensure all dependencies are installed. See the [project home page][] for details.

[project home page]: https://github.com/stanfordjournalism/cookiecutter-stanford-progj#requirements--setup

After creating this project:

* `cd paradise-mhp-analysis`
* `pipenv install`
