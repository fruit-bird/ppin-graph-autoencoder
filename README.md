# ppin-prediction

## Process
- [ ] Building the graph
  - [ ] Get PPIN data from somewhere
  - [ ] Get amino acid sequence + GO:funcs for each protein in the graph
    - [ ] Find the embedder that takes them both as input
    - [ ] Create embeddings
  - [ ] Combine embeddings with the graph
- [ ] Graph Analysis
  - [ ] Centrality, density...
  - [ ] Look for clusters and what they indicate
  - [ ] t-SNE plot of the embeddings
- [ ] Building the model
  - [ ] Try GAE, VGAE, or any link prediction GNN model
  - [ ] Use a GNN explainer model to optimize for large computations
  - [ ] Validate the model
- [ ] Finalizing the project
  - [ ] Interface the code out to an API
    - [ ] Publish the package
  - [ ] Look into deploying the model
  - [ ] Create a story with the data using [streamlit](https://streamlit.io)

## Viable Data Sources
- [STRING](https://string-db.org/)
- [BioGRID](https://thebiogrid.org/)
- [IntAct](https://www.ebi.ac.uk/intact/)
- [HINT (Human Interactome)](http://hint.yulab.org/)
- [HIPPIE (Human Integrated Protein-Protein Interaction rEference)](http://cbdm-01.zdv.uni-mainz.de/~mschaefer/hippie/)
- [Pathway Commons](http://www.pathwaycommons.org/)
