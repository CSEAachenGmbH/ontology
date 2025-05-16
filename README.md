# Circle Ontology Demonstration!

## Overview:

Ontology File: pcf-model.rdf – contains the RDF ontology.

Documentation Tool: Widoco – generates structured, multilingual HTML documentation from RDF/OWL files.

Automation: GitHub Actions – automates the generation and deployment process.

Publishing: GitHub Pages – hosts the generated documentation at
https://cseaachengmbh.github.io/ontology.

### More Details:

This repository uses an automated workflow based on GitHub Actions to generate and publish an HTML documentation of the included RDF ontology via GitHub Pages.

On every push to the main branch or when manually triggered, the current state of the RDF file (pcf-model.rdf) is processed. The Widoco tool is used to automatically create a structured, multilingual HTML documentation from the RDF ontology.

Afterwards, the contents of the docs folder are uploaded as an artifact and published through GitHub Pages. The publication process is fully automated and requires no additional manual steps. Any changes made to the RDF file or the repository will be automatically reflected on the published website shortly after.

The generated documentation can be accessed at the following URL:
https://cseaachengmbh.github.io/ontology/


## How it Works:

Each time a change is pushed to the main branch (or triggered manually), the following workflow runs:

    Documentation Generation: Widoco processes the pcf-model.rdf file and generates HTML documentation.

    Deployment: The generated files are placed into the docs directory.

    Publishing: GitHub Pages automatically publishes the contents of the docs folder.

This ensures that any changes made to the ontology are quickly reflected in the public documentation.


## Repository Structure:

.
├── .github/
│   └── workflows/
│       └── [CI workflow files]

├── CITATION.cff

├── CODE_OF_CONDUCT.md

├── LICENSE

├── README.md


└── pcf-model.rdf


## Technical Details

    Build tool: Widoco

    Hosting platform: GitHub Pages

    Automation: GitHub Actions


For more information or questions, please contact the team at CSEAachenGmbH.

## Note

To update the published website, it is sufficient to make changes to the repository and push them to the main branch. Alternatively, the workflow can be triggered manually via the GitHub Actions interface.
