# Machine-learning-for-project-portfolios
Taking portfolio data and applying ML for insight. More material needs to be moved in here

The examples given so far are all low-code approaches so that portfolio managers can apply approaches themselves. 
I will add some of the approaches requiring code once tidied up.

Currently the approaches are conventional ML applied to project data from spreadsheets and relational databases.

I will be preparing some ML applied to project data taken from graph databases. 
This is to take advantage of the extra extra context provided by graph databases, specifically in terms of which relationships are meaningful. 

ML to be applied is different each level. 
Broadly speaking:

1. PROJECT & PROGRAMME level: node, edge and property prediction for risks, dependencies, project sectoral properties and success.

2. PORTFOLIO level: mostly standard network algorithms (centrality, breadth first search etc). Includes the conversion between graph and tree structures to provide appropriate views for different stakeholders. The ML element is currently restricted to identifying common and anomalous graph motifs.

3. TASK AND SCHEDULE level: This is the least well developed, but a broad range of approaches to making the most of the Optimisation work of Professor Warren B. Powell, making the most of the inherent graph structure of resource-task-outcome paths. 
Eventually exploring Graph-Graph neural networks & Seq-Seq/ Transformer approaches as well as Monte Carlo Tree search

4. PMO and CENTRE OF EXCELLENCE. NLP applied to boost taxonomic and semantic approaches to curating body of project practice for the orgranisation. 
