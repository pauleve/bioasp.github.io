---
layout: index
---
[Overview](https://bioasp.github.io/index.html) \| [Applications](https://bioasp.github.io/apps.html) \| [Answer Set Programming](https://bioasp.github.io/index.html) \| [Who we are](https://bioasp.github.io/index.html)

# Applications
The BioASP software collection includes the following applications. For more details on each application, please visit the corresponding <em>Application page</em>. BioASP applications are freely available as python packages under General Public License (GPL) and they can be easily installed on your system. However you may want to try their <em>Web service</em> before doing so (example input data is provided in-place).

***

## Reasoning on metabolic network models

### [**_meneco_** - Metabolic network completion](https://bioasp.github.io/meneco) ###
This application can be used to check if a draft metabolic network provides the synthesis routes to comply with certain functionality. If this fails, **_meneco_** can automatically complete the network using reactions from a reference network stemming from other organisms until the observed functionality is provided.

[Application page](https://bioasp.github.io/meneco) \| 
[Web service](http://mobyle.genouest.org/cgi-bin/Mobyle/portal.py#forms::meneco) \|  [Citation](http://dx.doi.org/10.1007/978-3-642-40564-8_25)

***

### [**_precursor_** - Compute minimal metabolic precursors](https://bioasp.github.io/precursor) ###
Given a metabolic reaction network and a set of target metabolites, this application computes the subset minimal sets of precursor metabolites needed to produce the targets.

[Application page](https://bioasp.github.io/precursor) \|
[Web service](http://mobyle.genouest.org/cgi-bin/Mobyle/portal.py#forms::precursor)

***

## Reasoning on Boolean models

### [**_caspo_** - Reasoning on the response of logical signaling networks](https://bioasp.github.io/caspo) ###
The aim of this application is to implement a pipeline for automated reasoning on logical signaling networks. Features provided by **_caspo_** include, learning of logical networks from experiments, design new experiments in order to reduce the uncertainty, and finding intervention strategies to control the biological system.

[Application page](https://bioasp.github.io/caspo) \|
[Web service](http://mobyle.genouest.org/cgi-bin/Mobyle/portal.py#forms::caspo-learn) \| [Citation](http://dx.doi.org/10.1093/bioinformatics/btt393)

### [**_caspots_** - Boolean network inference from time series data with perturbations](https://bioasp.github.io/caspots) ###
**_caspots_** (caspo time-series) provides an automatic and exhaustive inference of Boolean networks from prior-knowledge interaction graph and time series data with perturbations. It allows for minimising errors for matching time series data, and supports fully-asynchronous and (general) asynchronous semantics of locally-monotonic Boolean networks.

[Application page](https://bioasp.github.io/caspots) \|
[Citation](http://dx.doi.org/10.1016/j.biosystems.2016.07.009)

***

## Reasoning on influence graph models

### [**_ExDesi_** - Experiment planning to discriminate influence graph models](https://bioasp.github.io/exdesi) ###
Modern methods for the inference of cellular networks from experimental data
often express nondeterminism by proposing an ensemble of candidate models with
similar properties.
To further discriminate among these model candidates, and to find the biological
truth, new experiments need to be carried out.
Building upon a notion of consistency between biochemical/genetic regulations
and measurements profiles of cell activity,
ExDesi determines those experiments that discriminate most of the candidates
while minimizing the costs.
ExDesi implements experiment planning with interaction graph models and sign consistency methods 
to determine experiments which are most suitable to deliver results
that allow for a refinement of the model.

[Application page](https://bioasp.github.io/exdesi)

### [**_iggy_** - Consistency of influence graphs models and observed systems behaviors](https://bioasp.github.io/iggy) ###
This application is a further development of ingranalyze it supports the incorporation of uncertain data and
 discovers inconsistencies in data or network, applies minimal repairs and predicts the behavior of unmeasured species. In particular, it distinguishes strong predictions (e.g. increase of a node level) and
weak predictions (e.g., node level increases or remains unchanged) enlarging the overall predictive power of the approach. Also included is a the tool opt_graph which computes networks which have an optimal fitness regarding the data of not only a single experiment but a set of experiments.
#### Our latest opt_graph implementation is included in this package! ####

[Application page](https://bioasp.github.io/iggy) \|
[Citation](http://dx.doi.org/10.1186/s12859-015-0733-7)

***

### [**_ingranalyze_** - Sign consistency on influence graphs](https://bioasp.github.io/ingranalyze) ###
This application confronts biological networks given as interaction graphs with
experimental data given as signs that represent the concentration changes between two measurements.
It allows to decover inconsistencies in data or network, proposes minimal repairs and
 predicts the behavior of unmeasured species.

[Application page](https://bioasp.github.io/ingranalyze) \| 
[Web service](http://mobyle.genouest.org/cgi-bin/Mobyle/portal.py#forms::ingranalyze) \| [Citation](http://dx.doi.org/10.1007/978-3-540-89982-2_19)


#### Other projects using ingranalyze
[CytoASP](http://dx.doi.org/10.1186/s12918-015-0179-6) is a [Cytoscape](http://www.cytoscape.org/) plugin that enables consistency checking, prediction and repair of network models while providing customizable visualizations in Cytoscape.
[Citation](http://dx.doi.org/10.1186/s12918-015-0179-6) \| 
[Sources](https://bitbucket.org/akittas/cytoasp)

***

## Reasoning on integrated metabolic gene regulation models

### [**_shogen_** - Identification of functional gene units](https://bioasp.github.io/shogen) ###
This application combines gene sequence information and metabolic reaction network into one model.
Together with data about metabolites involved in a chemical pathway,
 the Shortest Gene Segments (SGS) are proposed which activate the metabolic reactions of such a pathway.

[Application page](https://bioasp.github.io/shogen) \|
[Web service](http://mobyle.genouest.org/cgi-bin/Mobyle/portal.py#forms::shogen) \| [Citation](http://dx.doi.org/10.1007/978-3-642-40564-8_21)

***


