# SABS-R3 Student Software

A collection of software written and contributed to by SABS-R3 students.

If you want to contribute, please read [this](CONTRIBUTING.md).

## Table of contents

<!-- toc -->

- [SABS-R3 Software Projects](#sabs-r3-software-projects)
- [Libraries](#libraries)
- [Applications](#applications)
- [Demos / Tutorials](#demostutorials)
- [Publications](#publications)
- [Other](#other)

<!-- tocstop -->

## SABS-R3 Software Projects

## Libraries

* [PINTS](https://github.com/pints-team/pints) — a framework for optimisation and Bayesian inference on ODE models of noisy time-series, such as arise in electrochemistry and cardiac electrophysiology. 
  - ![](https://img.shields.io/badge/Language-Python-blue) ![](https://img.shields.io/badge/Topic-Bayesian%20Inference-blue) ![](https://img.shields.io/badge/Topic-Time%20Series%Modelling-green)
  - [![](https://img.shields.io/badge/Paper-10.5334/jors.252-blueviolet)](http://doi.org/10.5334/jors.252)
    [![](https://img.shields.io/badge/Citing%20Papers%20-blueviolet)](https://github.com/pints-team/pints/tree/master/papers)
  - [<img src="https://github.com/DavAug.png" alt="David Augustin" title="David Augustin" width="48"/>](https://github.com/DavAug)
    [<img src="https://github.com/simonmarchant.png" alt="Simon Marchant" title="Simon Marchant" width="48"/>](https://github.com/simonmarchant)
  - [![Unit tests on multiple python versions](https://github.com/pints-team/pints/actions/workflows/unit-test-python-coverage.yml/badge.svg)](https://github.com/pints-team/pints/actions) 
    [![Unit tests on multiple operating systems](https://github.com/pints-team/pints/actions/workflows/unit-test-os-coverage.yml/badge.svg)](https://github.com/pints-team/pints/actions)
    [![codecov](https://codecov.io/gh/pints-team/pints/branch/master/graph/badge.svg)](https://codecov.io/gh/pints-team/pints)
    [![Functional testing code](https://raw.githubusercontent.com/pints-team/functional-testing/master/badge-code.svg)](https://github.com/pints-team/functional-testing)
    [![Functional testing results](https://raw.githubusercontent.com/pints-team/functional-testing/master/badge-results.svg)](https://www.cs.ox.ac.uk/projects/PINTS/functional-testing)
    [![binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/pints-team/pints/master?filepath=examples)
    [![readthedocs](https://readthedocs.org/projects/pints/badge/?version=latest)](http://pints.readthedocs.io/en/latest/?badge=latest)

* [<img src="https://github.com/DavAug/chi/blob/main/docs/source/_static/logo_social_media.png" alt="Chi" title="Chi" height="48"/>](https://github.com/DavAug/chi) — Chi is a framework for pharmacokinetic and pharmacodynamic (PKPD) modelling, including simulation of treatment responses and the inference of model parameters from population data.
  - [![](https://img.shields.io/badge/Documentation-Overview-blue)](https://chi.readthedocs.io/en/latest/getting_started/quick_overview.html) [![](https://img.shields.io/badge/Documentation-API-blue)](https://chi.readthedocs.io/en/latest/?badge=latest) [![](https://img.shields.io/badge/Documentation-Getting%20started-blue)](https://chi.readthedocs.io/en/latest/getting_started/index.html)
  - ![](https://img.shields.io/badge/Language-Python-blue) ![](https://img.shields.io/badge/Topic-PKPD%20modelling-blue) ![](https://img.shields.io/badge/Topic-Bayesian%20Inference-blue) 
  - [![](https://img.shields.io/badge/Paper-bioRxiv/filter%20inference-blueviolet)](https://doi.org/10.1101/2022.11.01.514702) [![](https://img.shields.io/badge/Paper-bioRxiv/treatment%20response%20prediction-blueviolet)](https://doi.org/10.1101/2022.03.19.483454)
  - [<img src="https://github.com/DavAug.png" alt="David Augustin" title="David Augustin" width="48"/>](https://github.com/DavAug)
  - [![Unit tests on multiple python versions](https://github.com/DavAug/chi/workflows/Unit%20tests%20(python%20versions)/badge.svg)](https://github.com/DavAug/chi/actions) [![Unit tests on multiple operating systems](https://github.com/DavAug/chi/workflows/Unit%20tests%20(OS%20versions)/badge.svg)](https://github.com/DavAug/chi/actions) [![codecov](https://codecov.io/gh/DavAug/chi/branch/main/graph/badge.svg)](https://codecov.io/gh/DavAug/chi) [![Documentation Status](https://readthedocs.org/projects/chi/badge/?version=latest)](https://chi.readthedocs.io/en/latest/?badge=latest)
  
* [ImmuneBuilder](https://github.com/brennanaba/ImmuneBuilder) — A set of deep learning models to predict the structure of antibodies, nanobodies and TCRs. 
  - ![](https://img.shields.io/badge/Language-Python-blue) ![](https://img.shields.io/badge/Topic-Structure%20Prediction-blue) 
  - [![](https://img.shields.io/badge/Paper-bioRxiv/ImmuneBuilder-blueviolet)](https://www.biorxiv.org/content/10.1101/2022.11.04.514231v2)
  - [<img src="https://github.com/brennanaba.png" alt="Brennan Abanades" title="Brennan Abanades" width="48"/>](https://github.com/brennanaba)
  - [![PyPI - Downloads](https://img.shields.io/pypi/dm/immunebuilder?color=gree)](https://pypistats.org/packages/immunebuilder)
  
* [ABlooper](https://github.com/brennanaba/ABlooper) — Tool for modelling the CDR loops in antibodies. 
  - ![](https://img.shields.io/badge/Language-Python-blue) ![](https://img.shields.io/badge/Topic-Structure%20Prediction-blue) 
  - [![](https://img.shields.io/badge/Paper-Bioinformatics/ABlooper-blueviolet)](https://academic.oup.com/bioinformatics/article/38/7/1877/6517780)
  - [<img src="https://github.com/brennanaba.png" alt="Brennan Abanades" title="Brennan Abanades" width="48"/>](https://github.com/brennanaba)
  - [![PyPI - Downloads](https://img.shields.io/pypi/dm/ablooper?color=gree)](https://pypistats.org/packages/ablooper)

* [branchpro](https://github.com/SABS-R3-Epidemiology/branchpro) — Tool for modelling branching processes to estimate the time-dependent reproduction number of a disease with imported cases.  
  - ![](https://img.shields.io/badge/Language-Python-blue) ![](https://img.shields.io/badge/Topic-Epidemiological%20Modelling-blue)![](https://img.shields.io/badge/Topic-Bayesian%20Inference-blue) 
  - [![](https://img.shields.io/badge/Paper-Phil%20Trans%20A/local&imported%20branchpro-blueviolet)](https://royalsocietypublishing.org/doi/10.1098/rsta.2021.0308)
  - [<img src="https://github.com/I-Bouros.png" alt="Ioana Bouros" title="Ioana Bouros" width="48"/>](https://github.com/I-Bouros)
    [<img src="https://github.com/rccreswell.png" alt="Richard Creswell" title="Richard Creswell" width="48"/>](https://github.com/rccreswell)
    [<img src="https://github.com/DavAug.png" alt="David Augustin" title="David Augustin" width="48"/>](https://github.com/DavAug)
    [<img src="https://github.com/ao20.png" alt="Andrew Ó Heachteirn" title="Andrew Ó Heachteirn" width="48"/>](https://github.com/ao20)
    [<img src="https://github.com/FarmHJ.png" alt="Hui Jia Farm" title="Hui Jia Farm" width="48"/>](https://github.com/FarmHJ)
    [<img src="https://github.com/siting-miao.png" alt="Siting Miao" title="Siting Miao" width="48"/>](https://github.com/siting-miao)
  - [![Run Unit Tests on multiple OS](https://github.com/SABS-R3-Epidemiology/branchpro/actions/workflows/os-unittests.yml/badge.svg)](https://github.com/SABS-R3-Epidemiology/branchpro/actions/workflows/os-unittests.yml)
  [![Run Unit Tests on multiple python versions](https://github.com/SABS-R3-Epidemiology/branchpro/actions/workflows/python-version-unittests.yml/badge.svg)](https://github.com/SABS-R3-Epidemiology/branchpro/actions/workflows/python-version-unittests.yml)
  [![Documentation Status](https://readthedocs.org/projects/branchpro/badge/?version=latest)](https://branchpro.readthedocs.io/en/latest/?badge=latest)
  [![codecov](https://codecov.io/gh/SABS-R3-Epidemiology/branchpro/branch/main/graph/badge.svg?token=UBJG0AICF9)](https://codecov.io/gh/SABS-R3-Epidemiology/branchpro/)

* [seirmo](https://github.com/brennanaba/ABlooper) — Tool for modelling the outbreak of an infectious disease with the SEIR model.
  - ![](https://img.shields.io/badge/Language-Python-blue) ![](https://img.shields.io/badge/Topic-Epidemiological%20Modelling-blue) 
  - [<img src="https://github.com/FarmHJ.png" alt="Hui Jia Farm" title="Hui Jia Farm" width="48"/>](https://github.com/FarmHJ)
    [<img src="https://github.com/siting-miao.png" alt="Siting Miao" title="Siting Miao" width="48"/>](https://github.com/siting-miao)
    [<img src="https://github.com/DavAug.png" alt="David Augustin" title="David Augustin" width="48"/>](https://github.com/DavAug)
    [<img src="https://github.com/KCGallagher.png" alt="Kit Gallagher" title="Kit Gallagher" width="48"/>](https://github.com/KCGallagher)
    [<img src="https://github.com/NicholasFan235.png" alt="Nicholas Fan" title="Nicholas Fan" width="48"/>](https://github.com/NicholasFan235)
    [<img src="https://github.com/patricia-lamy.png" alt="Patricia Lamirande" title="Patricia Lamirande" width="48"/>](https://github.com/patricia-lamy)
    [<img src="https://github.com/rccreswell.png" alt="Richard Creswell" title="Richard Creswell" width="48"/>](https://github.com/rccreswell)
    [<img src="https://github.com/Elizabeth-Hayman.png" alt="Elizabeth Hayman" title="Elizabeth Hayman" width="48"/>](https://github.com/Elizabeth-Hayman)
    [<img src="https://github.com/I-Bouros.png" alt="Ioana Bouros" title="Ioana Bouros" width="48"/>](https://github.com/I-Bouros)
    [<img src="https://github.com/lukedtc.png" alt="Luke Heirene" title="Luke Heirene" width="48"/>](https://github.com/lukedtc)
  - ![Unit tests (python versions)](https://github.com/SABS-R3-Epidemiology/seirmo/workflows/Unit%20tests%20(python%20versions)/badge.svg)
  ![Unit tests (OS versions)](https://github.com/SABS-R3-Epidemiology/seirmo/workflows/Unit%20tests%20(OS%20versions)/badge.svg)
  [![codecov](https://codecov.io/gh/SABS-R3-Epidemiology/seirmo/branch/main/graph/badge.svg?token=D1P3CMQTDP)](https://codecov.io/gh/SABS-R3-Epidemiology/seirmo)
  [![Documentation Status](https://readthedocs.org/projects/seirmo/badge/?version=latest)](https://seirmo.readthedocs.io/en/latest/?badge=latest)

## Applications

## Demos / Tutorials

## Publications

* [Filter inference](https://github.com/DavAug/filter-inference) — A scalable nonlinear mixed effects inference approach for snapshot time series data. 
  - [![](https://img.shields.io/badge/Paper-bioRxiv/filter%20inference-blueviolet)](https://doi.org/10.1101/2022.11.01.514702)
  - [<img src="https://github.com/DavAug.png" alt="David Augustin" title="David Augustin" width="48"/>](https://github.com/DavAug) [<img src="https://github.com/ben18785.png" alt="Ben Lambert" title="Ben Lambert" width="48"/>](https://github.com/ben18785) [<img src="https://loop.frontiersin.org/images/profile/503334/203" alt="Ken Wang" title="Ken Wang" width="48"/>](https://loop.frontiersin.org/people/503334/overview) [<img src="https://loop.frontiersin.org/images/profile/1050700/203" alt="Antje Walz" title="Antje Walz" width="48"/>](https://loop.frontiersin.org/people/1050700/publications) [<img src="https://github.com/martinjrobins.png" alt="Martin Robinson" title="Martin Robinson" width="48"/>](https://www.cs.ox.ac.uk/files/8475//PTAIT_20160511_2470.jpg) [<img src="https://www.new.ox.ac.uk/sites/default/files/styles/large_navigation/public/2017-11/David%20Gavagh_0.jpg?itok=twkbQKQf" alt="David Gavaghan" title="David Gavaghan" height="48"/>](https://www.cs.ox.ac.uk/people/david.gavaghan/)

## Other
