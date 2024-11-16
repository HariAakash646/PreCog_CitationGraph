# PreCog_CitationGraphAnalysis
Repository containing all my files and reports for the Citation Grph Analysis task.

## Analysis
The cells of the .ipynb file can be run in order to view all th plots. A few lines of code can be toggled between commented/uncommented to include/exclude nodes with no dates. If the nodes are included, a date greater than the maximum date in the graph is assigned to them.

## Node2Vec
This folder contans the .ipynb file to train the node embeddings. The cells of this file can be run in order. It is ideal for the .ipynb notebook to run on a GPU. 

## Community Detection
The cells of the .ipynb files can be run in order to form the communities and create files labeling nodes according to their communities. Before running the file the .keras file containing the Node2Vec model and the node_id.json file need to uploaded to the working directory of the .ipynb file. Some changes in the file paths mentioned in the .ipynb may need to be made.

## Visualization
This folder contains the trained node embeddings and files clustering the nodes into communities. Any pair of these files can be uploaded into https://projector.tensorflow.org/ to visualize the communities.

## LinkPrediction
Running the cells of the .ipynb file allows us to train a link predictor model usng the node embeddings we previously trained. The .keras file containing the trained embeddings and node_id.json need to be uploaded to the working directory.  Some changes in the file paths mentioned in the .ipynb may need to be made. The .ipynb file will train and save a link predictor model.




