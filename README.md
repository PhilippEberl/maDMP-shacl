# About this project
Since machine-actionable Data Management Plans are becoming more and more common, there are also increased benefits not only for researchers, but also for funders. In this project we aim to extend the current defined constraints in order to support even more funding related constraints. This is done with the help of rewritten SPARQL queries into SHACL. This project just uses the existing one with all its files like the maDMPs. All mappings and criteria conversion stay the same. We also only used the already pre-processed JSON-LD files in order to speed up the validation process and without having to pre-process everything again.

## Validation of maDMPs with SHACL
This project should replace the existing SPARQL validation queries with the newer SHACL ones. Since SPARQL is to some extent verbose and error prone, we used SHACL for validation.

## Base of this project
The base of this project were the already existing SPARQL queries writen by [raffaelfoidl](https://github.com/raffaelfoidl/maDMP-evaluation/tree/v1.2) and the corresponding report can be found under [![DOI](https://zenodo.org/badge/364735916.svg)](https://zenodo.org/badge/latestdoi/364735916). The [JSON-LD](https://github.com/raffaelfoidl/maDMP-evaluation/tree/v1.2/maDMPs/5-json-ld-postprocessed) files are provided already by the contributors who created the validation queries with SPARQL.

## Structure of this repository
* `queries`: SHACL queries for quality assessment and validation of existing maDMPs

We do not include the DMPs in our project, since they can be found on the creators [GitHub repository](https://github.com/raffaelfoidl/maDMP-evaluation/tree/v1.2/maDMPs).
