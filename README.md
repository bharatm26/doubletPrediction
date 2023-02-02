# DoubletsPrediction_v2

This repo includes use of three different doublet prediction approches `Chord`, `DoubletFinder`, and `scDblFinder` using `SCT` and `RNA` assays in single sample (NOT INTEGRATED). After different comparisions of SCT assay doublets, it was noted that the predicted doublets were not consistent among `DoubletFinder`, and `scDblFinder`. We proceeded with `RNA` assay for doublet prediction. Further, it was noted that `Chord` utilizes `DoubletFinder`, `cxds`, and `bcds` to improve the doublet prediction.

Links:

Chord: https://github.com/13308204545/Chord

scDblFinder: https://github.com/plger/scDblFinder

DoubletFinder: https://github.com/chris-mcginnis-ucsf/DoubletFinder

The Input data for this analysis is at: /data/project/U_BDS/pipeline_dev_space/sample_runs_data/scRNA-seq/secondary_analysis_outputs