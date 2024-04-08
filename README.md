# 

# Safety, effectiveness, and skin immune response in a controlled human infection model of sand fly transmitted cutaneous leishmaniasis.
Vivak Parkash<sup>1</sup>, Helen Ashwin<sup>1</sup>, Shoumit Dey<sup>1</sup>, Jovana Sadlova<sup>2</sup>, Barbora Vojtkova<sup>2</sup>, Katrien Van Bocxlaer<sup>1,3</sup>, Rebecca Wiggins<sup>1</sup>, 
David Thompson<sup>4</sup>, Nidhi Sharma Dey<sup>1</sup>, Charles L. Jaffe<sup>5</sup>, Eli Schwartz<sup>6</sup>, Petr Volf<sup>2</sup>, Charles J. N. Lacey<sup>1</sup>, 
Alison M. Layton<sup>1,3,^</sup> and Paul M. Kaye<sup>1,3,^</sup>

<sup>1</sup>York Biomedical Research Institute, Hull York Medical School, University of York, York, UK<br>
<sup>2</sup>Department of Parasitology, Faculty of Science, Charles University, Viničná 7, Prague, Czech Republic<br>
<sup>3</sup>Skin Research Centre, Hull York Medical School, York, UK <br>
<sup>4</sup>York and Scarborough Teaching Hospitals NHS Foundation Trust, York, UK  <br>
<sup>5</sup>Department of Microbiology and Molecular Genetics, Kuvin Center for the Study of Infectious and Tropical Diseases, IMRIC, The Hebrew University – Hadassah Medical School, Jerusalem, Israel<br>
<sup>6</sup>The Center for Geographic Medicine and Tropical Diseases, Chaim Sheba Medical Center, and The School of Medicine, Tel Aviv University, Israel.<br>
<br>

#### <sup>^</sup>Corresponding authors: paul.kaye@york.ac.uk and alison.layton@hyms.ac.uk<br>
<br>
### Summary: <br>
The leishmaniases are globally important parasitic diseases for which no human vaccines are currently available. To facilitate vaccine development, we established a controlled human infection model of sand fly-transmitted cutaneous leishmaniasis caused by L. major. The primary objective was to demonstrate effectiveness (attack rate) and safety, whereas secondary objectives focused on defining immune responses in the developing lesion. We exposed 14 participants to infected sand flies and estimated an attack rate of 64%, rising to 82% for participants with confirmed bites. Lesion development was terminated by therapeutic biopsy, with three participants receiving adjunctive cryotherapy. No severe or serious adverse events were recorded, and all participants were lesion-free at long-term (>12 month) follow up.  Analysis of skin biopsies using spatial transcriptomics generated the first comprehensive map of cytokine/chemokine expression in human CL lesions, revealing discrete immune niches.  This controlled human infection model offers opportunities for rapid vaccine candidate selection and a greater understanding of immune-mediated protection and pathology.<br>

## Software requirements: <br/>

### OS
- Tested on Windows: Windows 10 x64 (For all R based code)<br/>
Code will however run on Mac and Linux operating systems as well<br/>

### Software <br/>


#### 1. R version 4.2.2
#### 2. RStudio 2022.02.3+492 (Optional)
#### 3. Package versioning required - see session information below; attached as sessionInfo() of attached packages

R version 4.2.2 (2022-10-31 ucrt)
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows 10 x64 (build 19045)

Matrix products: default

locale:
[1] LC_COLLATE=English_United Kingdom.utf8  LC_CTYPE=English_United Kingdom.utf8    LC_MONETARY=English_United Kingdom.utf8
[4] LC_NUMERIC=C                            LC_TIME=English_United Kingdom.utf8    

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] reshape2_1.4.4         corrplot_0.92          dplyr_1.0.10           sqldf_0.4-11           RSQLite_2.2.20         gsubfn_0.7            
 [7] proto_1.0.0            EnhancedVolcano_1.16.0 ggrepel_0.9.2          ggplot2_3.4.2          SeuratObject_4.1.3     Seurat_4.3.0          

