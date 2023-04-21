# slca-ontology

SemanticLCA is a simple OWL ontology focused on representing buildings in several use cases in conjuction
with their environmental impacts which are evaluated using Life Cycle Assessment methods.

The ontology is designed in several modules which are interconnected:

- Building module - represents buildings with its elements and materials
- District module - represents city districts as collections of multiple buildings
- Sensing module - represents sensing equipment within a building
- Scenario module - represents metadata on managing different input/output configurations for external simulation tools which work on building data
- State module - represents metadata on different states in time for a built asset physically and virtually
- LCA module - represents Life Cycle Assessment concepts
- Weighting module - represents methods to consider LCA results as different indexes

Each module is intended to be coupled with different specialised domain ontologies.

The current version of the ontology is not final, and represents work in progress by the SemanticLCA project consortium.

You can directly import to Protégé a merged ontology file using this raw link:
https://raw.githubusercontent.com/bojecp/slcao/main/owl/slca.owl

# about SemanticLCA

The SemanticLCA research project is an international collaboration effort between the Luxembourg
Institute of Science and Technology and Cardiff University to tackle interoperability between built enviornment assets (buildings in particular)
under various use cases for Life Cyle Assessment (LCA).

One of the key project outcomes is the SLCA-ontology, which is published here.

# project funding

The authors would like to acknowledge the financial support of the Fonds National de la Recherche (FNR) 
in Luxembourg and the Engineering and Physical Sciences Research Council (EPSRC) in the UK 
under grant agreement (INTER/UKRI/19/14106247; EP/T019514/1) for the SemanticLCA research project

## License

Licensed under the [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).