# Import data labellisée 
## Group LLM in only one category and human in second category
## separate train dataframe and test data frame with the same ratio of label
## Preprocess label encoder and supress column with no interest

# Create a Tokenizer
## before that supress, once for all, all backLine from dataset
## preprocess function to create token in each line of dataframe text column
## finally preprocess function in order to endly create an embbedding matrix and with help of tokenizer adjacency matrix

# Adjacency matrix
## with spacy help we link a word node to its children word previously turn to tokens. this for each text rows in dataframe
## A trainidx2graph is preprocessed in order to prepare in use for adj matrix and training loop

# Model
## as we shown a graph for each line of text category is ready to be created
## we use first a GAT2VCnv Graph attention network to keep model memory
## Then we apply deux Graph Convolution Layer and activation batch normalization and dropout as far as graph technology concerned
