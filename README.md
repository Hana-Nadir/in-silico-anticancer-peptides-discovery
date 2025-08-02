
# **In Silico Anticancer Peptides Discovery**

## **Project Overview**

This repository documents the in-silico analysis of peptides and secondary metabolites derived from the bacterial species *Lactococcus lactis* and *Streptomyces parvus*. The primary goal was to computationally identify and characterize novel therapeutic agents with potential anti-cancer properties, laying the groundwork for future experimental validation.

## **Methodology**

The research employed a multi-faceted computational approach, integrating various bioinformatics tools and machine learning models:

### **1\. Secondary Metabolite Identification**

The **antiSMASH** web server was used to perform a comprehensive analysis of the bacterial genomes. This tool was crucial for identifying, annotating, and characterizing biosynthetic gene clusters (BGCs) that are responsible for producing secondary metabolites.

### **2\. Antimicrobial Peptide (AMP) Discovery and Characterization**

Antimicrobial peptides were discovered and characterized using a multi-step process:

* **Prediction Tool**: The **CAMPR3** tool was utilized to predict potential AMPs from the identified biosynthetic genes. The process involved identifying a single longer AMP and subsequently deconstructing it into shorter, 20-amino acid AMPs.  
* **Characterization Models**: The identified peptides were characterized using a suite of custom-developed machine learning models to assess their potential as anticancer peptides (ACPs). The characterization was based on high-confidence prediction scores from the following models:  
  * **Support Vector Machine (SVM)**  
  * **Random Forest (RF)**  
  * **Artificial Neural Network (ANN)**  
  * **Discriminant Analysis (DA)**  
* **Input Features**: The SVM models were trained using various peptide features to ensure robust prediction, including:  
  * Amino Acid Composition  
  * Dipeptide Composition  
  * Binary Profiles

## **Key Findings**

The in-silico analysis successfully identified several promising secondary metabolites and peptides with significant anti-cancer potential.

### **Secondary Metabolites**

* **Beta-lactones**: Genes were identified that are associated with the biosynthesis of beta-lactones, a class of compounds known for their potent proteasome-inhibiting activity.  
* **RiPPs**: The research identified enzymes involved in the biosynthesis of Ribosomally Synthesized and Post-Translationally Modified Peptides, which are known to induce cell death by inactivating ribosomes.  
* **T3PKS**: Genes for Type III Polyketide Synthases were found, which produce polyketides that can interfere with cancer cell proliferation.  
* **RAS-RiPPs**: Radical S-adenosylmethionine (RaS) enzymes were identified, which are critical for producing bioactive RAS-RiPPs with direct cytotoxic effects.

### **Anticancer Peptides (ACPs)**

Several high-confidence AMPs were predicted and characterized, with notable examples including:

* A 99-amino acid AMP from the **TIPKS transcriptional regulator gene** in *Lactococcus lactis*, with exceptionally high probabilities from SVM (0.999) and Random Forest (0.934).  
* A 99-amino acid AMP from the **betalactone gene** in *Lactococcus lactis*, which was consistently and highly predicted by all four machine learning models.  
* A 90-amino acid AMP from a **terpene synthase protein** in *Streptomyces parvus*, which demonstrated some of the highest confidence scores (SVM: 1.00, RF: 0.93).

## **Next Steps**

The next phase of this research will focus on "activity-based anti-cancer peptide reconstruction and functional prediction." This will involve further computational analysis to validate the identified candidates, optimize their sequences, and predict their specific mechanisms of action, preparing them for potential in vitro and in vivo studies.
