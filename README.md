# Cookiecutter UIUCTHESIS template

A simple template to create your thesis using [UIUCTHESIS2014 latex template](https://github.com/mayhewsw/uiucthesis2014) 

### Requirements to use the cookiecutter template:
-----------

 - Python 2.7 or 3.5
 - **Make** and **TexLive** package on linux as this cookiecutter uses a [post_gen_project.sh](https://cookiecutter.readthedocs.io/en/latest/advanced/hooks.html) for running the latex command via a Makefile. 
 - [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0: This can be installed with pip by or conda depending on how you manage your Python packages:

``` bash
$ pip install cookiecutter
```

or

``` bash
$ conda config --add channels conda-forge
$ conda install cookiecutter
```

### The resulting directory structure
------------

The directory structure of your new project looks like this: 

```
.
|-- chapters                    <- keep all the chapter wise tex files here
|-- figures                     <- keep all the figures here. It is suggested to use 1 folder per chapter
|-- Makefile                    <- Makefile used for generating latex output
|-- README.md                   <- Update this README with information about your thesis
|-- README-thesis-template.md   <- README.md from the uiucthesis2014 project
|-- tables                      <- keep all the tables in a seperate tex file here. It is suggested to use 1 folder per chapter
|-- thesisbib.bib               <- Store all the bibtex entries here
|-- thesis-ex.tex
|-- uiucthesis2014.cls
|-- uiucthesis2014.dtx
|-- uiucthesis2014.ins
|-- uiucthesis2014.log
`-- uiucthesis2014.sty
```
