# pytorch_geometric_cs224w_2023
Solving some of the google colabs from Stanford's course CS224W Machine Learning With Graphs.

Slides and colab notebooks (2023): http://web.stanford.edu/class/cs224w/

Youtube videos of the lectures (2021): https://www.youtube.com/playlist?list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn

Colabs:
- Colab 2: 
  - Creating a GNN for node property prediction (using GCNConv layers).
  - Creating a GNN for graph property prediction (extending the previous GNN architecture, that computes node embeddings, to compute a graph embedding).
  - Training and evaluation loops using Pytorch.
  - GCNConv was first described in: https://arxiv.org/abs/1609.02907
- Colab 3:
  - Implementing GraphSAGE GNN layer from "scratch", translating the mathematical equations that explain the message and aggregation steps into code.
  - GraphSAGE was first described in: https://arxiv.org/abs/1706.02216
- Colab 4:
  - Implementing GAT (graph attention) GNN layer from "scratch", similarly to Colab 3.
  - Consideration of multi-head attention in the GAT message passing layer implementation.
  - Included numerical example of the attention weights calculation.
  - GAT was first described in: https://arxiv.org/abs/1710.10903
