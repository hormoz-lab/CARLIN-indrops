This is a fork of the main inDrops pipeline developed by the Klein lab. For standard inDrops runs, please use the code there: https://github.com/indrops/indrops

The code here should only be used if you prepared a CARLIN library using inDrops. In this case, this inDrops fork should be invoked with the additional argument `--no_clean_barcodes` which stores QC information for CBs and UMIs in the header line of each FASTQ read. This information is later used in the CARLIN pipeline for denoising CBs and UMIs.

If you use this code, _please cite the original inDrops paper_.
