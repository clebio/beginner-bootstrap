# Beginner Bootstrap

Resources for beginning Python programmers (or anyone interested).

## Setup

    mkvirtualenv bootstrap
    pip install -r requirements.txt

[Virtualenv][venv] is a way to encapsulate the dependencies for a Python project. The `mkvirtualenv` command is part of [virtualenvwrapper][venvwrapper], which adds helper utilities to `virtualenv`.

Your computer may have python 2.x installed, in addition to python 3. In that case, you might need to specify which python interpreter you want to use:

    mkvirtualenv -p `which python3` bootstrap

It can also be useful to upgrade pip (and setuptools):

    pip install -U pip setuptools

## Usage

    ipython notebook # (opens web browser)

[venvwrapper]: http://virtualenvwrapper.readthedocs.org/en/latest/command_ref.html
[venv]: http://docs.python-guide.org/en/latest/dev/virtualenvs/