loaded via a namespace (and not attached):
  [1] Rtsne_0.16             colorspace_2.0-3       deldir_1.0-6           ellipsis_0.3.2         ggridges_0.5.4         rstudioapi_0.14       
  [7] spatstat.data_3.0-0    farver_2.1.1           leiden_0.4.3           listenv_0.9.0          bit64_4.0.5            fansi_1.0.3           
 [13] codetools_0.2-18       splines_4.2.2          cachem_1.0.6           knitr_1.41             polyclip_1.10-4        jsonlite_1.8.4        
 [19] ica_1.0-3              cluster_2.1.4          png_0.1-8              uwot_0.1.14            shiny_1.7.4            sctransform_0.3.5     
 [25] spatstat.sparse_3.0-0  compiler_4.2.2         httr_1.4.6             Matrix_1.5-3           fastmap_1.1.0          lazyeval_0.2.2        
 [31] limma_3.54.0           cli_3.6.0              later_1.3.0            htmltools_0.5.4        tools_4.2.2            igraph_1.3.5          
 [37] gtable_0.3.1           glue_1.6.2             RANN_2.6.1             Rcpp_1.0.9             scattermore_0.8        vctrs_0.5.1           
 [43] nlme_3.1-161           spatstat.explore_3.0-5 progressr_0.13.0       lmtest_0.9-40          spatstat.random_3.0-1  xfun_0.36             
 [49] stringr_1.5.0          globals_0.16.2         mime_0.12              miniUI_0.1.1.1         lifecycle_1.0.3        irlba_2.3.5.1         
 [55] goftest_1.2-3          future_1.30.0          MASS_7.3-58.1          zoo_1.8-11             scales_1.2.1           promises_1.2.0.1      
 [61] spatstat.utils_3.0-1   parallel_4.2.2         RColorBrewer_1.1-3     yaml_2.3.6             memoise_2.0.1          reticulate_1.27       
 [67] pbapply_1.6-0          gridExtra_2.3          stringi_1.7.8          BiocParallel_1.32.5    chron_2.3-58           rlang_1.1.1           
 [73] pkgconfig_2.0.3        matrixStats_0.63.0     evaluate_0.19          lattice_0.20-45        ROCR_1.0-11            purrr_1.0.0           
 [79] tensor_1.5             labeling_0.4.2         patchwork_1.1.2        htmlwidgets_1.6.1      cowplot_1.1.1          bit_4.0.5             
 [85] tidyselect_1.2.0       parallelly_1.33.0      RcppAnnoy_0.0.20       plyr_1.8.8             magrittr_2.0.3         R6_2.5.1              
 [91] generics_0.1.3         DBI_1.1.3              withr_2.5.0            pillar_1.9.0           fitdistrplus_1.1-8     survival_3.5-0        
 [97] abind_1.4-5            sp_1.5-1               tibble_3.1.8           future.apply_1.10.0    crayon_1.5.2           KernSmooth_2.23-20    
[103] utf8_1.2.2             spatstat.geom_3.0-3    plotly_4.10.1          rmarkdown_2.19         grid_4.2.2             data.table_1.14.6     
[109] blob_1.2.3             digest_0.6.31          xtable_1.8-4           tidyr_1.2.1            httpuv_1.6.7           munsell_0.5.0         
[115] viridisLite_0.4.1      tcltk_4.2.2 

#### 4. RUNNING TIME: All R files run sequentially will take approximately 2 hours to run on a windows computer with 64GB RAM on a 8 core 3.00GHz machine (eg. processor Intel(R) Core(TM) i7-9700 CPU)
All code files, directory structure and instructions are available at https://github.com/jipsi/chim/ 

#### 5. Additional files required for running code available on [10.5281/zenodo.10018477](https://zenodo.org/records/10018477)

## Code to review/analyse the data and/or to replicate the figures in the manuscript 

