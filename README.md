# NFDI4Earth HydroOntology

The **NFDI4Earth HydroOntology** is a lightweight, domain-specific ontology developed to describe hydrological concepts, variables, and relationships in a semantically consistent and machine-readable way. It is intended to support the **FAIR (Findable, Accessible, Interoperable, Reusable)** principles for hydrological data by enabling semantic annotation, RDF transformation, and integration into knowledge graphs.

This ontology was developed as part of [NFDI4Earth project](https://www.nfdi4earth.de/) focused on transforming conventional hydrology datasets (e.g., CSVs) into semantically enriched RDF knowledge graphs, enabling better interoperability, query capabilities, and integration with other datasets using Semantic Web technologies.

## 🌊 Purpose and Scope

Hydrological datasets are often shared in formats like CSV, which lack semantic annotations and thus pose challenges for data discovery, reuse, and automated reasoning. The **NFDI4Earth HydroOntology** addresses these challenges by:

- Defining core hydrological entities (e.g., rivers, catchments, observations, sensors).
- Linking to existing vocabularies (e.g., SOSA, QUDT, Schema.org).
- Supporting the semantic transformation of datasets such as **LamaH-CE**.
- Enabling intelligent querying through **SPARQL** or integration with **question-answering systems**.

## 📦 Repository Contents

- [`NFDI4Earth_HydroOntology_FULL.ttl`](./NFDI4Earth_HydroOntology_FULL.ttl): The full OWL ontology in Turtle syntax.
- `README.md`: This documentation file describing the ontology and its usage.

## 🚀 Key Features

- OWL-compliant ontology built on RDF standards.
- Alignments with:
  - [SOSA/SSN](https://www.w3.org/TR/vocab-ssn/): For sensor and observation modeling.
  - [QUDT](http://qudt.org/): For units and quantities.
  - [Schema.org](https://schema.org): For general-purpose descriptions.
- Built-in support for mapping CSV columns to ontology concepts via custom mapping configuration.

## 🧪 Example Use Case

The ontology was used to annotate and convert the [LamaH-CE](https://github.com/realwaterresearch/LamaH-CE) dataset to RDF using a custom-built tool called **HydroTurtle**. The annotated RDF knowledge graph enabled:

- Integration of catchment attributes and time series measurements.
- Execution of SPARQL queries for hydrological analysis.
- Natural Language Question Answering over RDF data.

## 🔗 Ontology URI and Prefix

- Ontology base URI: [`https://nfdi4earth.pages.rwth-aachen.de/knowledgehub/nfdi4earth-ontology/test_hyd#`](https://nfdi4earth.pages.rwth-aachen.de/knowledgehub/nfdi4earth-ontology/test_hyd#)
- Recommended prefix: `n4e_hyd`




