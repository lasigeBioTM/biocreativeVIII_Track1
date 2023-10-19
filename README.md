# BioRED track lasigeBioTM submission: Relation extraction using Domain Ontologies with BioRED

The present repository contains the data used for our participation at the BioCreative VIII Track 1 Biored in both sub-tasks.

The paper describing our participation (team lasigeBioTM)  will be available [here](TODO).

## Data availability
### Tools
* Named-Entity Recognition: [HunFlair](https://github.com/flairNLP/flair/blob/master/resources/docs/HUNFLAIR.md)
* Relation Extraction: [K-RET](https://github.com/lasigeBioTM/K-RET)

### Knowledge Bases
#### NER
  * [ChemicalEntity](http://ctdbase.org/voc.go;jsessionid=7F90D81FA6B04BB14500F8B04D1BEF4D?type=chem)
  * [GeneOrGeneProduct](https://www.ncbi.nlm.nih.gov/gene/)
  * [OrganismTaxon](https://www.ncbi.nlm.nih.gov/taxonomy)
  * [DiseaseOrPhenotypicFeature](http://ctdbase.org/voc.go;jsessionid=7F90D81FA6B04BB14500F8B04D1BEF4D?type=disease)
  * [CellLine](https://www.cellosaurus.org/index.html)
#### RE
  * [Human Phenotype Ontology (HPO)](https://hpo.jax.org/app/data/ontology)
  * [Human Disease Ontology (DO)](https://www.ebi.ac.uk/ols/ontologies/doid)
  * [Chemical Entities of Biological Interest (ChEBI)](https://www.ebi.ac.uk/chebi/)
  * [NCBITaxon Ontology](https://www.ebi.ac.uk/ols/ontologies/ncbitaxon)
  * [Gene Ontology (GO)](http://geneontology.org/)

## Sub-task 1 Results
### Official Runs
| RUN 1                              	| P      	| R      	| F      	|
|------------------------------------	|--------	|--------	|--------	|
| Entity pair:                       	| 0.1942 	| 0.9914 	| 0.3248 	|
| Entity pair+Relation type:         	| 0.0435 	| 0.2218 	| 0.0727 	|
| Entity pair+Novelty:               	| 0.0770 	| 0.3963 	| 0.1290 	|
| Entity pair+Relation type+Novelty: 	| 0.0177 	| 0.0908 	| 0.0296 	|

### Unofficial Runs
|                                    	|        	|  RUN 1 	|        	|   	|        	|  RUN 2 	|        	|   	|        	|  RUN 3 	|        	|
|:----------------------------------:	|:------:	|:------:	|:------:	|:-:	|:------:	|:------:	|:------:	|:-:	|:------:	|:------:	|:------:	|
|                                    	|    P   	|    R   	|    F   	|   	|    P   	|    R   	|    F   	|   	|    P   	|    R   	|    F   	|
| Entity pair:                       	| 0.1942 	| 0.9914 	| 0.3248 	|   	| 0.1942 	| 0.9914 	| 0.3248 	|   	| 0.1942 	| 0.9914 	| 0.3248 	|
| Entity pair+Relation type:         	| 0.0825 	| 0.4214 	| 0.1381 	|   	| 0.0801 	| 0.4091 	| 0.1340 	|   	| 0.0435 	| 0.2218 	| 0.0727 	|
| Entity pair+Novelty:               	| 0.0770 	| 0.3963 	| 0.1290 	|   	| 0.0770 	| 0.3963 	| 0.1290 	|   	| 0.0770 	| 0.3963 	| 0.1290 	|
| Entity pair+Relation type+Novelty: 	| 0.0329 	| 0.1695 	| 0.0552 	|   	| 0.0309 	| 0.1592 	| 0.0518 	|   	| 0.0177 	| 0.0908 	| 0.0296 	|


## Sub-task 2 Results
### Official Runs
| RUN 1                             	| P      	| R      	| F      	|
|------------------------------------	|--------	|--------	|--------	|
| NER:                               	| 0.0003 	| 0.0001 	| 0.0001 	|
| Normalization:                     	| 0.4477 	| 0.0710 	| 0.1226 	|
| Entity pair:                       	| 0.0563 	| 0.0219 	| 0.0315 	|
| Entity pair+Relation type:         	| 0.0128 	| 0.0050 	| 0.0072 	|
| Entity pair+Novelty:               	| 0.0187 	| 0.0073 	| 0.0105 	|
| Entity pair+Relation type+Novelty: 	| 0.0047 	| 0.0018 	| 0.0026 	|

### Unofficial Runs
|                                    	|        	|  RUN 1 	|        	|   	|        	|  RUN 2 	|        	|
|:----------------------------------:	|:------:	|:------:	|:------:	|:-:	|:------:	|:------:	|:------:	|
|                                    	|    P   	|    R   	|    F   	|   	|    P   	|    R   	|    F   	|
| NER:                               	| 0.7703 	| 0.6411 	| 0.6998 	|   	| 0.7703 	| 0.6411 	| 0.6998 	|
| Normalization:                     	| 0.4212 	| 0.2280 	| 0.2958 	|   	| 0.4212 	| 0.2280 	| 0.2958 	|
| Entity pair:                       	| 0.0427 	| 0.0633 	| 0.0510 	|   	| 0.0427 	| 0.0633 	| 0.0510 	|
| Entity pair+Relation type:         	| 0.0110 	| 0.0163 	| 0.0131 	|   	| 0.0084 	| 0.0125 	| 0.0100 	|
| Entity pair+Novelty:               	| 0.0207 	| 0.0307 	| 0.0247 	|   	| 0.0207 	| 0.0307 	| 0.0247 	|
| Entity pair+Relation type+Novelty: 	| 0.0058 	| 0.0086 	| 0.0069 	|   	| 0.0040 	| 0.0060 	| 0.0048 	|
