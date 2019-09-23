---
RoroChip-Cookies: Python Application Project Template
---

[![Travis CI build status](https://travis-ci.org/mdklatt/cookiecutter-python-app.png)](%60travis%60_)

This is a [Cookiecutter](http://cookiecutter.readthedocs.org) template
for creating a Python application project.

The project layout is based on the [Python Packaging User
Guide](https://packaging.python.org/en/latest/distributing.html#configuring-your-project).
The current conventional wisdom forgoes the use of a source directory,
but moving the package out of the project root provides several
advantages (*cf.* [Packaging a Python
library](http://blog.ionelmc.ro/2014/05/25/python-packaging)).

Project Features
================

-   Python 3.5+
-   [MIT License](http://choosealicense.com/licenses/mit)
-   [pytest](http://pytest.org) test suite
-   [Sphinx](http://sphinx-doc.org) documentation

Application Features
====================

-   CLI with subcommands with Click
-   Logging
-   Hierarchical [YAML](http://pyyaml.org/wiki/PyYAML) configuration
-   PBR

Usage
=====

Install Python requirements for using the template:

``` {.sourceCode .console}
$ python -m pip install --user --requirement=requirements.txt
```

Create a new project directly from the template on
[GitHub](https://github.com/roaet/rorochip-cookies):

``` {.sourceCode .console}
$ cookiecutter gh:roaet/rorochip-cookies
```
