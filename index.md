---
layout: index
---

[Overview](#overview) | [Applications](http://bioasp.github.io/apps.html) | [Installation](#installation) | [Answer Set Programming](#answer-set-programming) | [Who we are](#who-we-are)

# Overview
BioASP is a meta-package to create an powerful environment of Answer Set Programming for Systems Biology. The BioASP applications implement methods for analyzing metabolic, signaling and gene regulatory networks, consistency checking, diagnosis, and repair of biological data and models. They allow for computing predictions and generating hypotheses about required extensions of biological models, as well as designing new experiments and finding intervention strategies to control the biological system at hand.
<a href="https://plus.google.com/106623620514531759221" rel="publisher">Google+</a>

# Applications
The BioASP software collection includes the following applications. For more details on each application, please visit the corresponding <em>Application Page</em>. BioASP applications are freely available as python packages under General Public License (GPL) and they can be easily installed on your system. However you may want to try their <em>Web Service</em> before doing so (example input data is provided in-place).

***

### Metabolic network completion: **_meneco_**
This application can be used to check if a draft metabolic network provides the synthesis routes to comply with certain functionality. If this fails, **_meneco_** can automatically complete the network using reactions from a reference network stemming from other organisms until the observed functionality is provided.

[Application Page](http://bioasp.github.io/meneco) | <a href="http://mobyle.genouest.org/cgi-bin/Mobyle/portal.py#forms::meneco" target="_blank">Web Service</a> | [Citation](http://dx.doi.org/10.1007/978-3-642-40564-8_25)

***

### Reasoning on the response of logical signaling networks: **_caspo_**
The aim of this application is to implement a pipeline for automated reasoning on logical signaling networks. Features provided by **_caspo_** include, learning of logical networks from experiments, design new experiments in order to reduce the uncertainty, and finding intervention strategies to control the biological system.

[Application Page](http://bioasp.github.io/caspo) | <a href="http://mobyle.genouest.org/cgi-bin/Mobyle/portal.py#forms::caspo-learn" target="_blank">Web Service</a> | [Citation](http://dx.doi.org/10.1093/bioinformatics/btt393)

***

### Sign consistency on influence graphs: **_ingranalyze_**
This application confronts biological networks given as Interaction Graphs with
experimental data given as signs that represent the concentration changes between two measurements.
It allows to decover inconsistencies in data or network, proposes minimal repairs and
 predicts the behavior of unmeasured species.

[Application Page](http://bioasp.github.io/ingranalyze) | <a href="http://mobyle.genouest.org/cgi-bin/Mobyle/portal.py#forms::ingranalyze" target="_blank">Web Service</a> | [Citation](http://dx.doi.org/10.1007/978-3-540-89982-2_19)

***

### Identification of functional gene units: **_shogen_**
This application combines gene sequence information and metabolic reaction network into one model.
Together with data about metabolites involved in a chemical pathway,
 the Shortest Gene Segments (SGS) are proposed which activate the metabolic reactions of such a pathway.

[Application Page](http://bioasp.github.io/shogen) | <a href="http://mobyle.genouest.org/cgi-bin/Mobyle/portal.py#forms::shogen" target="_blank">Web Service</a> | [Citation](http://dx.doi.org/10.1007/978-3-642-40564-8_21)

***

### Compute minimal metabolic precursors: **_precursor_**
Given a metabolic reaction network and a set of target metabolites, this application computes the subset minimal sets of precursor metabolites needed to produce the targets.

[Application Page](http://bioasp.github.io/precursor) | <a href="http://mobyle.genouest.org/cgi-bin/Mobyle/portal.py#forms::precursor" target="_blank">Web Service</a>

***

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


