# Publicly available low-sample size metagenomic sets
Datasets of the `Diease-sets-1`,`Diease-sets-2`, `CRC-Nation (five contries)`, and `CRC-stages`

## Table-1 | Summary of the human gut metagenomic datasets in this repo.
| Data Group                      | Reference                                                   | Dataset   | \# Case | \# Control | \# Species |
| ------------------------------- | ----------------------------------------------------------- | --------- | ------- | ---------- | ---------- |
| Disease-sets-1                  | PopPhy\-CNN and Meta-Singer, Reiman D. et al.<sup>1,2</sup> | Cirrhosis | 114     | 118        | 542        |
|                                 |                                                             | IBD       | 25      | 85         | 443        |
|                                 |                                                             | Obesity   | 164     | 89         | 465        |
|                                 |                                                             | T2D       | 223     | 217        | 606        |
|                                 |                                                             | CRC       | 48, 39  | 47         | 507        |
| Disease-sets-2                  | Met2Img, Nguyen H.et al.<sup>3,4</sup>                      | Cirrhosis | 118     | 114        | 542        |
|                                 |                                                             | IBD       | 25      | 85         | 443        |
|                                 |                                                             | Obesity   | 164     | 89         | 465        |
|                                 |                                                             | T2D       | 170     | 174        | 572        |
|                                 |                                                             | CRC       | 48      | 73         | 503        |
| Cross-nation sets of CRC-Nation | Wirbel, J. et al.<sup>5</sup>                               | AUS       | 46      | 63         | 849        |
|                                 |                                                             | CHN       | 74      | 54         | 849        |
|                                 |                                                             | DEU       | 60      | 60         | 849        |
|                                 |                                                             | FRA       | 53      | 61         | 849        |
|                                 |                                                             | USA       | 52      | 52         | 849        |
| Disease-stage sets of CRC-Stage | Yachida, S. et al.<sup>6</sup>                              | MP        | 40      | 127        | 7278       |
|                                 |                                                             | S0        | 27      | 127        | 7278       |
|                                 |                                                             | SI/II     | 69      | 127        | 7278       |
|                                 |                                                             | SIII/IV   | 54      | 127        | 7278       |




## 1. `Disease-sets-1`: 
The five metagenomic datasets in **Disease-sets-1** are Cirrhosis, Obesity, type 2 diabetes (T2D), inflammatory bowel disease (IBD) and colorectal cancer (CRC). The datasets were obtained from  the Meta-Signer[1, 2]. T

## 2. `Disease-sets-2`: 
The five metagenomic datasets in **Disease-sets-2** are Cirrhosis, Obesity, type 2 diabetes (T2D), inflammatory bowel disease (IBD) and colorectal cancer (CRC). The datasets were obtained from Met2Img[3, 4].


## 3. `CRC-Nation` 
The data covers 849 gut microbial species from fecal samples of 575 subjects (CRCs or healthy controls, CTRs) compiled by Wirbel et al. (2019)[5]. It contains five metagenomic datasets from five separate studies in five nations (FRA: France, AUS: Australia, DEU: Germany, CHN: China, USA: America). 

## 4. `CRC-Stage` 
The data is the each of the four CRC stages in pairwise comparisons against healthy controls, which was adapted from the study of Yachida et al. (2019) [6]. It consists of 317 subjects of the Japanese cohort with both metagenomic and metabolomic profiles, where 127 subjects are in the healthy stage, 40 subjects are in stage MP (multiple polypoid adenomas with low-grade dysplasia), 27 subjects are in stage S0 (intramucosal carcinoma polypoid adenoma with high-grade dysplasia), 69 subjects are in stage SI/II CRC, and 54 subjects are in stage SIII/IV CRC[4]. It originally covers a total of 8,367 gut microbial species, we removed the species with very low abundance values (smaller than 1e-8) by calculating the average relative abundance in each stage, leading to 7,278 species.

-------
## Reference
* [1]	Reiman, D., Metwally, A. A., Sun, J. & Dai, Y. PopPhy-CNN: a phylogenetic tree embedded architecture for convolutional neural networks to predict host phenotype from metagenomic data. IEEE J. Biomed. Health Inform. 24, 2993-3001 (2020).
* [2]	Reiman, D., Metwally, A. A., Sun, J. & Dai, Y. Meta-Signer: Metagenomic Signature Identifier based on Rank Aggregation of Features. bioRxiv (2020).
* [3]	Nguyen, T. H., Prifti, E., Chevaleyre, Y., Sokolovska, N. & Zucker, J.-D. Disease classification in metagenomics with 2d embeddings and deep learning. arXiv preprint arXiv:1806.09046 (2018).
* [4]	Nguyen, T. H., Prifti, E., Sokolovska, N. & Zucker, J.-D. Disease prediction using synthetic image representations of metagenomic data and convolutional neural networks. in 2019 IEEE-RIVF International Conference on Computing and Communication Technologies (RIVF).  1-6 (2019).
* [5]	Wirbel, J. et al. Meta-analysis of fecal metagenomes reveals global microbial signatures that are specific for colorectal cancer. Nat. Med. 25, 679-689 (2019).
* [6]	Yachida, S. et al. Metagenomic and metabolomic analyses reveal distinct stage-specific phenotypes of the gut microbiota in colorectal cancer. Nat. Med. 25, 968-976 (2019).



---

