# Finding Donors Project

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Python](https://img.shields.io/badge/Language-Python-blue.svg)](https://python.org/)


## Overview

CharityML is a fictitious charity organization located in the heart of Silicon Valley that was established to provide financial support for people eager to learn machine learning. After nearly 32,000 letters were sent to people in the community, CharityML determined that every donation they received came from someone that was making more than $50,000 annually. To expand their potential donor base, CharityML has decided to send letters to residents of California, but to only those most likely to donate to the charity. With nearly 15 million working Californians, CharityML has brought you on board to help build an algorithm to best identify potential donors and reduce overhead cost of sending mail. Your goal will be evaluate and optimize several different supervised learners to determine which algorithm will provide the highest donation yield while also reducing the total number of letters being sent.


## Contents

The project contains the following:

```text
.gitignore          - this will ignore vagrant and other metadata files
.flaskenv           - Environment variables to configure Flask
.gitattributes      - File to gix Windows CRLF issues
.devcontainers/     - Folder with support for VSCode Remote Containers
dot-env-example     - copy to .env to use environment variables
requirements.txt    - list if Python libraries required by your code
config.py           - configuration parameters

deploy/                    - K8s deployment files
├── deployment.yaml        - Deployment
├── postgresql.yaml        - PostgreSQL
└── service.yaml           - Service

docs/                      - Github Pages
├── doc.txt                - 
└── index.html             - AirBnB Data Analysis Blog

notebooks/                                         - Jupyter Notebooks
├── data                                           - Deployment
    ├── large_data_100MB     - Directory for large Data 
    └── small_data_100MB     - Directory for small data
        ├── archive          - Seattle Airbnb data directory
            ├── calendar.csv          
            ├── listings.csv          
            └── reviews.csv         
└── seattle-airbnb-exploration_REBEdit.ipynb      - Example Notebook

service/                   - service python package
├── __init__.py            - package initializer
├── models.py              - module with business models
├── routes.py              - module with service routes
└── common                 - common code package
    ├── error_handlers.py  - HTTP error handling code
    ├── log_handlers.py    - logging setup code
    └── status.py          - HTTP status constants

tests/              - test cases package
├── __init__.py     - package initializer
├── factories.py    - factory classes to generate test data
├── test_models.py  - test suite for business models
└── test_routes.py  - test suite for service routes
```

## License

Licensed under the Apache License. See [LICENSE](LICENSE)

