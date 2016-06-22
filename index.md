---
layout: index
---

[Overview](#overview) \| [Applications](http://bioasp.github.io/apps.html) \| [Answer Set Programming](#answer-set-programming) \| [Who we are](#who-we-are)

# Overview
BioASP is a collection of open-source programs, providing solutions for analyzing biological data and models with Answer Set Programming (ASP). ASP has proven to be an excellent tool for solving a variety of biological questions. The BioASP applications implement methods for analyzing metabolic, signaling and gene regulatory networks, consistency checking, diagnosis, and repair of biological data and models. In particular, it allows for computing predictions and generating hypotheses about required extensions of biological models, as well as designing new experiments and finding intervention strategies to control the biological system at hand.

BioASP is powered by the ASP tools of [Potassco, the Potsdam Answer Set Solving Collection](http://potassco.sourceforge.net/) and [PyASP](sthiele.github.io/pyasp) library which makes this power easily available.
The functionalities provided by the BioASP applications exploit technical know-how of modeling (biological) problems in ASP and gearing ASP solvers’ parameters to them.
BioASP applications integrate our practical experience and offers them via easy-to-use Python functions, thus enabling ASP non-experts to solve biological questions with ASP.

<a href="https://plus.google.com/106623620514531759221" rel="publisher">Google+</a>


# [Applications](http://bioasp.github.io/apps.html) 

# Installation
You can install all BioASP application at once from [pypi](http://pypi.python.org/pypi/bioasp) by running:
```
$ pip install bioasp
```
For details on how to use each application follow the corresponding links above. If you do not have **pip** installed on your system, you only need to download [get-pip.py](https://raw.github.com/pypa/pip/master/contrib/get-pip.py). Then run the following:
```
$ python get-pip.py
```
Alternatively, if you prefer not to install **pip**, you can download the sources of BioASP and after unpacking run:
```
$ python setup.py install
```
Note that you may need either administrator access or a [virtual environment](http://www.virtualenv.org).

# Answer Set Programming
BioASP applications strongly rely on Answer Set Programming (ASP) for knowledge representation and reasoning. ASP is a declarative problem solving paradigm from the field of Logic Programming combining several computer science areas such as Knowledge Representation and Reasoning, Artificial Intelligence, Constraint Satisfaction and Combinatorial Optimization.

For more details on ASP and state-of-the-art available tools, you may want to check the website of [Potassco, the Potsdam Answer Set Solving Collection](http://potassco.sourceforge.net).

# Who we are
BioASP is developed by several people at several institutions from several countries:

* [DyLISS, CNRS & Inria (Rennes, France)](http://www.irisa.fr/dyliss/)
* [Potassco, Potsdam University (Potsdam, Germany)](http://potassco.sourceforge.net)
* [MeForBio, IRCCyN & CNRS (Nantes, France)](http://www.irccyn.ec-nantes.fr/spip.php?rubrique97&lang=en)
* [ARB, Max Planck Institute (Magdeburg, Germany)](http://www.mpi-magdeburg.mpg.de/arb)
* [Systems Biomedicine, EMBL-EBI (Hinxton, UK)](http://www.ebi.ac.uk/research/saez-rodriguez)

If you would like to contribute in any way, your are welcome to join us at http://github.com/bioasp.


