**Materials and Method:** 

**In silico Peptide Selection and Anticancer Activity Prediction:**

This study employed an activity-based peptide reconstruction and functional prediction approach to identify novel anticancer peptides derived from Phytoene synthase and Lycopene cyclase proteins. The CAMPR3 database served as a platform for peptide selection. This approach aimed to discover peptides with potentially enhanced therapeutic efficacy against cancer.

Following selection, the identified peptides were analyzed using the antiCP1 web server( [https://webs.iiitd.edu.in/raghava/anticp/submission.php](https://webs.iiitd.edu.in/raghava/anticp/submission.php) ) .This specialized tool utilizes machine learning algorithms to predict the anticancer activity of peptides based on their amino acid sequences and structural features. Specifically, the ACP/AMP Dataset: \-1 model and SVM score were prioritized during the peptide redesign process. These parameters served as key criteria for selecting peptides for further analysis and functional prediction.

Upon submission to antiCP1, the server generated predictions regarding the peptides' anticancer potential, including scores and mutation data. These predictions provided valuable insights into the likelihood of the peptides exerting cytotoxic effects on cancer cells or inhibiting tumor growth. This information was used to guide the selection of the most promising candidates for further investigation.

**Result:**

This study involved a thorough computational analysis of putative antimicrobial peptides (AMPs). The primary methodology employed was the Support Vector Machine (SVM) algorithm, which was used to predict the antimicrobial activity of these peptides.

The table below provides a comprehensive overview of predicted anticancer peptides derived from various proteins. Each peptide is assessed based on its sequence, potential mutations, and a calculated SVM score. A higher SVM score indicates a higher probability of the peptide exhibiting anticancer activity.

PD101,PD102,and PD103 are derived from cetyl-CoA carboxylase biotin carboxylase.PD101 is non-mutant with a moderate SVM score of 0.34. A single mutation in PD102 has significantly increased the SVM score to 0.76 . This suggests that the specific mutation has enhanced the peptide's anticancer properties.PD103 Mutant With multiple mutations, this peptide shows the higher SVM score of 1.18.

PD104,PD105,and PD106 derived from AMP-binding enzyme.Similar to PD101, PD104 has a moderate score of 0.69. It may be worth exploring its potential through modifications.PD105 with a single mutation on position 7 slightly increased the SVM score to 0.78.With multiple mutations, PD106 has a higher SVM score of 1.16, indicating strong anticancer potential.

PD107,PD108, and PD109 all derived from GntR family transcriptional regulator. PD107 has a high SVM score of 0.88, suggesting inherent anticancer activity.PD108 which has single mutation gave a SVM score of 0.98 .PD109 has the highest SVM score of 1.22, indicating very strong anticancer potential.

PD110 , PD111, and PD112 those peptide from hydroxymethylglutaryl-CoA synthase . PD110 Non-mutant has a moderate SVM score of 0.81 . PD111 is a mutant with a slight increase in SVM score to 0.89. PD112 is a mutant with multiple mutations, this peptide has a high SVM score of 1.19 .

PD113, PD114, and PD115 from the AraC family transcriptional regulator. PD113 is non-mutant, this peptide has a moderate SVM score of 0.81 . PD114 result in  a slight increase in SVM score to 0.90 suggests that the mutation may enhance the peptide's anticancer properties. PD115 mutant with multiple mutations, this peptide has a high SVM score of 1.22, indicating strong anticancer potential.

PD116, PD117, and PD118 are from  the LysR family transcriptional regulator. PD116 non-mutant has a SVM score of 0.85 . PD117 mutant  with SVM score of  0.97 suggests that the mutation may enhance the peptide's anticancer properties. PD118  a peptide with multiple mutations, has a high SVM score of 1.20, indicating strong anticancer potential.

PD119 , PD120 ,and PD121 derived from  the Radical SAM superfamily . PD119 has a moderate SVM score of 0.62. PD120 has a SVM score of 0.74. PD121 this peptide has a high SVM score of 1.13, indicating strong anticancer potential.

PD122, PD123, and PD124 from a transcriptional regulator . PD122  has a SVM score of 0.64. PD123 has a SVM score of 0.74.  PD124 this peptide has a highier SVM score of 1.14, indicating strong anticancer potential.

PD125, PD126, and PD127 from YcaO cyclodehydratase, PD125 is non-mutant with a high SVM score of 0.91, indicating strong anticancer potential, PD126 is mutant, a slight increase in SVM score to 0.98 suggests that the mutation may enhance the peptide's anticancer properties, PD127 with multiple mutations, this peptide has a high SVM score of 1.20.

Peptides with SVM scores above 1.0, particularly those from PD103, PD106, PD109, PD112, PD115, PD118, PD121, PD124, and PD127, are strong candidates for further investigation.

These findings have profound implications for the field of antimicrobial research. By employing computational methods to predict the antimicrobial activity of peptides derived from Phytoene synthase and Lycopene cyclase proteins, we can expedite the discovery of novel therapeutic agents. Furthermore, the diverse array of mutations observed in these peptides highlights the significance of exploring natural protein sequences for novel antimicrobial candidates. Our study contributes to the ongoing endeavor to develop alternative anticancer therapies by elucidating the potential of these derived peptides.

 




|  PROTEINS |  PREDICTED AMP WITHIN PEPTIDES |  |  |  |  AMP PROBABILITY |  |  |  |  |  |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
|  |  |  **PEPTIDE ID** |  **PEPTIDES** |  |  | **NO OF MUTATION** | **MUTATED** |  **MUTATION POSITION** |  **PREDICTION SCORE (SVM)** |  **PREDICTION** |
| cetyl-CoA carboxylase biotin carboxylase |  GYPVMIKAALGGGGRGMRVA  | PD101 | [GYPVMIKAALGGGGRGMRVA](https://webs.iiitd.edu.in/raghava/anticp/pepsearch1.php?seq=GYPVMIKAALGGGGRGMRVA&thval=0.0) |  |  | 0 | NON-MUTANT | 0 | 0.34 | ANTICP |
|  |  | PD102 | FYPVMIKAALGGGGRGMRVA |  |  | 0 | MUTANT | 1 | 0.76 | ANTICP |
|  |  | PD103 | FEPVRLEACKGGGGRGMRVA |  |  | 6 | MUTANT | 5 | 1.18 | ANTICP |
| AMP-bindi ng enzyme |  LLSELGIKKSDKVIIFKSSA  | PD104 | LLSELGIKKSDKVIIFKSSA |  |  | 0 | NON-MUTANT | 0 | 0.69 | ANTICP |
|  |  | PD105 | LLSELGEKKSDKVIIFKSSA |  |  | 0 | MUTANT | 7 | 0.78 | ANTICP |
|  |  | PD106 | LRFVCGEKCKDKVIIFKSSA |  |  | 6 | MUTANT | 2 | 1.16 | ANTICP |
| GntR family transcripti onal regulator |  IVFNIKKEITKGILDVGDKI  | PD107 | IVFNIKKEITKGILDVGDKI |  |  | 0 | NON-MUTANT | 0 | 0.88 | ANTICP |
|  |  | PD108 | IEFNIKKEITKGILDVGDKI |  |  | 0 | MUTANT | 2 | 0.98 | ANTICP |
|  |  | PD109 | FEFACEEECTKGILDVGDKI |  |  | 6 | MUTANT | 9 | 1.22 | ANTICP |
| hydroxyme thy lglutaryl-C oA synthase |  AAIAFHTPYTKMGKKALLPM  | PD110 | AAIAFHTPYTKMGKKALLPM |  |  | 0 | NON-MUTANT | 0 | 0.81 | ANTICP |
|  |  | PD111 | [AAIAFHTCYTKMGKKALLPM](https://webs.iiitd.edu.in/raghava/anticp/pepsearch1.php?seq=AAIAFHTCYTKMGKKALLPM&thval=0.0) |  |  | 0 | MUTANT | 9 | 0.89 | ANTICP |
|  |  | PD112 | [AEPCCETCCTKMGKKALLPM](https://webs.iiitd.edu.in/raghava/anticp/pepsearch1.php?seq=AEPCCETCCTKMGKKALLPM&thval=0.0) |  |  | 6 | MUTANT | 4 | 1.19 | ANTICP |
| AraC family transcriptio nal regulator |  ALLLLKQVVKMCYFNNKVTK  | PD113 | [ALLLLKQVVKMCYFNNKVTK](https://webs.iiitd.edu.in/raghava/anticp/pepsearch1.php?seq=ALLLLKQVVKMCYFNNKVTK&thval=0.0) |  |  | 0 | NON-MUTANT | 0 | 0.81 | ANTICP |
|  |  | PD114 | [ALLLLKQSVKMCYFNNKVTK](https://webs.iiitd.edu.in/raghava/anticp/pepsearch1.php?seq=ALLLLKQSVKMCYFNNKVTK&thval=0.0) |  |  | 0 | MUTANT | 8 | 0.90 | ANTICP |
|  |  | PD115 | [KLLVVLGSVVMCYFNNKVTK](https://webs.iiitd.edu.in/raghava/anticp/pepsearch1.php?seq=KLLVVLGSVVMCYFNNKVTK&thval=0.0) |  |  | 6 | MUTANT | 5 | 1.22 | ANTICP |
| LysR family transcriptio nal regulator |  AIKDIEVEVDLSLFQRSSKG  | PD116 | [AIKDIEVEVDLSLFQRSSKG](https://webs.iiitd.edu.in/raghava/anticp/pepsearch1.php?seq=AIKDIEVEVDLSLFQRSSKG&thval=0.0) |  |  | 0 | NON-MUTANT | 0 | 0.85 | ANTICP |
|  |  | PD117 | [AEKDIEVEVDLSLFQRSSKG](https://webs.iiitd.edu.in/raghava/anticp/pepsearch1.php?seq=AEKDIEVEVDLSLFQRSSKG&thval=0.0) |  |  | 0 | MUTANT | 2 | 0.97 | ANTICP |
|  |  | PD118 | [FEPCIEEEVCLSLFQRSSKG](https://webs.iiitd.edu.in/raghava/anticp/pepsearch1.php?seq=FEPCIEEEVCLSLFQRSSKG&thval=0.0) |  |  | 6 | MUTANT | 7 | 1.20 | ANTICP |
| Radical SAM superfamil y |  AVRGKGTFESAIKSVALLVK  | PD119 | [AVRGKGTFESAIKSVALLVK](https://webs.iiitd.edu.in/raghava/anticp/pepsearch1.php?seq=AVRGKGTFESAIKSVALLVK&thval=0.0) |  |  | 0 | NON-MUTANT | 0 | 0.62 | ANTICP |
|  |  | PD120 | [AVRGCGTFESAIKSVALLVK](https://webs.iiitd.edu.in/raghava/anticp/pepsearch1.php?seq=AVRGCGTFESAIKSVALLVK&thval=0.0) |  |  | 0 | MUTANT | 5 | 0.74 | ANTICP |
|  |  | PD121 | [ARFCCETECSAIKSVALLVK](https://webs.iiitd.edu.in/raghava/anticp/pepsearch1.php?seq=ARFCCETECSAIKSVALLVK&thval=0.0) |  |  | 6 | MUTANT | 6 | 1.13 | ANTICP |
| transcriptio nal regulator |  LQRSVGHISQKVLTQHLRAL  | PD122 | [LQRSVGHISQKVLTQHLRAL](https://webs.iiitd.edu.in/raghava/anticp/pepsearch1.php?seq=LQRSVGHISQKVLTQHLRAL&thval=0.0) |  |  | 0 | NON-MUTANT | 0 | 0.64 | ANTICP |
|  |  | PD123 | [LQRSVGHISKKVLTQHLRAL](https://webs.iiitd.edu.in/raghava/anticp/pepsearch1.php?seq=LQRSVGHISKKVLTQHLRAL&thval=0.0) |  |  | 0 | MUTANT | 10 | 0.74 | ANTICP |
|  |  | PD124 | [LQPCCEECSKKVLTQHLRAL](https://webs.iiitd.edu.in/raghava/anticp/pepsearch1.php?seq=LQPCCEECSKKVLTQHLRAL&thval=0.0) |  |  | 6 | MUTANT | 6 | 1.14 | ANTICP |
| YcaO cyclodehy drat ase |  VLCIGYGSKKCIGLGTSTQI  | PD125 | [VLCIGYGSKKCIGLGTSTQI](https://webs.iiitd.edu.in/raghava/anticp/pepsearch1.php?seq=VLCIGYGSKKCIGLGTSTQI&thval=0.0) |  |  | 0 | NON-MUTANT | 0 | 0.91 | ANTICP |
|  |  | PD126 | [VLCIGEGSKKCIGLGTSTQI](https://webs.iiitd.edu.in/raghava/anticp/pepsearch1.php?seq=VLCIGEGSKKCIGLGTSTQI&thval=0.0) |  |  | 0 | MUTANT | 6 | 0.98 | ANTICP |
|  |  | PD127 | [KEGCCEGSKKCIGLGTSTQI](https://webs.iiitd.edu.in/raghava/anticp/pepsearch1.php?seq=KEGCCEGSKKCIGLGTSTQI&thval=0.0) |  |  | 6 | MUTANT | 5 | 1.20 | ANTICP |

**Table 4: Activity-based peptide reconstruction of predicted peptide from CAMPR3 using antiCP1 web servers.** 

**Reference:**

1. Tyagi A . *et. al. *(2013),In Silico Models for Designing and Discovering  
   Novel Anticancer Peptides [Scientific Reports, 3 (10.1038/srep02984).](http://www.nature.com/srep/2013/131018/srep02984/full/srep02984.html)

