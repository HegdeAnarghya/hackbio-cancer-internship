<!--StartFragment-->

**STAGE 1 TASK:  Summary of the paper “Multi-omic machine learning predictor of breast cancer therapy response”**

**Authors (@slack): Chairunnisa Amanda (@AmandaC), Bassam Elhamsa (@Bassam\_Elhamsa), Anarghya Hegde (@AnuHegde), Chioma Onyido (@Omabekee)**

**Introduction**

Therapy responses for breast cancer are influenced by the tumour ecology. Machine learning and multi-omic profiling improves personalised therapeutic strategies and response prediction. This study is aimed at identifying which tumour would react better to therapy and why. 

****![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXd-4NMt91Io5fep08XcJ036D2y17DOsX8XxwApSLX257AJKtmm44tm__GV10TnvPmOGYNjQN0Qh-OSlGTUX8jmhSrSr3SGFQNokw88WeZYmqR68LwIcr4dLjHEuTRGmY1ZZw0Vxo4Q6sc_nWTQsqIfXlq8o?key=e0Ey5E-E1J9wOhx_UejcnA)****

_Figure 1_: Overview of the study design

Pre-therapy breast tumours from 168 patients were profiled using DNA and RNA sequencing and digital pathology analysis. After patients underwent chemotherapy for about 18 weeks, findings revealed that 26% of patients had pathological complete response (pCR), while other patients had remaining cancer in varied degrees.

**Key Biological Features Identified**

They found that tumours attaining pCR had more neoantigens, higher mutation burdens and fewer subclonal mutations. Additionally, aggressive subtypes with higher pCR rates included TP53 and triple-negative mutant tumours. Loss of HLA class I genes increased the incidence of residual disease and decreased treatment response by impeding the presentation of neoantigens.

Tumours accomplishing pCR were found to over-express genes such as EGFR, CDKN2A and MYC whereas the tumours with residual disease had down-regulated immune pathways and epithelial-to-mesenchymal transition. Immunological signatures and tumour proliferation especially in lymphocytes were found to be correlated with pCR in case of HER2- tumours. Though certain immune dysfunctional tumours continue to be resistant to therapy, this illustrates the collective effect of an active immune microenvironment and rapid proliferation in determining treatment sensitivity and outcome prediction.

**Multi-omics integration and machine learning prediction of treatment response**

To predict the pCR to breast cancer therapy, six ensemble machine learning models were developed with different feature sets - clinical, molecular and digital pathology data incorporated (Figure 2). An external cohort of 75 patients yielded the highest accuracy (AUC 0.87) for the fully integrated model (Figure 3). Immune activity, gene expression, proliferation, lymphocyte density and age were top predictive features.

****![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfqASO2L3I0h0FTDdZkEswngXjeZg5k8jTkXvgYIbTozGczaaPt2pZDjwekzGPMmMRq1Wund7RvOp-D8Xh2wlaoNNjOJXtPCOVe8x2Ku7FAaEtuAxoRotco6cdsmJ679vWv74FEZl6G_C3BNB7udHiDIFQ?key=e0Ey5E-E1J9wOhx_UejcnA)****

_Figure_ 2: Schematic of the machine learning framework



****![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXedv4etmssoVGtw9E-y90K_CZ1H6tx7CIGUuXx7AZU-5aVfKs3095EE3HBmiiqR0azQAE3GFjE-r0pYl5stX3ZuGuONQZKdUzHZ-zKTcmz4fOMeenm-pKM3Syp6iJ2J3azZrYvUzT3C0VhSqRpDK5-QW6c9?key=e0Ey5E-E1J9wOhx_UejcnA)****

_Figure 3:_ AUCs for models obtained from the external validation cohorts

**Conclusion**

Although individual breast cancer features fail to make effective pCR prediction, a machine learning model integrative of all features accomplishes the possible accuracy, indicating the significance of comprehensive data in predicting therapy response.

**References**

1. Sammut, S. J., Crispin-Ortuzar, M., Chin, S. F., Provenzano, E., Bardwell, H. A., Ma, W., ... & Caldas, C. (2022). Multi-omic machine learning predictor of breast cancer therapy response. _Nature_, _601_(7894), 623-629.

\


<!--EndFragment-->
