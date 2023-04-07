# DP_CI
Here are the experiments for the paper: Confidence Intervals for Private Query Processing

Input data are stored in bank_marketing.csv adult.csv and HepPh.txt.

For experiments on median CI:
  
  Synthetic.ipynb describes results on synthetic datasets
  
  medianCI.ipynb describes the results on real datasets
  
Ladder.ipynb describes experiments on graph counting queries, the ladder functions are calculated according to https://dl.acm.org/doi/pdf/10.1145/2723372.2737785

Residual.ipynb describes the experiments on TPC-H queries, the residual sensitivities are calculated according to https://dl.acm.org/doi/pdf/10.1145/3448016.3452813

meanCI.ipynb describes the experiments for mean CI.

DrawFigures.ipynb draws the figures used in the paper.
