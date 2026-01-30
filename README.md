# persona-ontology

The persona ontology is an application profile over existing OWL ontologies. It models the domain of natural people in the Mee Identity Agent. It documents in SHACL which classes and properties from other ontologies are used to describe a person. 

## Ontologies used

| Prefix | Namespace                                                | Notes                         | Source                                                                                                                                                                       |
|--------|----------------------------------------------------------|-------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| bfo    | http://purl.obolibrary.org/obo/BFO_                      | Basic Formal Ontology         | [bfo-core.ttl](https://github.com/BFO-ontology/BFO-2020/blob/master/21838-2/owl/bfo-core.ttl)                                                                                |
| cco    | http://www.ontologyrepository.com/CommonCoreOntologies/  | Common Core Ontologies        | [CommonCoreOntologiesMerged.ttl](https://opensource.ieee.org/cco/CommonCoreOntologies/-/raw/cameronmore-master-patch-e888/CCO-2.0/cco-merged/CommonCoreOntologiesMerged.ttl) | 
| uo     | http://purl.obolibrary.org/obo/UO_                       | Units Ontology                | |
| po     | http://www.ontologyrepository.com/CommonCoreOntologies/  | Person Ontology               | [PersonOntology.ttl](https://opensource.ieee.org/po/person-ontology-project/-/raw/master/dev/Person-Ontology-dev.ttl?ref_type=heads)                                         |
| iao    | http://purl.obolibrary.org/obo/IAO_                      | Information Artifact Ontology | | 
| dct    | http://purl.org/dc/terms/                                | Metadata only                 | | 
| sh     | http://www.w3.org/ns/schacl#                             | Metadata only                 | | 
| p      | http://www.mee.foundation/ontologies/persona#            | TBD                           | [persona.ttl](https://raw.githubusercontent.com/MeeFoundation/persona-ontology/refs/heads/main/persona.ttl)                                                                  | 
   
