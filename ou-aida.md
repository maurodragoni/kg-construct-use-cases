# USE CASE AIDA BY The Open University

## Context
The Academia/Industry DynAmics (AIDA) Knowledge Graph describes 21M publications and 8M patents according to the research topics drawn from the Computer Science Ontology (http://cso.kmi.open.ac.uk/). 5.1M publications and 5.6M patents are further characterized according to the type of the author's affiliations (academy, industry, or collaborative) and 66 industrial sectors (e.g., automotive, financial, energy, electronics) organized according to the INDUSO ontology (https://aida.kmi.open.ac.uk/downloads/induso.ttl). AIDA was generated by an automatic pipeline that integrates data from Microsoft Academic Graph, Dimensions, DBpedia, the Computer Science Ontology, and the Global Research Identifier Database. It is publicly available under CC BY 4.0 and can be downloaded as a dump or queried via a triplestore.

## Challenges
1. Generating a coherent KG from multiple sources: Microsoft Academic Graph, Dimensions, DBpedia, and the Global Research Identifier Database.
2. Improving the scalability of the generation process.
3. Improving data completeness (e.g., detecting the industrial sectors of companies that are not in DBpedia).

## Resources
- Website: http://w3id.org/aida
- SPARQL endpoint: http://w3id.org/aida/sparql
- Data dumps: https://aida.kmi.open.ac.uk/downloads.php
- Ontology: http://w3id.org/aida/ontology
- Paper: Angioni, S., Salatino, A.A., Osborne, F., Recupero, D.R. and Motta, E., 2020, August. Integrating knowledge graphs for analysing academia and industry dynamics. In ADBIS, TPDL and EDA 2020 Common Workshops and Doctoral Consortium (pp. 219-225). Springer, Cham. (http://oro.open.ac.uk/70715/)