# IEO Quizzes

* [Quiz 1](#quiz-1)
* [Quiz 2](#quiz-2)
* [Quiz 3](#quiz-3)
* [Quiz 4](#quiz-4)
* [Quiz 5](#quiz-5)
* [Quiz 6](#quiz-6)

## Quiz 1

* Started on: Sunday, 7 April 2019, 8:36 PM
* Completed on: Sunday, 7 April 2019, 8:37 PM
* Time taken: 57 secs

### Question 1. High-throughput sequencing of nucleic acids

* a. allows one to partially profile the DNA, RNA and protein content of the cell.
* **b. allows one to uniformly profile the DNA and RNA content of the cell.**
* c. allows one to uniformly profile the DNA, RNA, protein and metabolite content of the cell.
* d. allows one to uniformly profile the DNA, RNA and protein content of the cell.
* e. allows one to partially profile the DNA and RNA content of the cell.

### Question 2. In a SummarizedExperiment object

* a. Phenotypic variables in the column data match sample names in the assay data.
* b. Row names in the assay data match the row names in the column data.
* **c. Sample column names in the assay data match the sample row names in the column data.**
* d. Phenotypic variables in the sample annotation match feature names in the assay data.
* e. Sample column names in the assay data match the sample row names in the row data.

### Question 3. The detection of RNA expression in whole blood through a high-throughput sequencing experiment depends on

* a. Only on how deep we sequence.
* b. The sample preparation protocol and how large is the sequencer.
* **c. The sample preparation protocol and how deep we sequence.**
* d. On the number of samples we sequence and how deep we sequence.
* e. Only on the sample preparation protocol.

### Question 4. A SummarizedExperiment object

* a. follows a matrix-like organisation with samples associated with rows and features with columns.
* **b. follows a matrix-like organisation with features associated with rows and samples with columns.**
* c. organises the data in a manner that is completely different to any other data structure.
* d. follows a vector-like organisation with features associated with rows and samples with columns.
* e. follows a vector-like organisation with samples associated with rows and features with columns.

### Question 5. When doing exome sequencing, the obtained reads should only map to

* a. known (protein) coding regions and promoter regions.
* b. known (protein) coding regions and introns.
* c. known and unknown (protein) coding regions.
* d. known introns.
* **e. known (protein) coding regions.**

## Quiz 2

* Started on: Monday, 15 April 2019, 9:00 AM
* Completed on: Monday, 15 April 2019, 9:03 AM
* Time taken: 3 mins 15 secs

### Question 1. The so-called batch effect precludes distinguishing the source of variation that drives the observed results

* **a. when is confounded with the outcome of interest in our experiment.**
* b. when the outcome of interest in our experiment is unclear.
* c. when is not confounded with the outcome of interest in our experiment.
* d. always.
* e. only when the data is published in high-impact journals.

### Question 2. RNA-seq data

* a. require a normalization pre-processing step due to the expression properties of the genes.
* b. require a normalization pre-processing step when most genes are not differentially expressed.
* c. require a normalization pre-processing step when most genes are differentially expressed.
* **d. require a normalization pre-processing step due to the expression properties of the samples.**
* e. do not require a normalization pre-processing step because are very accurate.

### Question 3. Estimating surrogate variables, with a method such as SVA, can help to

* a. adjust for the batch indicator variable.
* b. adjust for hidden (latent) non-biological factors only.
* **c. adjust for hidden (latent) biological and non-biological factors.**
* d. estimate a batch indicator variable.
* e. adjust for hidden (latent) biological factors only.

### Question 4. We read in an article that 30 genes were called differentially expressed (DE) at a FDR level of 10%. This means that

* a. only 30 genes had p-values smaller than 0.1.
* b. only 30 genes had p-values such that one could expect a maximum of 10% of true discoveries among them.
* c. only 30 genes had p-values larger than 0.1.
* d. only 30 genes had p-values smaller than 0.01.
* **e. only 30 genes had p-values such that one could expect a maximum of 10% of false discoveries among them.**

### Question 5. In a volcano plot...

* a. most significant gene expression changes are at both ends of the y-axis.
* **b. most significant gene expression changes are at the top of the y-axis.**
* c. most significant gene expression changes are at both ends of the x-axis.
* d. most significant gene expression changes are at the bottom of the y-axis.
* e. most significant gene expression changes are always highlighted in red.

## Quiz 3

* Started on: Monday, 13 May 2019, 7:24 AM
* Completed on: Monday, 13 May 2019, 7:26 AM
* Time taken: 1 min 56 secs

### Question 1. The design matrix of a linear model has:

* a. as many rows as variables of the model and as many columns as samples.
* b. as many rows as samples and as many columns as variables of model.
* **c. as many rows as samples and as many columns as coefficients of the model.**
* d. as many rows as coefficients of the model and as many columns as samples.
* e. as many rows as genes and as many columns as samples.

### Question 2. Under the null hypothesis of no-differential expression, the distribution of p-values calculated for all the genes should be:

* a. Independent.
* b. Skewed to the left.
* c. Normal (Gaussian).
* **d. Uniform.**
* e. Skewed to the right.

### Question 3. We have to analyze a RNA-seq data set of blood samples from patients before and after being treated with a specific drug. Therefore, we have one pair of samples per individual and we want to use a paired design. In a first exploratory analysis, we observe in an MDS plot an effect of the sex among the patients. Should be include sex as explanatory factor in the design matrix employed to conduct the differential expression analysis?

* a. Yes, because sex could affect the response of the patient to the drug.
* **b. No, because it's implicitly adjusted when comparing samples in pairs from the same individual.**
* c. No, because it gets automatically adjusted when using surrogate variable analysis.
* d. Yes, because we should always adjust for sex in any differential expression analysis.
* e. Yes, because according to the MDS plot, a fraction of the variability of the RNA-seq data can be attributed to the sex of the patients.

### Question 4. What is it measuring the first coefficient after the intercept in a design matrix that follows the reference model for a differential expression analysis with one binary explanatory variable?

* **a. The log fold-change between values of the explanatory variable associated with the coefficient.**
* b. The average expression of the explanatory variable.
* c. The fold-change between explanatory variable and the reference variable.
* d. The average expression for one of the values of the explanatory variable.
* e. The fold-change between values of the explanatory variable associated with the coefficient.

### Question 5. Functional annotations on genes are not...

* a. dynamic, annotations do not change over time.
* **b. evenly covering all organisms, some organisms have more annotations than others.**
* c. partial, there are annotations for every gene.
* d. noisy, annotations are always accurate.
* e. essential to downstream bioinformatic analyses.

## Quiz 4

* Started on:	Monday, 20 May 2019, 9:07 AM
* Completed on: Monday, 20 May 2019, 9:13 AM
* Time taken:	5 mins 44 secs

### Question 1 A study published by Ioannidis et al. in Nature Genetics in 2009 found out that out of 18 microarray gene-expression related papers only 2 were exactly reproducible. One the following reasons is not related to the lack of reproduciblity of they observed in the other 16 papers, which one?

* **a. Article was published in a low-impact journal.**
* b. Methods were unclear.
* c. Data were not avaiable.
* d. Different result was obtained.
* e. Software not available

### Question 2. In a functional enrichment analysis with the Fisher's exact test the number of gene sets with p-value < 0.05 can substantially increase when

* a. the total number of gene sets being tested is too high.
* b. the total number of genes condidered in the test is wrong and is too low.
* c. the total number of genes considered in the test is correct but is small.
* **d. the total number of genes considered in the test is wrong and is too high.**
* e. the total number of genes considered in the test is correct but is large.

### Question 3. The so-called GSEA-like methods for functional analysis are specially useful when

* a. there is enough biological variability that leads to a ranking of genes that correlates well with the phenotype.
* **b. there is limited biological variability that precludes finding statistically significant changes in gene expression.**
* c. there are lots of biological variability that lead to too many statistically significant changes in gene expression.
* d. there are genes that can be classified into gene sets.
* e. we have no clue about what to do with the data.

### Question 4. The simple GSEA method using a z-test is most sensitive for detecting gene sets

* a. whose genes are only down regulated.
* b. whose genes are only up regulated.
* **c. whose genes are either all up, or all down, regulated.**
* d. whose genes show a change in scale.
* e. whose genes are both up and down, regulated.

### Question 5. Assume we perform a Gene Ontology (GO) analysis using the Fisher's exact test on a list of differentially expressed (DE) genes and we find one GO term significantly enriched (p-value < 0.05). What does this mean?

* a. All DE genes are not random.
* b. The enriched GO term includes a subset of DE genes annotated to this GO term whose size does not exceed any expectation of finding such a number of DE genes by chance alone within that GO term.
* c. All genes in the enriched GO term are DE.
* d. All DE genes are functionally relevant to our experiment.
* **e. The enriched GO term includes a subset of DE genes annotated to this GO term whose size exceeds any expectation of finding such a number of DE genes by chance alone within that GO term.**

## Quiz 5

* Started on: Sunday, 26 May 2019, 7:04 PM
* Completed on:	Sunday, 26 May 2019, 7:05 PM
* Time taken: 1 min 30 secs

### Question 1. After mapping the reads from an RNA-seq experiment, the percentage of multi-mapping reads tell us something about:

* a. reads mapping to multiple annotated features from multiple loci in the genome.
* b. reads mapping to multiple loci from single annotated features.
* c. reads mapping to multiple genomes.
* **d. reads mapping to multiple loci in the genome.**
* e. reads mapping to multiple annotated features in the genome.

### Question 2. After mapping the reads from an RNA-seq experiment were samples were prepared with poly-A selection of RNA molecules we expect:

* a. a high percentage of chimeric reads.
* **b. a high percentage of uniquely mapping reads.**
* c. a high percentage of unmapped reads.
* d. a high percentage of multi-mapping reads.
* e. a high percentage of spliced-mapped reads.

### Question 3. The input of software to summarize RNA-seq sequence reads aligned to a reference genome into a table of counts, are:

* a. unsorted SAM files.
* b. unsorted BAM files.
* c. FASTQ files.
* **d. sorted and indexed BAM files.**
* e. sorted and indexed SAM files.

### Question 4. Select the correct sentence:

* **a. The LC/MS technique can measure only a subset of existing compounds.**
* b. Chromatograms separate compounds at different m/z ratio.
* c. There is no relation between metabolite reactions and gene expression.
* d. The human metabolome is known and finite.
* e. The metabolomics data processing workflow is as mature as genomics workflow.

### Question 5. Select the correct sentence. In discovery proteomics:

* **a. one uses fragmented spectra (MS2) to know the sequence of the peptides.**
* b. one uses non-unique peptides to quantify proteins.
* c. the identification of peptides is made using uniquely the exact mass of the peptide.
* d. the missing values are always due to the absence of the molecule.
* e. all peptides and proteins in the cell are seen in all the samples.