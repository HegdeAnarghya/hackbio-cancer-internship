**The Cancer Genome Atlas (TCGA): An introduction to its association with ML (Machine Learning)**

Also known as the “Living Legacy for Cancer Research”, the TCGA is an open-source database that maps the genomic profiles of around 33 cancer types and subtypes ranging from breast and bladder to uterine and pancreatic. The database also reveals the associated molecular features linked to cancer, giving all the cancer researchers a common platform to access the information. It has transformed the research on the molecular pathways underlying cancer since it eased the process of assembling bits of data obtained from various cancer associated biological processes.

In cancer research, early detection and prognosis have become essential so as to subsequently help with the clinical management of patients. Due to the significance of categorizing cancer patients into low- and high- risk groups, numerous research teams are investigating the use of machine learning (ML) techniques.

The importance of machine learning technologies is demonstrated by their capacity to identify key features from intricate datasets. In cancer research, a range of methods such as Bayesian Networks (BNs), artificial Neural Networks (ANNs), Decision Trees (DTs) and Support Vector Machines (SVMs) have been extensively used to create predictive models that enable precise and efficient decision-making. While it’s clear that applying machine learning techniques can help understand how cancer progresses, these techniques need to be efficiently validated before they could be considered for routine clinical setting.

Below are some studies conducted using the TCGA data in association with ML algorithms:

<!--[if !supportLists]-->1.     <!--[endif]-->TCGA team obtained the non-differentiated stem cells and their differentiated progenitors’ data from public repositories and two classes of markers were built that would indicate genetic and epigenetic expression features of the cells. Then, a variant of “one-class logistic regression” was utilized to categorize the various TCGA samples as per their degree of differentiation, which is a key feature for the development of tumour \[1].

<!--[if !supportLists]-->2.     <!--[endif]-->A study used the copy number, expression and mutation data to predict the stimulation of Ras pathway and if the RNAseq expression data was involved in the path activation \[2].

<!--[if !supportLists]-->3.     <!--[endif]-->A study utilized Convolutional Neural Networks (CNN) to map tumour infiltrating lymphocytes (TIL) on the basis of eosin and haematoxylin images \[3].

The establishment of informatics architecture and its application in various classification and feature selection algorithms in conjunction with the integration of multi-dimensional data might yield promising tools for predictions in cancer domain.

 

**References:**

\[1] Malta, T. M., Sokolov, A., Gentles, A. J., Burzykowski, T., Poisson, L., Weinstein, J. N., ... & Schumacher, S. E. (2018). Machine learning identifies stemness features associated with oncogenic dedifferentiation. Cell, 173(2), 338-354.

\[2] Liñares-Blanco, J., Pazos, A., & Fernandez-Lozano, C. (2021). Machine learning analysis of TCGA cancer data. PeerJ Computer Science, 7, e584.

\[3] Saltz, J., Gupta, R., Hou, L., Kurc, T., Singh, P., Nguyen, V., ... & Danilova, L. (2018). Spatial organization and molecular correlation of tumor-infiltrating lymphocytes using deep learning on pathology images. Cell reports, 23(1), 181-193.
