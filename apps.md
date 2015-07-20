---
layout: index
---
[Overview](http://bioasp.github.io/index.html) | [Applications](http://bioasp.github.io/apps.html) | [Answer Set Programming](http://bioasp.github.io/index.html) | [Who we are](http://bioasp.github.io/index.html)

# Applications
The BioASP software collection includes the following applications. For more details on each application, please visit the corresponding <em>Application Page</em>. BioASP applications are freely available as python packages under General Public License (GPL) and they can be easily installed on your system. However you may want to try their <em>Web Service</em> before doing so (example input data is provided in-place).

***

## Reasoning on metabolic network models

###[**_meneco_** - Metabolic network completion](http://bioasp.github.io/meneco)
This application can be used to check if a draft metabolic network provides the synthesis routes to comply with certain functionality. If this fails, **_meneco_** can automatically complete the network using reactions from a reference network stemming from other organisms until the observed functionality is provided.

[Application Page](http://bioasp.github.io/meneco) | <a href="http://mobyle.genouest.org/cgi-bin/Mobyle/portal.py#forms::meneco" target="_blank">Web Service</a> | [Citation](http://dx.doi.org/10.1007/978-3-642-40564-8_25)

***
###[**_precursor_** - Compute minimal metabolic precursors](http://bioasp.github.io/precursor)
Given a metabolic reaction network and a set of target metabolites, this application computes the subset minimal sets of precursor metabolites needed to produce the targets.

[Application Page](http://bioasp.github.io/precursor) | <a href="http://mobyle.genouest.org/cgi-bin/Mobyle/portal.py#forms::precursor" target="_blank">Web Service</a>

***

## Reasoning on Boolean models

###[**_caspo_** - Reasoning on the response of logical signaling networks](http://bioasp.github.io/caspo)
The aim of this application is to implement a pipeline for automated reasoning on logical signaling networks. Features provided by **_caspo_** include, learning of logical networks from experiments, design new experiments in order to reduce the uncertainty, and finding intervention strategies to control the biological system.

[Application Page](http://bioasp.github.io/caspo) | <a href="http://mobyle.genouest.org/cgi-bin/Mobyle/portal.py#forms::caspo-learn" target="_blank">Web Service</a> | [Citation](http://dx.doi.org/10.1093/bioinformatics/btt393)

***

##Reasoning on influence graph models

###[**_ingranalyze_** - Sign consistency on influence graphs](http://bioasp.github.io/ingranalyze)
This application confronts biological networks given as interaction graphs with
experimental data given as signs that represent the concentration changes between two measurements.
It allows to decover inconsistencies in data or network, proposes minimal repairs and
 predicts the behavior of unmeasured species.

[Application Page](http://bioasp.github.io/ingranalyze) | <a href="http://mobyle.genouest.org/cgi-bin/Mobyle/portal.py#forms::ingranalyze" target="_blank">Web Service</a> | [Citation](http://dx.doi.org/10.1007/978-3-540-89982-2_19)


#### Other projects using ingranalyze
[CytoASP](http://dx.doi.org/10.1186/s12918-015-0179-6) is a [Cytoscape](http://www.cytoscape.org/) plugin that enables consistency checking, prediction and repair of network models while providing customizable visualizations in Cytoscape.
[Citation](http://dx.doi.org/10.1186/s12918-015-0179-6) | 
[Sources](https://bitbucket.org/akittas/cytoasp)
***

###[**_iggy_** - Consistency based analysis of influence graphs and observed systems behaviors](http://bioasp.github.io/iggy)
This application is a further development of ingranalyze it supports the incorporation of uncertain data and
 discovers inconsistencies in data or network, applies minimal repairs and predicts the behavior of unmeasured species. In particular, it distinguishes strong predictions (e.g. increase of a node level) and
weak predictions (e.g., node level increases or remains unchanged) enlarging the overall predictive power of the approach. Also included is a the tool opt_graph which computes networks which have an optimal fitness regarding the data of not only a single experiment but a set of experiments.

[Application Page](http://bioasp.github.io/iggy) 

***


## Reasoning on integrated metabolic gene regulation models

###[**_shogen_** - Identification of functional gene units](http://bioasp.github.io/shogen)
This application combines gene sequence information and metabolic reaction network into one model.
Together with data about metabolites involved in a chemical pathway,
 the Shortest Gene Segments (SGS) are proposed which activate the metabolic reactions of such a pathway.

[Application Page](http://bioasp.github.io/shogen) | <a href="http://mobyle.genouest.org/cgi-bin/Mobyle/portal.py#forms::shogen" target="_blank">Web Service</a> | [Citation](http://dx.doi.org/10.1007/978-3-642-40564-8_21)

***


