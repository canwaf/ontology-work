# DEFRA Linked Data Domain Model

This repository is an effort to create a linked data domain model for the Defra Group. It aims to provide a structured, machine-readable representation of regulatory and water-related data, supported by a core ontology.

## Project Structure

The model is currently composed of two primary ontologies:
- **Core Ontology**: Provides reusable classes and properties (e.g., Party, Organisation, Site, Document).
- **Regulation Ontology**: Covers regulatory concepts such as Permits, Conditions, Limits, and Breaches.

And three ontologies which extend the primary ontologies to address domain specific components:
- **Farming Ontology**: Contains specific domain knowledge regarding Sustainable Farming Incentive Schemes, Applcations, and Options.
- **Nature Ontology**: COntains specific domain knowledge regarding Protected Sites.
- **Water Ontology**: Contains specific domain knowledge regarding Water Bodies, Catchments, and related activities.

## Status

**Work in Progress**
Please note that this project is currently a work in progress. It is being constructed as a foil to begin formal consideration of DEFRA's domain and is subject to major changes as it is being developed.

## Legacy Data

The `legacy/` folder contains the first attempt at this process. This folder will eventually be deleted as the new structure is finalized.

## Licence

Unless stated otherwise, the codebase in this repository is released under the [MIT License](LICENCE).

Copyright (c) 2026 Crown Copyright (Government Digital Service)

The documentation and any other non-code content in this repository is licensed under the [Open Government Licence v3.0](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/), except where otherwise stated.

Contains public sector information licensed under the Open Government Licence v3.0.
