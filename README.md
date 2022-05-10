# Polypharmacy side effect association network analysis
This is a project on network analysis which was done as a part of course network analysis and mining.

### Information Regarding the Dataset :- Polypharmacy side effect dataset
This is a network of polypharmacy side-effects. Nodes represent drugs and edges represent different types of side effects that are associated with drug pairs. Edges indicate which side effects a patient will likely experience if he takes two drugs together (i.e., a drug combination). Such side effects are known as polypharmacy side-effects, as they are associated with drug pairs (or higher-order drug combinations) and cannot be attributed to either individual drug in the pair (in a drug combination).   
  
### Problem Statement Identified from dataset  
Polypharmacy deals with use of multiple medications and their effects.   In this project we identify various types of side effects that occur by consuming multiple drugs that interact with each other by using graph analysis and prediction methodologies.

### Flow of project

1. Extracting the dataset form the snap dataset.
2. Converted the dataset into graph using networkx package.
3. Performed some eda like finding top side effects,drug causing the top side effects etc
4. Performed graph metrics like centrality measures.
5. Performed spectral clustering to identify the important communities.
6. Performed link prediction using traditional similarity based methods like jaccard,adamic adar and pefential attachment.
7. Performed link prediction usin graph ml technique (node2vec)
  
### Top Learning from the project 

1. Learned how to make use of the networkx package to create graph,perform centrality measures and perform spectral clustering.
2. Learnt about how traditional methods perform  link prediction and its performance measures.We saw jaccard coefficient and adamic adar were good models for the graph.
3. Explore modern neural methods of learning on graphs – representation learning and semi-supervised graph algorithms using neural techniques.
4. Explored node2vec model helping to perform node embedding and then perform a link prediction on it.

###Issues faced in the project
1. Wasn’t able to perform graph ml models like gcn,graphSAGE and GAT models in our project due to data not matching with the model requirements.
2. Most of models used are for node prediction but our main goal was to perform link prediction which set as a drawback to this project.
3. From various literature survey we found that the dataset that we choose was a part of huge directory called decagon which had resources that will help make a prediction of side effects based on drug-drug interaction,protein-drug interaction and protein-protein interactions.

### Conclusion
In conclusion our project was an exploration of modelling polypharmacy using various framework available in the python coding language. We successfully used our ideas to generate conclusions such as most common side effects and their spread within our network, highest centrality measures,clsutering of graphs and perform some traditional graph learning models. Working with the “ChSe Decagon” data set increased our confidence when working with large datasets to create solutions for unique problems and as a group feel like the experience has improved our ability for future projects that require the use of such data sets. To conclude we found this project interesting and a little bit challenging due to the new ideas presented. 


