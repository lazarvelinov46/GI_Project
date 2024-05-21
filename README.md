Detecting spatially variable genes (SVG)

This is project for master course subject Computational Genomics.

Task description:

Propose and implement the algorithm for the detection of spatially variable genes. Test the algorithm on Mouse embryo 9.5 and Mouse brain samples that can be read to the Anndata object using the Scanpy library. The algorithm could be based on measuring the entropy or some other metrics for every gene across spatial coordinates and deciding whether the gene is SVG based on that metric(s).

Compare the results of the implemented algorithm with SpaGFT, the algorithm for detecting SVGs that can be considered ground truth. Report Confusion matrix, f-scores, and AUC metrics.

Create a PowerPoint (Google Slides) presentation explaining all the work being done and a video presentation publicly available on YouTube. Perform code versioning on the Github repository and provide the link to it.

Useful links:

Link for embryo sample: https://ftp.cngb.org/pub/SciRAID/stomics/STDS0000058/stomics/E9.5_E1S1.MOSTA.h5ad

Link for brain sample: https://ftp.cngb.org/pub/SciRAID/stomics/STDS0000058/stomics/Mouse_brain_cell_bin.h5ad

Link for anndata files description: https://anndata.readthedocs.io/en/latest/

Link for SpaGFT: https://www.biorxiv.org/content/biorxiv/early/2022/12/13/2022.12.10.519929.full.pdf

Link for YouTube presentation: https://youtu.be/66h_YrG9qtY
