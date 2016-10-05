[![Build Status](https://travis-ci.org/NLeSC/mcfly.svg?branch=master)](https://travis-ci.org/NLeSC/mcfly)
[![Code quality](https://scrutinizer-ci.com/g/NLeSC/mcfly/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/NLeSC/mcfly/)
[![Coverage](https://scrutinizer-ci.com/g/NLeSC/mcfly/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/NLeSC/mcfly/statistics/)
<a href="https://zenhub.io"><img src="https://raw.githubusercontent.com/ZenHubIO/support/master/zenhub-badge.png"></a>
[![Documentation Status](https://readthedocs.org/projects/mcfly/badge/?version=latest)](http://mcfly.readthedocs.io/en/latest/?badge=latest)

# mcfly

This repository is to ease using deep learning technology for time series classification. The advantages of deep learning algorithms is that it can handle raw data directly with no need to compute signal features, it does not require a expert domain knowledge about the data, and it has been shown to be competitive with conventional machine learning techniques. The notebook [Tutorial mcfly on PAMAP2](https://github.com/NLeSC/mcfly/blob/master/notebooks/Tutorial%20mcfly%20on%20PAMAP2.ipynb) shows how mcfly can be used on accelerometer time series data.

## Installation
Prerequisites:
- Python 2.7 or 3
- pip

To install the package, run in the project directory:

`pip install .`

## Visualization
To run the  model visualization, cd to the project directory and start up a python web server:

`python -m http.server 8888 &`

Navigate to `http://localhost:8888/html/plots.html` in your browser to open the visualization. For a more elaborate description of the visualization see [user manual](https://github.com/NLeSC/mcfly/wiki/User-manual).


## User documentation
* [User manual](https://github.com/NLeSC/mcfly/wiki/User-manual)
* [Code documentation](http://mcfly.readthedocs.io/en/latest/)
* [Technical Documentation](https://github.com/NLeSC/mcfly/wiki/Technical-documentation)
* [Information on Data preprocessing](https://github.com/NLeSC/mcfly/wiki/Data-preprocessing)

## Contributing
You are welcome to contribute to the code via pull requests. Please have a look at the [NLeSC guide](https://nlesc.gitbooks.io/guide/content/software/software_overview.html) for guidelines about software development.

We use numpy-style docstrings for code documentation.

## Licensing
Source code and data of mcfly are licensed under the Apache License, version 2.0.
