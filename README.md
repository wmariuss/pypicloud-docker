# pypi

Deploy `PyPi` server for hosting Python libs/packages.

## Requirements

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
