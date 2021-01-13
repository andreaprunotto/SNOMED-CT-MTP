# SNOMED-CT Multiple-Translation-Path approach



Supplementary Material of MIE conference paper *Automatic Generation of German Translation Candidates for SNOMED CT Textual Descriptions*, A. Prunotto, S. Schulz, and M. Boeker, IMBI Freiburg.


**Schematic illustration of various MT strategies.** White labels=source languages, yellow=target; cylinders=MT tools. **A** Classical MT approach. **B** Multiple engines approach. **C** Multiple Translation Path (MTP) approach.

![Supp. Fig. 1](https://github.com/andreaprunotto/SNOMED-CT-MTP/blob/main/schemes_of_translations_methods.png)

**Consensus matrix of direct translations obtained with different MT tools.** The matrix is defined by assigning TPs on row and columns, and then placing the number of TCs found in common among any TPs couple in the cells. Barplots on top and left represent the average consensus of one TP with all the others.

![Supp. Fig. 1](https://github.com/andreaprunotto/SNOMED-CT-MTP/blob/main/Heatmap_engines-sources.png)

**Full consensus matrix.** Same structure as above, but using all 12 support languages, for a total of 91 TPs. 

![Supp. Fig. 2](https://github.com/andreaprunotto/SNOMED-CT-MTP/blob/main/heatmap_overall_StarterSet.png)


**PCA of the full consensus matrix.** Data is related to TCs of the SNOMED Starter Set, obtained by a MTP approach. The ellipses represent the areas that contain 95% of the TPs related to that engine. The higher concordance between Google and Deepl is confirmed by the intersection among Google (green) and Deepl (red) ellipses. The substantial separation of Systran individuals (blue) is an indication of a high amount of peculiar TCs found only by this engine.

![Supp. Fig. 3](https://github.com/andreaprunotto/SNOMED-CT-MTP/blob/main/PCA_overall.png)

**Distribution of unique TCs obtained from each TP.** The three central heatmaps show in colour those concepts (rows) which are translated in a unique way by means of a TP (columns). Notably, the higher the number words in a FSN (left-most plot), the higher the number of the related distinct TCs (right-most plot). In average, the MTP approach leads to an average of 20-30 distinct TCs for each FSN. As expected, the highest number of unique candidates is found throughout STs, whereas all the TCs obtained by DT are usually found by means of some other TP (a similar outcome is observed for those TPs involving Danish or English as support language). An exception is represented by TPs involving Systran, which provide the highest number of unique candidates. 

![Supp. Fig. 4](https://github.com/andreaprunotto/SNOMED-CT-MTP/blob/main/1_cand.png)

**Distribution of TCs multiplicity.** The heatmap displays the number of FSNs whose *n*-th candidate (*n* in rows) has a multiplicity *m* (columns). For instance, the topleft cell of the heatmap assesses that there are 221 FSNs whose first candidate (column 1 from left) has a multiplicity of 6 (first row from top).

![Supp. Fig. 4](https://github.com/andreaprunotto/SNOMED-CT-MTP/blob/main/multiplicity.png)