#### 1. Code will attempt to create folder structure as shown in the repository. Please maintain folder structure as per the repository for the plots/Rds files to save in the correct folders (there is no need to create these folders manually). Download all Rds files from [10.5281/zenodo.10018477](https://zenodo.org/records/10018477) to your working folder as further mentioned in the following steps.

#### 2. To see how the data is normalised, integrated and clustered please look at prepare_rds.Rmd. However the raw data will be made available upon publication but please use <b>'Option 2'</b> below and the rds file link below to load the integrated data for inspection, analysis or re-creating figures. All instructions and R source files (.Rmd files) are available at https://github.com/jipsi/chim 

##### Option1 : Start from scratch using raw 10x files (GSE record is currently private, but please contact the authors for access via a token. GSE record will be made public upon publication)
- Download all samples/10x files from GSE263298 into V*/'sample_name'/ ie a folder named
- Start with prepare_rds.Rmd
- This file will take approximately 2 hours to run from start to finish on a windows computer with 64GB RAM on a 8 core 3.00GHz machine (eg. processor Intel(R) Core(TM) i7-9700 CPU)

##### Option2 : Start from prepared Rds containing primary clustering analysis
- Download Rds partial_dims_15_res_0.3_LC_cohort1.Rds, lesion_core_dims_10_res_0.2.rds and lesion_core_cyto_only_dims_10_res_0.5.Rds from [10.5281/zenodo.10018477](https://zenodo.org/records/10018477) into your working directory
- Start with downstream_analysis.Rmd
- Please run individual chunks to first loading Seurat objects, then proceeding to re-plot figures in the manuscript. Each chunk and the individual lines indicates which panel is being plotted
- PDF/CSV files are created within a folder named as 'R' or 'R\markers' in your working directory when the code is executed. If the folders are already present, the code will simply ignore it with a warning
- This file will take approximately 10-15 minutes to run from start to finish on a windows computer with 64GB RAM on a 8 core 3.00GHz machine (eg. processor Intel(R) Core(TM) i7-9700 CPU)

#### 6. Cell2location: Generating q05_cell_abundance_w_sf_barcoded.csv
#### Cell2location v0.1 (https://cell2location.readthedocs.io/en/latest/) was run by following the instructions as per the tool's tutorial for [mapping lymph nodes](https://cell2location.readthedocs.io/en/latest/notebooks/cell2location_tutorial.html). The code was run on University of York's HPC, namely, Viking using GPU node with 1 GPU, 1 node utilising 40GB RAM in approximately 2.5 hours. 1 hour for reference modelling and 1.5 hours for modelling the spatial data to calculate cell abundances in Visium spots 
- Cell2location was installed in its own environment as per the instructions in the link above
- Annotated single cell data (10.1126/science.aba6500) and RAW spatial data (this study, GSE263298) was used as input to cell2location
- Output was stored as a model.pt file and anndata file containing q05 abundances as metadata
- Python scripts were submitted to a job manager (slurm) on the HPC as a shell script with the following batch parameters and script

> #!/bin/bash
> #SBATCH --job-name=XXXX
> #SBATCH --mail-type=END
> #SBATCH --mail-user=shoumit.dey@york.ac.uk
> #SBATCH --ntasks=1
> #SBATCH --cpus-per-task=1
> #SBATCH --mem=40gb
> #SBATCH --time=04:00:00
> #SBATCH --output=sd22.5.1.log
> #SBATCH --account=XXXX
> #SBATCH --partition=gpu
> #SBATCH --gres=gpu:1
> 
> module load system/CUDA/10.0.130
> module load lang/Miniconda3/4.9.2
> 
> source activate cell2loc_env2
> 
> command -v python
> 
> python config.py
> 
> source deactivate
- Python code used is available on request. Running this will require RAW data which will be available on publication.
- integrated_downstream.Rmd file in this repository uses q05_cell_abundance_w_sf_barcoded.csv this to analyse cell type abundances in spatial spots

## License

### This project is covered under the <b>MIT License</b>.
