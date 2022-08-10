# ICDAR2019_cTDaR
The ICDAR 2019 cTDaR is to evaluate the performance of methods for table detection (TRACK A) and table recognition (TRACK B). For the first track, document images containing one or several tables are provided. For TRACK B two subtracks exist: the first subtrack (B.1) provides the table region. Thus, only the table structure recognition must be performed. The second subtrack (B.2) provides no a-priori information. This means, the table region and table structure detection has to be done. 

Official website: https://cndplab-founder.github.io/cTDaR2019


Important Note: 
1. For the modern dataset no training data is available for Track B. Note that the modern dataset has a different annotation (Bounding box of the content describes a cell region in contrast to the historical dataset whereas a cell region is described by the cell area) and thus a different requested output. 
2. Samples from the modern dataset have the prefix "cTDaR_t1" and samples from the historical dataset start with "cTDaR_t0". 

Update Note：

1. We publish a supplement dataset version in [ICDAR2019_cTDaR_dataset_supplement](https://github.com/cndplab-founder/ICDAR2019_cTDaR_dataset_supplement), which is a helpful subset in terms of adjacency relations, from <strong>Prof. Cheng-Lin Liu's Group, Institute of Automation, Chinese Academy of Sciences</strong>. 
