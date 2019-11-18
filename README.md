# pypi

[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

Deploy `PyPi` server for hosting Python libs/packages.

* Deploy using `docker` and `docker-compose`
* Install and configure proxy

## Requirements

* `Ubuntu >= 18.04`
* `Python >= 3.6`

## Install

* Run `pip install invoke`
* Create `env` file (eg. [env.template](env.template))
* Run `invoke install --docker --compose`
* Run `invoke build --pypi` and `invoke run --pypi`

Optional

* Install nginx `invoke nginx --pypi`

## Authors

* [Marius Stanca](mailto:me@marius.xyz)
