# Publicly available low-sample size metagenomic sets
Datasets of the `Diease-sets`, `CRC-Nation (five contries)`, and `CRC-stages`

## Table-1 | Summary of the human gut metagenomic datasets in this study

| Data Group                           | Dataset   | \# Case | \# Control | \# Species |
| ------------------------------------ | --------- | ------- | ---------- | ---------- |
| `Disease-sets`\[2\]                    | Cirrhosis | 114     | 118        | 542        |
| IBD                                  | 25        | 85      | 443        | 542        |
| Obesity                              | 164       | 89      | 465        | 542        |
| T2D                                  | 223       | 217     | 606        | 542        |
| CRC                                  | 48, 39    | 47      | 507        | 542        |
| Cross-nation sets of `CRC-Nation`\[3\] | AUS       | 46      | 63         | 849        |
| CHN                                  | 74        | 54      | 849        |849        |
| DEU                                  | 60        | 60      | 849        |849        |
| FRA                                  | 53        | 61      | 849        |849        |
| USA                                  | 52        | 52      | 849        |849        |
| Disease-stage sets of `CRC-Stage`\[4\] | MP        | 40      | 127        | 7278       |
| S0                                   | 27        | 127     | 7278       | 7278       |
| SI/II                                | 69        | 127     | 7278       | 7278       |
| SIII/IV                              | 54        | 127     | 7278       | 7278       |


## 1. `Disease-sets`: 
The five metagenomic datasets in Disease-sets are Cirrhosis, Obesity, type 2 diabetes (T2D), inflammatory bowel disease (IBD) and colorectal cancer (CRC). The datasets were obtained from  the MetAML package[1] and Meta-Signer[2]. The two sets of CRC metagenomic datasets are the across-nation CRC data (CRC-Nation sets) and CRC stage-specific data (CRC-Stage sets), which are obtained from recent study of Wirbel et al. (2019)[3] and Yachida et. al. (2019)[4], respectively. A summary of the datasets used in this study is in Table 1. The microbial taxa of all datasets are at species-level and with relative abundance value for the specific disease and control groups.

* 1) The Cirrhosis dataset covers 542 gut microbial species from fecal samples of 114 cirrhosis patients and 118 healthy subjects[5]. 
* 2) The T2D dataset covers 606 gut microbial species from fecal samples of 223 patients with T2D and 217 healthy subjects from two studies[6, 7]. 
* 3) The Obesity dataset covers 465 gut microbial species from fecal samples of 292 individuals of which 164 individuals with a BMI greater than 30 kg/m2 as obesity and 89 individuals with a BMI lower than 25 kg/m2 as control[8]. 
* 4) The IBD dataset covers 443 gut microbial species from fecal samples of 25 patients (21 had ulcerative colitis, and 4 had Crohn’s disease) and 85 healthy subjects[9]. 
* 5) The multiclass CRC dataset covers 507 gut microbial species from fecal samples of 134 subjects where 48 subjects had cancer, 39 had adenomas (26 subjects had small adenomas, 13 subjects had large adenomas) and 47 are healthy subjects[2, 10]. 

## 2. `CRC-Nation` 
The data covers 849 gut microbial species from fecal samples of 575 subjects (CRCs or healthy controls, CTRs) compiled by Wirbel et al. (2019)[3]. It contains five metagenomic datasets from five separate studies in five nations (FRA: France, AUS: Australia, DEU: Germany, CHN: China, USA: America). 

## 3. `CRC-Stage` 
The data is the each of the four CRC stages in pairwise comparisons against healthy controls, which was adapted from the study of Yachida et al. (2019) [4]. It consists of 317 subjects of the Japanese cohort with both metagenomic and metabolomic profiles, where 127 subjects are in the healthy stage, 40 subjects are in stage MP (multiple polypoid adenomas with low-grade dysplasia), 27 subjects are in stage S0 (intramucosal carcinoma polypoid adenoma with high-grade dysplasia), 69 subjects are in stage SI/II CRC, and 54 subjects are in stage SIII/IV CRC[4]. It originally covers a total of 8,367 gut microbial species, we removed the species with very low abundance values (smaller than 1e-8) by calculating the average relative abundance in each stage, leading to 7,278 species.

-------
## Reference
[1].	Pasolli, E., et al., Machine learning meta-analysis of large metagenomic datasets: tools and biological insights. PLoS computational biology, 2016. 12(7): p. e1004977.
[2].	Reiman, D., et al., Meta-Signer: Metagenomic Signature Identifier based on Rank Aggregation of Features. bioRxiv, 2020.
[3].	Wirbel, J., et al., Meta-analysis of fecal metagenomes reveals global microbial signatures that are specific for colorectal cancer. Nature medicine, 2019. 25(4): p. 679-689.
[4].	Yachida, S., et al., Metagenomic and metabolomic analyses reveal distinct stage-specific phenotypes of the gut microbiota in colorectal cancer. Nature medicine, 2019. 25(6): p. 968-976.
[5].	Qin, N., et al., Alterations of the human gut microbiome in liver cirrhosis. Nature, 2014. 513(7516): p. 59-64.
[6].	Qin, J., et al., A metagenome-wide association study of gut microbiota in type 2 diabetes. Nature, 2012. 490(7418): p. 55-60.
[7].	Karlsson, F.H., et al., Gut metagenome in European women with normal, impaired and diabetic glucose control. Nature, 2013. 498(7452): p. 99-103.
[8].	Le Chatelier, E., et al., Richness of human gut microbiome correlates with metabolic markers. Nature, 2013. 500(7464): p. 541-546.
[9].	Qin, J., et al., A human gut microbial gene catalogue established by metagenomic sequencing. nature, 2010. 464(7285): p. 59-65.
[10].	Zeller, G., et al., Potential of fecal microbiota for early‐stage detection of colorectal cancer. Molecular systems biology, 2014. 10(11): p. 766.

---

