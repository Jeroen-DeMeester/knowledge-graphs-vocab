---
layout: default
title: Knowledge Graphs Vocabulary
---

This knowledge graph combines:

- Vocabulary – the ontology defining classes and properties.
- Data – instances of people, organizations, places, and photographs, and their relationships.
- Rules for FOAF reasoning – bridge rules to map the custom jdm: vocabulary to the FOAF ontology for interoperability and querying.

## Classes

- `jdm:Person` – A human individual  
- `jdm:Organization` – An organization: a company, museum, ...  
- `jdm:Museum` – A museum institution
- `jdm:Photograph` – A photograph taken by a photographer
- `jdm:Place` – A location where something is situated or took place

## Properties

- `jdm:name` – The full name of a person or organization  
- `jdm:birthDate` – The birth date of a person  
- `jdm:knows` – Indicates that a person knows another person  
- `jdm:worksAt` – Indicates the organization where a person works  
- `jdm:hobby` – A hobby or leisure activity of a person  
- `jdm:website` – The website of a person or organization
- `jdm:sameCourse` – Indicates that two persons participate in the same course
- `jdm:title` – The title of a photograph
- `jdm:hasPhotographer` – Indicates the photographer of a photograph
- `jdm:depicts` – Indicates which person is depicted in a photograph
- `jdm:takenAt` – Indicates where the photograph was taken
- `jdm:description` – A description of the photograph
- `jdm:image` – A link to the image file of the photograph

## Files

### Vocabulary file
You can download or view the full vocabulary [here](vocab.ttl).

### Data file
You can download or view the full dataset [here](data.ttl).
It contains instances of persons, organizations, places, and photographs, and their relationships.

### Rules for FOAF reasoning
To use FOAF-based queries and reasoning with a Notation3 reasoner like EYE, you can use the bridge rules defined in rules.n3.
You can download or view the rules [here](rules.n3).
