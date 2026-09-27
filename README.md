# CCAMC Fine-Grained Source Corpus

Data-only release associated with *Tracing the Evolution of Oracle Bone Characters Across Three Millennia*. This repository publishes source-corpus records and documentation; model source code is not included.

## Download

- [CCAMC source corpus archive](https://github.com/Fulcrum-XAI/MSEF-data/releases/latest/download/ccamc-fine-grained-v1.0.tar.gz)
- Machine-readable occurrence tables and summary statistics are in [`metadata/`](metadata/).
- [Dataset source and rights](DATA_RIGHTS.md) describes provenance and the status of third-party material.

The archive contains 158,620 source occurrences across six CCAMC script categories, with cached source pages and linked source images. Occurrences are distinct from unique characters, artifacts, and images. Original source labels and provenance are retained.

This package is the CCAMC source-corpus component. It does not contain the derived FGCCES cross-era correspondences, survival annotations, engineered feature files, or character-disjoint train/validation/test splits used in the paper’s experiments. The source corpus alone must not be treated as those derived labels.
