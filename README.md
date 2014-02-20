## BioASP

Here you can find the latest BioASP applications.

BioASP is a collection of open-source programs, providing solutions for analyzing biological data and models with Answer Set Programming (ASP). ASP has proven to be an excellent tool for solving a variety of biological questions. The BioASP applications implement methods for analyzing metabolic, signaling and gene regulatory networks, consistency checking, diagnosis, and repair of biological data and models. In particular, it allows for computing predictions and generating hypotheses about required extensions of biological models, as well as designing new experiments and finding intervention strategies to control the biological system at hand.

The BioASP collection is available as a [python package](http://pypi.python.org/pypi/bioasp) which encapsulates the ASP solutions, provides functions for reading biological data formats pre-processing the input, post-processing and presenting the results. The functionalities provided by the BioASP applications exploit technical know-how of modeling (biological) problems in ASP and gearing ASP solvers’ parameters to them. BioASP applications integrate our practical experience and offers them via easy-to-use Python functions, thus enabling ASP non-experts to solve biological questions with ASP.

BioASP is powered by the ASP tools of [Potassco, the Potsdam Answer Set Solving Collection](http://potassco.sourceforge.net/).

Don't hesitate to ask questions, report bugs, etc. at:
* [Issues](https://github.com/bioasp/bioasp.github.io/issues)
* [Google+](https://plus.google.com/106623620514531759221)

### The BioASP applications

* [Identification of functional gene units: shogen](shogen)
* [Reasoning on the response of logical signaling networks: caspo](caspo)
* [Sign consistency on influence graphs: ingranalyze](ingranalyze)
* [Metabolic network completion: meneco](meneco)

#### Installation

You can install all BioASP application at once simply by running:

```
$ pip install bioasp
```

For details on how to install each individual application follow the corresponding links above. If you do not have **pip** installed on your system, you only need to download [get-pip.py](https://raw.github.com/pypa/pip/master/contrib/get-pip.py). Then run the following:

```
$ python get-pip.py
```

Note that you may need either administrator access or a [virtual environment](http://www.virtualenv.org/). 
