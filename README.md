# Using Multiple Aggregation Functions with GraphSAGE
## Original Code Author: William Leif

- Basic reference TensorFlow implementation of [GraphSAGE]
(https://github.com/williamleif/GraphSAGE).
- Original PyTorch implementation of [GraphSAGE]
(https://github.com/williamleif/graphsage-simple/).

## Requirements
- python >= 3.10.8 is required to run.
- pytorch >= 1.13.0 is also required. This can be installed by running `conda install pytorch`.
- run `pip -r requirements.txt` to install all required dependencies.

## Running examples
From 'Machine-Learning-Project', run one of the following:
- To test one aggregator combination, enter `python -m graphsage.model aggr1 aggr2` where aggr1 and aggr2 can be either `mean` or `max`.
- To test every aggregator combination, enter `python -m graphsage.model all`, this will print a table with the F1-Score for every combination in this experiment.
- Bash scripts to run each combination are provided for reference and convenience. 
