# Gaussian-Processes-for-Topology-Inference-of-Directed-Graphs
implementation of Gaussian Processes for Topology Inference of Directed Graphs, with MATLAB and Python implementation and test cases shown in the following paper:

@INPROCEEDINGS{9909923,
  author={Cui, Chen and Banelli, Paolo and Djurić, Petar M.},
  booktitle={2022 30th European Signal Processing Conference (EUSIPCO)}, 
  title={Gaussian Processes for Topology Inference of Directed Graphs}, 
  year={2022},
  volume={},
  number={},
  pages={2156-2160},
  keywords={Network topology;Time series analysis;Directed graphs;Gaussian processes;Machine learning;Signal processing;Topology;topology inference;Gaussian processes;causal-ity;ARD kernel},
  doi={10.23919/EUSIPCO55093.2022.9909923}}

main.ipynb: The workflow of the code.
            Contains:  Data processing, Inference, Plot(haven't done yet).

dataProcessing.ipynb:  Given the graph signal from t=1 to t=T, with considered \Lambda lag, output the training input and output.

Inference.ipynb: Given the input and output, the inference process of the graph topology.





