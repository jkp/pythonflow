# Pythonflow: Dataflow programming for python. [![Build Status](https://travis-ci.org/spotify/pythonflow.svg)](https://travis-ci.org/spotify/pythonflow) [![Documentation Status](https://readthedocs.org/projects/pythonflow/badge/?version=latest)](http://pythonflow.readthedocs.io/en/latest/?badge=latest)

Pythonflow is a simple implementation of [dataflow programming](https://en.wikipedia.org/wiki/Dataflow_programming) for python. Users of [Tensorflow](https://www.tensorflow.org/) will immediately be familiar with the syntax.

At Spotify, we use Pythonflow in data preprocessing pipelines for machine learning models because

* it automatically caches computationally expensive operations,
* any part of the computational graph can be easily evaluated for debugging purposes,
* it allows us to distribute data preprocessing across multiple machines.

See the [documentation](http://pythonflow.readthedocs.io/en/latest/) for details.
