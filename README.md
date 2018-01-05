# sci2017_analysis
Data and analysis codes for Matson et al. 2017 manuscript
[**The commensal microbiome is associated with anti-PD-1 efficacy in metastatic melanoma patients**](http://science.sciencemag.org/content/359/6371/104). Please refer to READMEs in `Data` and `Notebook` sub-directory for more detailed information of the files. Description of how the OTU and shotgun species abundance tables are generated from raw FastQ files are provided in the supplementary methods section of the manuscript.


## Contents
* [Data](data/)
<br>Processed `biom` or `csv` data files used in 16S, shotgun, and qPCR analyses.
   * human_16S.sampleinfo.csv
   * human_16S.even13190.abs.sig.csv
   * human_16S.even13190.rel.sig.csv
   * human_16S.even13190.stats.sig.csv
   * human_16S.even13190.abs.full.biom
   * human_16S.even13190.rel.full.biom
   * human_16S_qPCR.csv
   * human_shotgun.rel.full.csv
   * human_joint_evidence.csv
   * mouse_16S.sampleinfo.csv
   * mouse_16S.even22560.abs.sig.csv
   * mouse_16S.even22560.rel.sig.csv
   * mouse_16S.even22560.abs.full.biom
   * mouse_16S.even22560.rel.full.biom


* [Notebook](notebook/)
<br>Jupyter notebooks that provide custom codes and input/output to reproduce relevant portion of analysis. 
   * 01_OTU_heatmap.ipynb
   * 02_qPCR_score.ipynb
   * 03_OTU_ratio.ipynb
   * 04_16S_shotgun_cor.ipynb
   * 05_Joint_evidence.ipynb
   * assets
