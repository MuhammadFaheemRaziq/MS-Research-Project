**Prioritizing gut microbial SNPs linked to immunotherapy outcomes in NSCLC patients by integrative bioinformatics analysis**

**Overview**

This repository contains all computational workflows, analyses, and findings from my MS research project, which investigates the role of the gut microbiome in shaping immunotherapy response in non-small cell lung cancer (NSCLC) patients. The study integrates metagenomics, machine learning, and structural bioinformatics to identify microbial strains and genomic variations linked to immune checkpoint inhibitor (ICI) therapy outcomes.

**Research Objectives**

The primary objectives of this research were:

1. To identify specific microbial species and strains associated with treatment response.
2. To identify gut microbial genomic variations from the associated strains in NSCLC patients undergoing ICI therapy.
3. To develop machine learning models capable of prioritizing the identified SNPs from microbial genomic variations in responder (R) and non-responder (NR) patients.
4. To assess the functional impact of prioritized SNPs through structural bioinformatics approaches.

**Dataset**

The study used publicly available metagenomes from 87 NSCLC patients who were treated with nivolumab, an ICI therapy. The samples were collected at three different time points:

T0 (before treatment)
T1 (early response phase)
T2 (later response phase or disease progression)

These metagenomic datasets were analyzed to track microbial composition changes and genetic variations associated with treatment response.

**Research Methodology**

The study followed a multi-step computational pipeline involving different bioinformatics and statistical approaches:

1. **Data Preprocessing**

Raw metagenomic sequences underwent quality control and preprocessing to ensure reliable downstream analysis. This included removing low-quality reads and sequencing artifacts.

2. **Taxonomic Profiling and Strain Identification**

1. To investigate the gut microbiome’s role in immunotherapy response, we:
2. Identified microbial strains present in the gut metagenomes of NSCLC patients.

Focused on high-confidence species profiled in responders and non-responders.

3. **Variant Calling and Annotation**

We analyzed single nucleotide polymorphisms (SNPs) and other genomic variations in microbial strains to explore potential genetic differences between responders and non-responders. Key findings included:

1. Certain microbial species, such as _Lachnospira eligens_, were found exclusively in responders.
2. Other species, such as _Parabacteroides distasonis_, were found only in non-responders.

4. **Statistical Association Analysis**

To assess whether microbial variations were significantly linked to treatment response, we applied statistical modeling to detect meaningful associations between microbial genes and clinical outcomes. This helped in identifying specific microbial SNPs that might serve as potential biomarkers for treatment response.

5. **Machine Learning-Based SNP Prioritization**

To predict treatment response based on microbial SNPs, we developed and evaluated multiple machine learning models. The best-performing model, Logistic Regression, achieved:

1. Over 90% accuracy in distinguishing responders from non-responders.
2. Area under the ROC curve (AUC-ROC) > 95%, indicating a strong predictive ability.

The key predictive SNPs identified included:

1. Ala168Val (lpdA) in Phocaeicola dorei
2. Tyr233His, Leu330Ser (lpdA) in Parabacteroides distasonis
3. His233Arg (obgE) in Parabacteroides distasonis

These SNPs showed a strong correlation with patients' immunotherapy response and could be useful in developing personalized treatment strategies.

6. Structural Bioinformatics Analysis

To understand the functional impact of prioritized SNPs, we performed structural bioinformatics analyses, including:

1. Protein stability prediction to determine how mutations affect protein function.
2. Active site analysis to examine whether SNPs altered critical regions of microbial proteins.

Findings revealed that some SNPs affected substrate binding sites or led to reduced protein stability, which could impact bacterial metabolism and, consequently, host immune interactions.

**Key Findings & Results**

1. Strain-specific variations were identified in the gut microbiome of NSCLC patients undergoing ICI therapy.
2. Genomic differences in microbial strains were associated with responders and non-responders.
3. Machine learning models successfully distinguished responders from non-responders with high accuracy.
4. Structural bioinformatics analysis provided insights into how specific microbial SNPs might alter bacterial protein function and, in turn, impact immunotherapy outcomes.

**Significance of the Study**

This research highlights the potential of the gut microbiome as a biomarker for predicting response to immunotherapy in NSCLC patients. By integrating metagenomics, statistical modeling, and machine learning, this study provides a robust framework for developing personalized microbiome-based interventions in cancer treatment.

**Future Directions**

1. Validation with larger cohorts: Expanding the study to a broader population will strengthen the findings.
2. Exploring longitudinal microbiome dynamics: Understanding how the microbiome changes over time during treatment.
3. Developing a clinical prediction tool: Using microbial SNPs to guide personalized immunotherapy strategies.

**Author & Contact**

Researcher: Muhammad Faheem Raziq
Institution: Metagenome Discovery Lab/SINES/National University of Sciences & Technology H-12 Islamabad, Pakistan
Email: faheemraziq1999@gmail.com

The research paper has been published for this work and can be found at "https://doi.org/10.1186/s12967-025-06370-0".
