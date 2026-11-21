## VEGA project

VEGA is an open-source application that provides tens of QSAR models to predict tox, ecotox, environ, and phys-chem properties of chemical substances. Binary distribution files for the VEGA standalone GUI application (and for other applications based on its models) are available on the [VEGA HUB website](https://www.vegahub.eu/).

The repository for the standalone application is [VEGA-GUI](https://github.com/amanganaro/VEGA-GUI).

Repositories for all the other components used by the VEGA application:

| Repository&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Description |
| ----- | ----- |
| [VEGA-insilico-core](https://github.com/amanganaro/VEGA-insilico-core) | Core libraries for the VEGA project |
| [VEGA-insilico-core-aux](https://github.com/amanganaro/VEGA-insilico-core-aux) | Auxiliary libraries for specific groups of models (PMML) |   
| [VEGA-alertspng](https://github.com/amanganaro/VEGA-alertspng) | Cached version of depictions for alerts (no code, just PNG files) |   
| [VEGA-padeladapter](https://github.com/amanganaro/VEGA-padeladapter) | Padel adapter libraries for the VEGA project (provides an interface to use a legacy Padel on an older version of the CDK) |
| [VEGA-coral](https://github.com/amanganaro/VEGA-coral) | Coral libraries for the VEGA project, implementing a Java porting of the Coral application developed by Andrey and Alla Toropov |
| [VEGA-NRMEA](https://github.com/amanganaro/VEGA-NRMEA) | NRMEA libraries for the VEGA project, implementing the core functionalities to run NRMEA models (developed by Prof. Wei Shi, University of Nanjing) |
| [VEGA-toxtree](https://github.com/amanganaro/VEGA-toxtree) | Porting of models from ToxTree (Verhaar and Cramer) |
| [VEGA-python-models](https://github.com/amanganaro/VEGA-python-models) | Source for all Python models used in VEGA |
| [VEGA-resources-cddd](https://github.com/amanganaro/VEGA-resources-cddd) | Serialized Python CDDD model |
| [VEGA-models-human](https://github.com/amanganaro/VEGA-models-human) | Collections of QSAR models related to human toxicity |
| [VEGA-models-ecotox](https://github.com/amanganaro/VEGA-models-ecotox) | Collections of QSAR models related to eco-toxicity |
| [VEGA-models-fate](https://github.com/amanganaro/VEGA-models-fate) | Collections of QSAR models related to environmental fate |
| [VEGA-models-properties](https://github.com/amanganaro/VEGA-models-properties) | Collections of QSAR models related to physical-chemical properties |
| [VEGA-models-other](https://github.com/amanganaro/VEGA-models-other) | Collections of QSAR models related to all other endpoints |
| [VEGA-models-all](https://github.com/amanganaro/VEGA-models-all) | Wrapper for all available VEGA models |

An additional repository (VEGA-resources-python), with resources (environments) for the Python models, is not available here due to Github LFS limitations. We can share it on demand, the artifact is anyway available in the Maven repository reported in the POM files of the VEGA-GUI project.
