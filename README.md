# ippull

[![UNLICENSE licensed][license-badge]][license-url]

[license-badge]: https://img.shields.io/badge/license-UNLICENSE-blue.svg
[license-url]: ./UNLICENSE

[ippull.py](ippull.py) is a Python script to get one's public ip address by contacting an [ippush](https://github.com/shtsoft/ippush) service.

### Installation

To install ippull, first clone the repo.
Then set up an environment by running the following commands in the context of the repo top-level:

```console
user@host:~$ python -m venv venv
user@host:~$ source venv/bin/activate.fish
user@host:~$ python -m pip install --upgrade pip
user@host:~$ python -m pip install -r requirements.txt
user@host:~$ deactivate
```

### Usage

To get one's ip address from `1.2.3.4` run the following commands in a properly set up and activated environment:

```console
user@host:~$ python ippull.py 1.2.3.4
```

### Upgrade

To upgrade the installation of ippull, just remove `./venv`; then pull and reinstall.
