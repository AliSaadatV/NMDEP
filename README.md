# From mutation to degradation: predicting nonsense-mediated mRNA decay with NMDap

## Highlights

- **Integrative model** (optimized rule-based heuristics + deep sequence embeddings + curated biological features) for continuous NMD activity prediction.
- **Benchmarks** of aggregation strategies from token embeddings to sequence predictions (AggFirst, AggLast, DeepSets; mean/max/sum/token; Alt vs Alt–Ref).
- **Explainability** to discover known and novel NMD determinants. 
- **Genome-wide inference** for almost **3 million** SNVs causing stop-gain on canonical transcripts. All of the predictions are available in the NMDap_predictions folder. If needed to binarize (NMD escape or not), we recommend using the threshold of 0.65 (values below 0.65 are predicted to escape NMD).

## Paper

NMDap paper is available [here](https://arxiv.org/abs/2502.14547).

## Data

Data can be accessed [here](https://zenodo.org/records/15100891).
