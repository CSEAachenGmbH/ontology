# Circle Ontology Demonstration!

This repository uses an automated workflow based on GitHub Actions to generate and publish an HTML documentation of the included RDF ontology via GitHub Pages.

On every push to the main branch or when manually triggered, the current state of the RDF file (pcf-model.rdf) is processed. The Widoco tool is used to automatically create a structured, multilingual HTML documentation from the RDF ontology.

Afterwards, the contents of the docs folder are uploaded as an artifact and published through GitHub Pages. The publication process is fully automated and requires no additional manual steps. Any changes made to the RDF file or the repository will be automatically reflected on the published website shortly after.

The generated documentation can be accessed at the following URL:
https://cseaachengmbh.github.io/ontology/
Technical Details

    Build tool: Widoco

    Hosting platform: GitHub Pages

    Automation: GitHub Actions

Note

To update the published website, it is sufficient to make changes to the repository and push them to the main branch. Alternatively, the workflow can be triggered manually via the GitHub Actions interface.
