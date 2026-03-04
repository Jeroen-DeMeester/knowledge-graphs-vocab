---
layout: default
title: Knowledge Graphs Vocabulary
---

This vocabulary defines the following **classes** and **properties**:

## Classes

- `jdm:Person` – A human individual  
- `jdm:Organization` – An organization: a company, museum, ...  
- `jdm:Museum` – A museum institution  

## Properties

- `jdm:name` – The full name of a person or organization  
- `jdm:birthDate` – The birth date of a person  
- `jdm:knows` – Indicates that a person knows another person  
- `jdm:worksAt` – Indicates the organization where a person works  
- `jdm:hobby` – A hobby or leisure activity of a person  
- `jdm:website` – The website of a person or organization

### External vocabularies
This vocabulary uses or aligns with external vocabularies, e.g.:
- mnh:human, mnh:name, mnh:knows from [Minh Tran's vocabulary](https://minhphtran.github.io/knowledge-graphs-vocab/vocab#)
- lrs:Person, lrs:name, lrs:knows from [Tobias Laurens' vocabulary](https://laurenstobias.com/vocab#)

### Vocabulary file
You can download or view the full vocabulary [here](vocab.ttl).

### Data file
You can download or view the full dataset [here](data.ttl), containing instances of persons, organizations, and their relationships.
