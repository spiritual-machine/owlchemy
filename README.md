# owlchemy 🦉🌙

**owlchemy: A high-performance ontology annotator for turning your metadata into semantic gold.**

`owlchemy` is a Python library for high-throughput semantic annotation. It bridges the gap between messy, real-world metadata and formal ontologies.

It's the tool you've been missing:
* **Smarter than** lexical tools (like `text2term`) that can't find synonyms.
* **Simpler than** complex academic frameworks (like `BERTMap`) that are overkill for annotation.

This package is the engine for a human-in-the-loop ETL pipeline, designed to turn data into a clean, searchable, and interconnected knowledge graph. Users may specify their own ontologies-- either from local files or online-- allowing for customizability and privacy that online annotators and APIs cannot offer.

## The Core Idea

`Owlchemy` works by pre-processing one or more `.owl` ontologies into a high-speed vector index. It turns all class labels, synonyms, and definitions into mathematical representations.

When you query with a term, it uses high-performance indexed `numpy` matrix operations to instantly find the closest semantic match from hundreds of thousands of concepts in milliseconds. 

## Funding Acknowledgements
