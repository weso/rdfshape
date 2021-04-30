# RDFShape

RDFShape is full web application for semantic data analysis and validation where you can toy with...
- RDF conversion between different formats like Turtle and JSON-LD
- RDF validation using ShEx (Shape Expressions) and SHACL (Shapes Constraint Language)
- RDF querying with SPARQL
- RDFS and OWL inference

...among others.

## FYI
This is a general repository for explanations and configuration files of RDFShape. **If you're searching for detailed instructions or tutorials for the backend or frontend of this tool, head to the linked repositories.**

# Quick reference
- **Maintained by**: [WESO Research Group](https://weso.es)

# Structure of RDFShape

RDFShape is formed by:

- **rdfshape-api**: A backend in charge of the operations, which are exposed in the form of a public API
  - [Repo](https://github.com/weso/rdfshape-api)
  - [Deployment](https://api.rdfshape.weso.es)
- **rdfshape-client**: A general use-case client
  - [Repo](https://github.com/weso/rdfshape-client)
  - [Deployment](https://rdfshape.weso.es)
- **wikishape**: A wikibase/wikidata oriented client
  - [Repo](https://github.com/weso/wikishape)
  - [Deployment](https://wikishape.weso.es/)


# Deploying a full RDFShape stack (server & clients)
A template [docker-compose file](https://github.com/weso/rdfshape/blob/master/docker-compose.yml) is available in this repository for users to tweak it according to their needs.

If you only require certain services of the RDFShape stack or want to test them out yourself, the Dockerfiles and detailed instructions on how to build/run the Docker images can be found in each module's repository.

Alternatively, you may get yourself a fully operational RDFShape service using our [deployed services](https://github.com/weso/rdfshape#structure-of-rdfshape).

### WESO members
Weso members can access the instructions for deploying RDFShape in our [Wiki](https://github.com/weso/wesolocal/wiki/rdfshape).

# Contribution and issues

Contributions are greatly appreciated. Please head to the specific sub-repositories of RDFShape to open a
pull request to add more features or submit issues:

* [Issues about RDFShape API](https://github.com/weso/rdfshape-api#contribution-and-issues)
* [Issues about RDFShape Client](https://github.com/weso/rdfshape-client#contribution-and-issues)
* [Issues about Wikishape](https://github.com/weso/wikishape#contribution-and-issues)
