---
layout: index
---
[Overview](http://bioasp.github.io/index.html) | [Applications](http://bioasp.github.io/apps.html) | [Answer Set Programming](#answer-set-programming) | [Who we are](#who-we-are)

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
