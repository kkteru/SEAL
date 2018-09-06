SEAL -- learning from Subgraphs, Embeddings, and Attributes for Link prediction
===============================================================================

About
-----

Code for SEAL (learning from Subgraphs, Embeddings, and Attributes for Link prediction). SEAL is a novel framework for link prediction which systematically transforms link prediction to a subgraph classification problem. For each target link, SEAL extracts its *h*-hop enclosing subgraph *A* and builds its node information matrix *X* (containing latent embeddings and explicit attributes of nodes). Then, SEAL feeds (*A, X*) into a graph neural network (GNN) to classify the link existence, so that it can learn from both graph structure features (from *A*) and latent/explicit features (from *X*) simultaneously for link prediction.

Version
-------

SEAL is implemented in both MATLAB and Python. The MATLAB version was used to generate the experimental results in the paper, which also contains the evaluation code of other baseline methods. The Python software has better flexibility and scalability.

Reference
---------

If you find the code useful, please cite our paper:

    @article{zhang2018link,
      title={Link Prediction Based on Graph Neural Networks},
      author={Zhang, Muhan and Chen, Yixin},
      journal={arXiv preprint arXiv:1802.09691},
      year={2018}
    }

Muhan Zhang, Washington University in St. Louis
muhan@wustl.edu
9/5/2018