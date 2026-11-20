Required Software:

R
> version
                          
platform       x86_64-w64-mingw32               
arch           x86_64                           
os             mingw32                          
crt            ucrt                             
system         x86_64, mingw32                  
status                                          
major          4                                
minor          5.2                              
year           2025                             
month          10                               
day            31                               
svn rev        88974                            
language       R                                
version.string R version 4.5.2 (2025-10-31 ucrt)
nickname       [Not] Part in a Rumble                            

Package Versions:
> sessionInfo()

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] tidybayes_3.0.7    lmerTest_3.2-1     lme4_2.0-1         Matrix_1.7-4       latex2exp_0.9.8    effectsize_1.0.1   performance_0.16.0
 [8] brms_2.23.0        Rcpp_1.1.1         lubridate_1.9.5    forcats_1.0.1      stringr_1.6.0      dplyr_1.2.0        purrr_1.2.1       
[15] readr_2.2.0        tidyr_1.3.2        tibble_3.3.1       ggplot2_4.0.2      tidyverse_2.0.0   

loaded via a namespace (and not attached):
 [1] svUnit_1.0.8          tidyselect_1.2.1      farver_2.1.2          loo_2.9.0             S7_0.2.1              fastmap_1.2.0        
 [7] tensorA_0.36.2.1      bayestestR_0.17.0     digest_0.6.39         timechange_0.4.0      lifecycle_1.0.5       StanHeaders_2.32.10  
[13] magrittr_2.0.4        posterior_1.6.1       compiler_4.5.2        rlang_1.1.7           tools_4.5.2           yaml_2.3.12          
[19] knitr_1.51            bridgesampling_1.2-1  pkgbuild_1.4.8        RColorBrewer_1.1-3    abind_1.4-8           numDeriv_2016.8-1.1  
[25] withr_3.0.2           grid_4.5.2            stats4_4.5.2          datawizard_1.3.0      inline_0.3.21         scales_1.4.0         
[31] MASS_7.3-65           insight_1.4.6         cli_3.6.5             mvtnorm_1.3-3         rmarkdown_2.30        reformulas_0.4.4     
[37] generics_0.1.4        RcppParallel_5.1.11-2 rstudioapi_0.18.0     tzdb_0.5.0            parameters_0.28.3     minqa_1.2.8          
[43] rstan_2.32.7          splines_4.5.2         bayesplot_1.15.0      parallel_4.5.2        matrixStats_1.5.0     vctrs_0.7.1          
[49] boot_1.3-32           arrayhelpers_1.1-2    hms_1.1.4             ggdist_3.3.3          glue_1.8.0            nloptr_2.2.1         
[55] codetools_0.2-20      distributional_0.6.0  stringi_1.8.7         gtable_0.3.6          QuickJSR_1.9.0        pillar_1.11.1        
[61] htmltools_0.5.9       Brobdingnag_1.2-9     R6_2.6.1              Rdpack_2.6.6          evaluate_1.0.5        lattice_0.22-7       
[67] rbibutils_2.4.1       backports_1.5.0       rstantools_2.6.0      coda_0.19-4.1         gridExtra_2.3         nlme_3.1-168         
[73] checkmate_2.3.4       xfun_0.56             pkgconfig_2.0.3 

Execution:
The main R file is Bayesian_multilevel_Cohens_d.Rmd containing all executable code. The folder "data" contains the original raw dataset from 
(Edelsbrunner et al., 2024) as well as the results of the limited Monte Carlo simulation study. The folder "graphics" contains all graphics
from the publication, and the folder "models" contains the pre-sampled ANOVA models.