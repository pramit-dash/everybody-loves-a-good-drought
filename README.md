# everybody-loves-a-good-drought

## Background
The project's name is inspired by the award-winning [book by the same name](https://en.wikipedia.org/wiki/Everybody_Loves_a_Good_Drought) by P. Sainath, which essays life in some of the poorest districts of India. The essays point to an uncomfortable truth -the price of development in India. Based on his observations, Sainath argues that the poorest sections of the Indian society -the tribals, the rural impoverished, the urban destitutes, the backwards classes and castes are most adversely affected by "development" projects of any kind. This is even more prevelant in the most mineral-rich areas of the country. 

It is expected that with climate change and other natural and man-made disasters in the process of unravelling, these issues will be exacerbated in the coming decades, if note years. Within the scope of this project, we intend to bring in data from different types of sources and kinds to visualise data, and infer correlations. We also review potential of renewable energy in the form of solar and wind to alleviate these problems. The following data sources are expected to be of use:
* [Demographic Health Survey](https://api.dhsprogram.com/#/index.html)
* [World population data](https://www.worldpop.org/datacatalog/)
* [Historical and current meterorological data](https://open-meteo.com/en/docs)
* [Natural disasters data](https://www.wunderground.com/weather/in/koraput)
* [World distribution of natural resources]()
* [Solar energy potential](https://openweathermap.org/api/solar-radiation)


## Implementation
The project will be setting up a RESTful API application using FastAPI framework. It is planned to be designed with the following stack:
* Python - v3.9+
* Dependency management - pip/[requirements](requirements.txt), Poetry/[pyproject.toml](pyproject.toml)
* CI/CD - using GitHub actions & Google Cloud Build
* Cloud Deployment (on GCP):
    * Cloud Environment: Google Cloud Run
    * Secrets: Google Secret Manager
    * Persistent Storage: Google BigQuery & Google Cloud Storage
    * Logging: Google Cloud Logger
* Testing: PyTest
