# **Seabird nutrients reshape energy flow and productivity in coral reef food webs code and data**

**This repository contains code and data presented in the article**:
  
Authors (anonymized). Seabird nutrients reshape energy flow and productivity in coral reef food webs. 

 

## 1. How to download this project?

On the project main page on Anonymous GitHub, click on the button `Download Repository` and then extract the ZIP folder.



## 2. Description of the project

### 2.1 Project organization

This project is organized in 3 folders:
  
* :file_folder:	`data` folder contains 28 datasets and map files.
* :file_folder:	`code` folder contains two Rmd file (see **2.2 Code description**).
* :file_folder:	`figures` folder contains 2 subfolders (`main` and `supp`) for saving figures and one subfolder `silhouettes` containing 16 PNG files.

### 2.2 Code description

The _01_cnpflux.Rmd_ code if formatted in Rmarkdown and contains analyses to produce the `cnpflux_output.Rdata` dataframe. This dataframe is already included in the file_folder:	`data` folder given calculation time.

The _02_main.Rmd_ code is formatted in Rmarkdown and contains all R-based analyses and code to reproduce data and figures from the paper, including supplementary material. 
Following productivity calculations and the DAG, models and outputs are divided into the eight feeding groups described in the paper. The inset plots from Fig 2, S4 and S5 are also included.

## 3. Reproducibility parameters

R version 4.6.0 (2026-04-24 ucrt)
Platform: x86_64-w64-mingw32/x64
Running under: Windows 10 x64 (build 19045)

Matrix products: default
  LAPACK version 3.12.1

locale:
[1] LC_COLLATE=English_United Kingdom.utf8  LC_CTYPE=English_United Kingdom.utf8    LC_MONETARY=English_United Kingdom.utf8
[4] LC_NUMERIC=C                            LC_TIME=English_United Kingdom.utf8    

time zone: Indian/Mauritius
tzcode source: internal

attached base packages:
[1] grid      stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] lme4_2.0-6          Matrix_1.7-5        modelr_0.1.11       jtools_2.3.1        reshape2_1.4.5      piecewiseSEM_2.3.1 
 [7] lubridate_1.9.5     forcats_1.0.1       stringr_1.6.0       dplyr_1.2.1         purrr_1.2.2         readr_2.2.0        
[13] tidyr_1.3.2         tibble_3.3.1        tidyverse_2.0.0     cowplot_1.2.0       magick_2.9.1        gridExtra_2.3.1    
[19] brms_2.23.0         Rcpp_1.1.1-1.1      tidybayes_3.0.7     MixSIAR_3.1.12      simcausal_0.5.7     scales_1.4.0       
[25] ggpubr_1.0.0        ggdag_0.2.13        dagitty_0.3-4       plyr_1.8.9          ggrepel_0.9.8       ggplot2_4.0.3      
[31] ggspatial_1.1.10    ggplotify_0.1.3     raster_3.6-32       sp_2.2-3            sf_1.1-1            rnaturalearth_1.2.0

loaded via a namespace (and not attached):
  [1] RColorBrewer_1.1-3   tensorA_0.36.2.1     rstudioapi_0.19.0    jsonlite_2.0.0       magrittr_2.0.5       TH.data_1.1-5       
  [7] estimability_2.0.0   nloptr_2.2.1         farver_2.1.2         rmarkdown_2.31       ragg_1.5.2           fs_2.1.0            
 [13] vctrs_0.7.3          minqa_1.2.8          terra_1.9-34         rstatix_1.1.0        htmltools_0.5.9      distributional_0.8.1
 [19] curl_7.1.0           broom_1.0.13         Formula_1.2-6        gridGraphics_0.5-1   StanHeaders_2.32.10  parallelly_1.48.0   
 [25] KernSmooth_2.23-26   htmlwidgets_1.6.4    sandwich_3.1-3       emmeans_2.0.4        zoo_1.8-15           igraph_2.3.3        
 [31] lifecycle_1.0.5      pkgconfig_2.0.3      R6_2.6.1             fastmap_1.2.0        future_1.75.0        rbibutils_2.4.1     
 [37] digest_0.6.39        furrr_0.4.0          textshaping_1.0.5    labeling_0.4.3       timechange_0.4.0     abind_1.4-8         
 [43] compiler_4.6.0       proxy_0.4-29         pander_0.6.6         withr_3.0.3          inline_0.3.21        S7_0.2.2            
 [49] backports_1.5.1      carData_3.0-6        DBI_1.3.0            performance_0.17.1   QuickJSR_1.10.0      pkgbuild_1.4.8      
 [55] broom.mixed_0.2.9.7  ggsignif_0.6.4       MASS_7.3-65          rappdirs_0.3.4       classInt_0.4-11      loo_2.10.1          
 [61] tools_4.6.0          units_1.0-1          otel_0.2.0           glue_1.8.1           callr_3.8.0          DiagrammeR_1.0.12   
 [67] nlme_3.1-170         checkmate_2.3.4      generics_0.1.4       gtable_0.3.6         tzdb_0.5.0           class_7.3-23        
 [73] data.table_1.18.4    hms_1.1.4            tidygraph_1.3.1      car_3.1-5            pillar_1.11.1        ggdist_3.3.3        
 [79] yulab.utils_0.2.4    posterior_1.7.0      splines_4.6.0        lattice_0.22-9       survival_3.8-6       tidyselect_1.2.1    
 [85] knitr_1.51           reformulas_0.4.4     arrayhelpers_1.1-2   V8_8.2.0             stats4_4.6.0         xfun_0.57           
 [91] bridgesampling_1.2-1 matrixStats_1.5.0    rstan_2.32.7         MuMIn_1.48.19        visNetwork_2.1.4     stringi_1.8.9       
 [97] yaml_2.3.12          boot_1.3-32          evaluate_1.0.5       codetools_0.2-20     cli_3.6.6            RcppParallel_6.2.0  
[103] systemfonts_1.3.2    Rdpack_2.6.6         processx_3.9.0       globals_0.19.1       coda_0.19-4.1        svUnit_1.0.8        
[109] parallel_4.6.0       rstantools_2.7.0     assertthat_0.2.1     bayesplot_1.15.0     Brobdingnag_1.2-9    listenv_1.0.0       
[115] mvtnorm_1.3-7        e1071_1.7-17         insight_1.5.2        rlang_1.2.0          multcomp_1.4-31     


## 3. Reproducibility parameters
