# QuantileKL
# Language: Python
# Input: TXT
# Output: DAT
# Tested with: PluMA 1.1, Python 3.6

PluMA plugin that runs Transformer model with Quantile-based cumulative Kullback-Leibler divergence (Sunoj et al, 2018)

The plugin expects as input a tab-delimited file of keyword-value pairs:
datadirectory   Directory for NPY files
datasetname     Output directory
metainformation JSON file
modelconfig     JSON file
trainconfig     JSON file

