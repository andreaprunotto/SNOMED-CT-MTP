# SNOMED-CT Multiple-Translation-Path approach
Supplementary Material of MIE conference paper "Automatic Generation of German Translation Candidates for SNOMED CT Textual Descriptions" (A. Prunotto, S. Schulz, and M. Boeker, IMBI Freiburg)

**Supp. Fig 1.** Consensus matrix of direct translations obtained with different MT tools (TPs on row and columns, number of common TCs in cells). The heatmap illustrates the number of FSNs direct translations that are found by any of two given TPs. Barplots on top and left represent the average concordance of one TP with all the others.

![Supp. Fig. 1](https://github.com/andreaprunotto/SNOMED-CT-MTP/blob/main/Heatmap_engines-sources.png)

**Supp. Fig 2.** Full consensus matrix, same structure as above, but using all 12 support languages and 91 TPs. 

![Supp. Fig. 2](https://github.com/andreaprunotto/SNOMED-CT-MTP/blob/main/heatmap_overall_StarterSet.png)


**Supp. Fig 3.** PCA of the full consensus matrix. Data is related to TCs of the SNOMED Starter Set, obtained by a MTP approach. The ellipses represent the areas that contain 95% of the TPs related to that engine. The higher concordance between Google and Deepl is confirmed by the intersection among Google (green) and Deepl (red) ellipses. The substantial separation of Systran individuals (blue) is an indication of a high amount of peculiar TCs found only by this engine.

![Supp. Fig. 3](https://github.com/andreaprunotto/SNOMED-CT-MTP/blob/main/PCA_overall.png)

**Supp. Fig 4.** Distribution of unique TCs obtained from each TP. The three central heatmaps show in colour those concepts (rows) which are translated in a unique way by means of a TP (columns). Notably, the higher the number words in a FSN (left-most plot), the higher the number of the related distinct TCs (right-most plot). In average, the MTP approach leads to an average of 20-30 distinct TCs for each FSN. As expected, the highest number of unique candidates is found throughout STs, whereas all the TCs obtained by DT are usually found by means of some other TP (a similar outcome is observed for those TPs involving Danish or English as support language). An exception is represented by TPs involving Systran, which provide the highest number of unique candidates. 

![Supp. Fig. 4](https://github.com/andreaprunotto/SNOMED-CT-MTP/blob/main/1_cand.png)

