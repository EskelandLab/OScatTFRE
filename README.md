Code to accompany paper Thang et al., 2026 "Proteome-wide Multi-omics Profiling of Osteosarcoma Transcription Factor Networks"
[Journal of Molecular Biology](https://doi.org/10.1016/j.jmb.2026.169959)
A preprint of this manuscript can be found in [bioRxiv](https://doi.org/10.64898/2026.03.29.714917)

## R Code
All analysis has been performed in [R](r-project.org). 
## Figure 1 and S1
Comparisons of TF motif design and [CiiiDER](https://ciiider.erc.monash.edu/) predictions. Figure 1B-D and supplemental figure 1B-E "1.catTFFRE_design_CiiDER_Final"

## Figure 2 and S2
Proteomics analysis of catTFRE in osteosarcoma cell lines: "2.catTFRE_rHOS_MG63_U2OS_Final" .
We also analysed two pulldowns together: "3.OS_catTRFE_C1C4_Final"
## Figure 3 and S3
We utilized [PANDA](https://netzoo.github.io/zooanimals/panda/) to analyse generegulatory networks of catTFRE TFs: "4.OS_pandaR_C1_Final."
## Figure 4 and S4
We utilized [DESeq2](https://bioconductor.org/packages//release/bioc/html/DESeq2.html) for analysis of RNAseq in osteosarcoma cell lines "5.RNAseq_OS_FINAL_RAW_DESeq2"
Integrative analysis of transcription factor gene regulation, chromatin accessibility and enhancer/promoter regulation was performed with [ANANSE](https://github.com/vanheeringen-lab/ANANSE): "6.ANANSE_DMSO_analysis"
"6.OS_ChIPseq_RNAseq_ATACseq_ANANSE_multiomics_bashscript"
