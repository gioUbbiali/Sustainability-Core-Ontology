# Sustainability Core Ontology

## Description

This repository maintains the Sustainability Core Ontology (SCO). SCO is a middle-level ontology, covering the terminology related to the three major theoretical challenges of sustainability [Ubbiali *et al.* (2024)](https://doi.org/10.31219/osf.io/z8uqr ):
1) The polysemy of the term "sustainability".
2) The relationship between sustainability and sustainable development.
3) The complexity underlying sustainability.
   
SCO is designed to be the pivotal resource upon which to harmonize and integrate top-level and domain ontologies regarding sustainability. The ultimate goal is to establish a family of interoperable sustainability ontologies. Currently, SCO offers ontological representations that align with [Basic Formal Ontology (BFO)](https://github.com/BFO-ontology/BFO-2020) and [Unified Foundational Ontology (UFO)](https://ontouml.readthedocs.io/en/latest/intro/ufo.html).


See also the [SCO-B documentation webpage](https://w3id.org/sco/docs) and [SCO-U documentation webpage](https://w3id.org/sco/sco-u/docs).

## Material


To date, this repository hosts the SCO Structured Vocabulary (SCO SV) and the current release of SCO, SCO V1.1.0. 


### SCO SV

The SCO SV is an initial (non-exhaustive) ontological resource providing some essential terms and relations to include in SCO. This resource has been developed as Annex 2 of [Ubbiali *et al.* (2024)](https://doi.org/10.31219/osf.io/z8uqr).

The SCO SV includes two spreadsheets: 

- [The SCO SV guidelines.](https://github.com/gioUbbiali/Sustainability-Core-Ontology/tree/main/SCO%20SV%20guidelines)
- [The SCO SV.](https://github.com/gioUbbiali/Sustainability-Core-Ontology/tree/main/SCO%20SV%20guidelines) 

The SV guidelines spreadsheet details the methodology followed for constructing the list.

SCO structured vocabulary spreadsheets are available in both Excel and CSV formats. The SCO SV spreadsheet also contains the graphical representation (named Supplementary Fig. S1 The structured vocabulary of SCO) of SCO SV in JPG format.


### SCO V1.1.0.

SCO V1.1.0. implements [SCO V1.0.1.](https://github.com/gioUbbiali/Sustainability-Core-Ontology/releases/tag/v1.0.1) by establishing an additional ontology segment aligned to [Unified Foundational Ontology (UFO)](https://ontouml.readthedocs.io/en/latest/intro/ufo.html). SCO V1.0.1. only employes [Basic Formal Ontology (BFO)](https://github.com/BFO-ontology/BFO-2020) as the upper level ontology. 

SCO V1.1.0. is comprised of two segments: SCO-B (B for BFO) and SCO-U (U for UFO). SCO-B aligns the SCO vocabulary with [BFO](https://github.com/BFO-ontology/BFO-2020). SCO-U aligns the SCO vocabulary with [gUFO (UFO implementation in OWL)](https://nemo-ufes.github.io/gufo/). SCO V1.1.0. also includes a [SKOS vocabulary](https://www.w3.org/2004/02/skos/)-based mapping between the two segments.

SCO V1.1.0. is formalized in [OWL](https://www.w3.org/TR/owl2-overview/) and covers three natural languages, English, French, and Italian. SCO V1.1.0. conforms to [OBO-Foundry principles](https://obofoundry.org/principles/fp-000-summary.html). SCO-B includes 80 classes, 84 object properties, and 2 individuals. SCO-U includes 197 classes, 151 object properties, and 106 individuals.


SCO materials can be found here:


- [SCO V1.0.1. release.](https://github.com/gioUbbiali/Sustainability-Core-Ontology/releases/tag/v1.0.1-revisions)
- [SCO-B current release](https://github.com/gioUbbiali/Sustainability-Core-Ontology/blob/main/sco-b.ttl).
- [SCO-U current release](https://github.com/gioUbbiali/Sustainability-Core-Ontology/blob/main/sco-u.ttl).
- [Mapping between SCO-B and SCO-U](https://github.com/gioUbbiali/Sustainability-Core-Ontology/blob/main/sco-u-b-mapping.ttl).
- [SCO V1.1.0.- final draft versions prior to release](https://github.com/gioUbbiali/Sustainability-Core-Ontology/tree/main/SCO%20material/src/ontology).
- [SCO V1.1.0. imports](https://github.com/gioUbbiali/Sustainability-Core-Ontology/tree/main/SCO%20material/src/ontology/imports).
- [SCO materials](https://github.com/gioUbbiali/Sustainability-Core-Ontology/tree/main/SCO%20material).
- [SCO V1.1.0. development protocol](https://github.com/gioUbbiali/Sustainability-Core-Ontology/tree/main/SCO%20material/SCO%20development%20protocol).

  
The most recent version of SCO-B segment can always be found at https://w3id.org/sco/sco-b. The most recent version of SCO-U segment can always be found at https://w3id.org/sco/sco-u. The most recent version of the mapping between SCO-U and SCO-B can always be found at https://w3id.org/sco/sco-u-b-mapping. SCO is also accessible on [Ontobee](https://ontobee.org/ontology/SCO), [AgroPortal](https://agroportal.lirmm.fr/ontologies/SCO), [BioPortal](https://bioportal.bioontology.org/ontologies/SCO_V1), and [IndustryPortal](https://industryportal.enit.fr/ontologies/SCO).

### SCO - Useful Links

- [SCO V1.0.1.](https://w3id.org/sco)
- [SCO V1.1.0. - SCO-B](https://w3id.org/sco/sco-b).
- [SCO V1.1.0. - SCO-B. BFO merged](https://w3id.org/sco/sco-b-bfo-merged).
- [SCO V1.1.0. - SCO-U](https://w3id.org/sco/sco-u).
- [SCO V1.1.0. - SCO-U. UFO merged](https://w3id.org/sco/sco-ufo-merged).
- [SCO V1.1.0. - mapping between SCO-U and SCO-B](https://w3id.org/sco/sco-u-b-mapping).
- [SCO V1.1.0. SCO-B - documentation webpage](https://w3id.org/sco/sco-b/docs).
- [SCO V1.1.0. SCO-U - documentation webpage](https://w3id.org/sco/sco-u/docs).


##  SCO Developer   

[Giorgio A.Ubbiali](https://orcid.org/0000-0001-7872-1770)


## Involved Institutions in the Development of SCO V1.1.0. 

[UNIMI](https://www.unimi.it/it)

[UT](https://www.utwente.nl/en/)


## Involved Institutions in the Development of SCO V1.0.1. 

[UNIMI](https://www.unimi.it/it)

[UT](https://www.utwente.nl/en/)


## Involved Institutions in the Development of SCO V1.0.0. 

[UNIMI](https://www.unimi.it/it)

[IC-FOODS](https://www.ic-foods.org/)


## Involved Institutions in the Development of SCO-SV 

[UNIMI](https://www.unimi.it/it)

[IC-FOODS](https://www.ic-foods.org/)


## Contact

Giorgio A. Ubbiali - Giorgio.Ubbiali@unimi.it


## Publications and Documentation

- Ubbiali, G. A., Borghini, A., & Lange, M. C. (2024). *Ontologies for Sustainability: Theoretical Challenges*. https://doi.org/10.31219/osf.io/z8uqr 

- Ubbiali, G. A. (2025). *Designing Foundational Strategies for Developing a Family of Food Systems Sustainability Ontologies*. PhD Thesis, UNIMI. https://air.unimi.it/handle/2434/1161515



## License
This work is licensed under [CC BY 4.0 ](https://creativecommons.org/licenses/by/4.0/)
