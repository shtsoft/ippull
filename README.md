# ippull

This repo contains a python script to get one's public ip address by contacting an [ippush](https://github.com/shtsoft/ippush) service.

# Set Up Environment

To set up an environment run the following commands in the context of the repo top-level:

```console
user@host:~$ python -m venv venv
user@host:~$ source venv/bin/activate.fish
user@host:~$ python -m pip install --upgrade pip
user@host:~$ python -m pip install -r requirements.txt
user@host:~$ deactivate
```

# Get IP Address

To get one's ip address from `1.2.3.4` run the following commands in a properly set up environment:

```console
user@host:~$ source venv/bin/activate.fish
user@host:~$ python -m pip install --upgrade pip
user@host:~$ python -m pip install --upgrade -r requirements.txt
user@host:~$ python ippull.py 1.2.3.4
user@host:~$ deactivate
```
