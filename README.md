# LstarkeyiMalicAcidProduction

- [Description](#description)
- [Setup](#setup)
- [Summary of files](#summary-of-files)
- [Reference](#reference)
- [License](#license)

## Description

Medium components have a profound impact on production of microbial products. The effects of metals and vitamins on *L. starkeyi* malic acid production is being explored here. The Automated Recommendation Tool ([ART](https://www.nature.com/articles/s41467-020-18008-4)) is a machine learning based tool for bioproduction applications. The tool has been designed to provide both initial design of experiment and recommendations for further designs. The algorithm uses [Latin Hypercube Sampling](https://en.wikipedia.org/wiki/Latin_hypercube_sampling) to combinatorally explore the initial design space. 

A media optimization pipeline has been described using ART ([Zournas A et al. (2024): DOI: 10.21203/rs.3.rs-5072705/v1](https://www.researchsquare.com/article/rs-5072705/v1)), and it is leveraged here to perform medium optimization in engineered _Lipomyces starkeyi_. 

Information about licensing ART is available at https://github.com/JBEI/ART. See [Radivojević et al](https://www.nature.com/articles/s41467-020-18008-4) for more information on ART. 


## Setup

The medium optimization utilized the Automated Recommendation Tool. 

* Information about licensing ART is available at https://github.com/JBEI/ART. See [Radivojević et al](https://www.nature.com/articles/s41467-020-18008-4) for more information on ART.
* Simulations were ran within the ART Docker container as described at the [ART repo](https://github.com/JBEI/ART). 

## Summary of files


* Lipomyces_Media_Opt_Cycle1.ipynb - initial medium parameter space exploration notebook, DBTL1. 
* Lipomyces_Media_Opt_Round2_partA.ipynb - DBTL2 - learning from DBTL1 results. 
* Lipomyces_Media_Opt_Round2_moreExplore_partB.ipynb - DBTL2 - including additional explore medium conditions. 
* Lipomyces_Media_Opt_Round3.ipynb - DBTL3 - learning from DBTL1 and DBTL2.
* mediumSetup - directory containing files for running ART.
* mediumConcentrationOuputs - directory containing the outputs of ART (i.e., medium concentrations to test and ART model files (as pickles).
* experimentalResults - directory containing medium compositions used in experiments as well as the corresponding results (biomass, malic acid production). 


## Reference

This work is currently under review (21 Nov 2024). 

## License

Released under the Creative Commons 0 Public Domain Dedication: 
https://creativecommons.org/publicdomain/zero/1.0/
 
This material is free to use, and attribution is always appreciated.  Attribution may be as follows:
Authored by Jeffrey Czajka (Staff) at the Pacific Northwest National Laboratory, operated by Battelle for the U.S. Department of Energy.
Please cite the following in your work: Under reviewer.
 
 
 
This material was prepared as an account of work sponsored by an agency of the United States Government.  Neither the United States Government nor the United States Department of Energy, nor the Contractor, nor any or their employees, nor any jurisdiction or organization that has cooperated in the development of these materials, makes any warranty, express or implied, or assumes any legal liability or responsibility for the accuracy, completeness, or usefulness or any information, apparatus, product, software, or process disclosed, or represents that its use would not infringe privately owned rights.
Reference herein to any specific commercial product, process, or service by trade name, trademark, manufacturer, or otherwise does not necessarily constitute or imply its endorsement, recommendation, or favoring by the United States Government or any agency thereof, or Battelle Memorial Institute. The views and opinions of authors expressed herein do not necessarily state or reflect those of the United States Government or any agency thereof.
 
PACIFIC NORTHWEST NATIONAL LABORATORY
operated by
BATTELLE
for the
UNITED STATES DEPARTMENT OF ENERGY
under Contract DE-AC05-76RL01830

