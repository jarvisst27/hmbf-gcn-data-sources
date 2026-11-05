# HMBF-GCN Reference Data Sources

This index links to three public datasets used in the HMBF-GCN study. Access the data through the original providers and cite the original studies when reusing them.

| Dataset | Role in the study | Source |
| --- | --- | --- |
| Breast Invasive Carcinoma (TCGA, Nature 2012) | Clinical annotations used to curate breast cancer subtype labels for the primary analysis | [cBioPortal clinical data](https://www.cbioportal.org/study/clinicalData?id=brca_tcga_pub) |
| Breast Invasive Carcinoma (TCGA, PanCancer Atlas) | Clinical annotations used to curate breast cancer subtype labels for the primary analysis | [cBioPortal clinical data](https://www.cbioportal.org/study/clinicalData?id=brca_tcga_pan_can_atlas_2018) |
| MOAEAM breast cancer (BRCA) dataset | The 875-sample dataset used for comparison with published multi-omics results | [Zhao et al.'s processed data](https://github.com/ZhaoShuMins/MOAEAM/tree/a9bb1e4e573d3b6bf396cabdd54a14701ae88093/data_5k) |

For the MOAEAM comparison, the five BRCA folds are [BRCA1](https://github.com/ZhaoShuMins/MOAEAM/tree/a9bb1e4e573d3b6bf396cabdd54a14701ae88093/data_5k/BRCA1), [BRCA2](https://github.com/ZhaoShuMins/MOAEAM/tree/a9bb1e4e573d3b6bf396cabdd54a14701ae88093/data_5k/BRCA2), [BRCA3](https://github.com/ZhaoShuMins/MOAEAM/tree/a9bb1e4e573d3b6bf396cabdd54a14701ae88093/data_5k/BRCA3), [BRCA4](https://github.com/ZhaoShuMins/MOAEAM/tree/a9bb1e4e573d3b6bf396cabdd54a14701ae88093/data_5k/BRCA4), and [BRCA5](https://github.com/ZhaoShuMins/MOAEAM/tree/a9bb1e4e573d3b6bf396cabdd54a14701ae88093/data_5k/BRCA5). HMBF-GCN used mRNA expression in this comparison.

The cBioPortal links provide source clinical annotations. The final filtered 1,047-sample RNA-seq expression matrix is outside the scope of this index.
