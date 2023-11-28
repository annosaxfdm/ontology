# The Anthropological Notation Ontology (ANNO)

[![build](https://github.com/annosaxfdm/ontology/actions/workflows/build.yml/badge.svg)](https://github.com/annosaxfdm/ontology/actions/workflows/build.yml)
[![SHACL status](https://github.com/annosaxfdm/ontology/actions/workflows/shacl.yml/badge.svg)](https://github.com/annosaxfdm/ontology/actions/workflows/shacl.yml)
[![License: CC BY 4.0](https://img.shields.io/badge/license-CC_BY_4.0-blue)](LICENSE)
[![DOI](https://zenodo.org/badge/473966297.svg)](https://zenodo.org/badge/latestdoi/473966297)

ANNO consists of ANNOdc (domain-core) and ANNOds (domain-specific).
ANNOdc is connected to the General Formal Ontology (GFO).

## Files

The [master](https://github.com/annosaxfdm/ontology/tree/master) branch contains the newest versions of [ANNOdc](annodc.owl) and [ANNOds](annods.owl).
RDF Turtle serializations are available in the [dist](https://github.com/annosaxfdm/ontology/tree/dist) branch:

* [anno.ttl](https://github.com/annosaxfdm/ontology/blob/dist/anno.ttl) combination of ANNOdc and ANNOds
* [anno-ols.ttl](https://github.com/annosaxfdm/ontology/blob/dist/anno-ols.ttl) combination with language tags removed, use this only with OLS 2
* [shacl.ttl](https://github.com/annosaxfdm/ontology/blob/dist/shacl.ttl) SHACL shapes for validation

## Releases

Releases have the [calendar versioning](https://calver.org/) scheme YY.MM for short year and short month.
For example, [23.08](https://github.com/annosaxfdm/ontology/releases/tag/23.11) is the state of November 2023 and contains the ontology as <https://github.com/annosaxfdm/ontology/releases/download/23.11/anno.ttl>.
You can also use the dynamic link to the newest version at <https://github.com/annosaxfdm/ontology/releases/latest/download/anno.ttl>.respectively [anno-ols.ttl](https://github.com/annosaxfdm/ontology/releases/latest/download/anno-ols.ttl).

## Validation

Install [pySHACL](https://github.com/RDFLib/pySHACL) and execute the `scripts/shacl` shell script.

## See Also

* [Project Website](https://annosaxfdm.de)
* [Paper (under development)](https://github.com/annosaxfdm/anno-paper-swj)
* [Project Website Repository](https://github.com/annosaxfdm/annosaxfdm.de)
* [Anno Ontology Lookup Service (OLS)](https://ols.imise.uni-leipzig.de/index)
* [Anno OLS Repository](https://github.com/annosaxfdm/ols)
* [OLS Synchronization Component Repository](https://github.com/annosaxfdm/olsync)
