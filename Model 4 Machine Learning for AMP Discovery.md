**Methods :** 

**Machine Learning for AMP Discovery:** 

To identify promising antimicrobial peptides (AMPs) derived from biosynthetic genes, we leveraged the advanced machine learning capabilities of the CAMPR3 tool. This two-step approach involved initially predicting a single 99-amino acid AMP using the model with the highest probability 1. Subsequently, this predicted sequence was deconstructed to identify 20 distinct 20-amino acid AMPs, each selected based on its likelihood of being an AMP according to multiple models. This strategy streamlined the peptide selection process, enabling a focused exploration of potential antimicrobial candidates for further experimental validation. 

**Results :** 

**Leveraging Machine Learning to Predict Antimicrobial Peptides from Secondary Metabolite Genes:** 

A comprehensive analysis of nine genes involved in secondary metabolite biosynthesis was conducted to identify potential antimicrobial peptides (AMPs). The genes analyzed encompassed a diverse range of protein functions, including transcriptional regulators, enzymes involved in secondary metabolism, and radical SAM superfamily proteins. 

Machine learning models were employed to predict AMPs within these genes, resulting in the identification of multiple potential candidates. The machine learning models used in this study (SVM, RF,and ANN) consistently predicted high probabilities of antimicrobial activity for the identified AMP sequences. 

The predicted AMPs varied in length and type, with examples including: 

● **Betalactone:** A 99-amino acid AMP predicted from the gene ctg1\_573, which encodes cetyl-CoA carboxylase biotin carboxylase. This enzyme is involved in fatty acid biosynthesis. 

● **RiPP-like Peptide:** A 34-amino acid AMP predicted from the gene ctg1\_649, which encodes a GntR family transcriptional regulator. GntR proteins are involved in regulating gene expression in response to various environmental signals. 

● **T3PKS-like Peptide:** A 20-amino acid AMP predicted from the gene ctg1\_932, which encodes YcaO cyclodehydratase. This enzyme is involved in the biosynthesis of cyclopropane fatty acids. 

The subsequent phase of this research will focus on elucidating the anti-cancer potential of the identified peptides. This will involve reconstructing their sequences to optimize their efficacy against cancer cells and conducting functional prediction to assess their biological activity and mechanisms of action. By adopting this comprehensive approach, we aim to gain a deeper  
understanding of the therapeutic potential of these peptides in cancer treatment and advance our knowledge of their underlying mechanisms.

| Secondary  Metabolites | S/N  | Encoding  Gene | Protein Length  | Predicted AMP within Peptides  |  | AMP Probability  |  |  |  | Predicte  d as  AMP  Across  All  Models |
| ----- | ----: | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
|  |  |  |  | **SEQUENCE**  | **POSITION**  | **SVM**  | **RF**  | **ANN**  | **DA** |  |
| betalactone  | 1  | ctg1\_573  | cetyl-CoA  1137  carboxylase  biotin  carboxylase  | **99 AMP** |  |  |  |  |  |  |
|  |  |  |  | MRLNEKIEVQIEKGKTLSIRLDEIGEPDLAGNRVLFFNLNG QRREVVINDQSVQTQVVAKRKAETGNPNQIGATMPGSVLE ILVKAGDKVQKGQALMVT | 1001-1099  | 0.999  | .984  | **AMP**  | \-  | YES |
|  |  |  |  | **20 AMP** |  |  |  |  |  |  |
|  |  |  |  | GYPVMIKAALGGGGRGMRVA | 151-170  | 0.933  | 0.931  | AMP  | \-  | YES |
|  | 2  | ctg1\_566  | AMP-bindi  507  ng enzyme  | **99 AMP** |  |  |  |  |  |  |
|  |  |  |  | MHTFLSASKQKEPVFLQIYGQSECGPMIWKKHRLST LADTNAREMGIGMPGLSKARIADKDGNECPAGTPG RIHFLSKGRALTYYKEEERFNKEVYGDW | 294-392  | 0.991  | 0.994  | NAMP  | \-  | NA |
|  |  |  |  | **20 AMP** |  |  |  |  |  |  |
|  |  |  |  |  | 57-76  | 0.965  | 0.874  | AMP  | \-  | YES |

|  |  |  |  | LLSELGIKKSDKVIIFKSSA |  |  |  |  |  |  |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
|  | 3  | **ctg1\_64 9** | GntR  121  family  transcripti  onal  regulator  | **99 AMP** |  |  |  |  |  |  |
|  |  |  |  | MHIDPNNKDAIYEQIVFNIKKEITKGILDVGDKILSVREMS KQLGVNPNTVAKAYKELEHQNVITTIKGRGSFVKNNDGQ DEEIDIQTQKKLRSQLKSW | 1-99  | 1.000  | .984  | AMP  | \-  | YES |
|  |  |  |  | **20 AMP** |  |  |  |  |  |  |
|  |  |  |  | IVFNIKKEITKGILDVGDKI | 15-34  | .994  | .907  | AMP  | \-  | YES |
| RiPP like  | 4  | **ctg1\_93 2** | YcaO  345  cyclodehy  drat ase  | **99 AMP** |  |  |  |  |  |  |
|  |  |  |  | GMASHTNSKEVIKTAFFEFFERQSFLTNFLSQTAVPRLLFDN EESLIIADNYLKNYVDKINYYDVSLDRSLHVVLCIGYGSKK CIGLGTSTQIKEAIKK | 102-200  | .993  | .963  | AMP  | \-  | YES |
|  |  |  |  | **20 AMP** |  |  |  |  |  |  |
|  |  |  |  | GMASHTNSKEVIKTAFFEFFERQSFLTNFLSQTAVPRLLFDN EESLIIADNYLKNYVDKINYYDVSLDRSLHVVLCIGYGSKK CIGLGTSTQIKEAIKK | 175-194  | .966  | .935  | AMP  | \-  | YES |
| T3PKS  | 5  | ctg1\_15 89 | hydroxyme  384  thy  lglutaryl-C  oA  synthase  | **99 AMP** |  |  |  |  |  |  |
|  |  |  |  | IITFAANAAASILTEEDKKAIDMVIVGTESSLDESKASAVVV HDLLGIQPFARSIEMKEACYATTAGLALARDHVLLNPDTKVL | 51-149  | .995  | .953  | AMP  | \-  | YES |

|  |  |  |  | VIASDIAKYGLNTGG |  |  |  |  |  |  |
| :---- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
|  |  |  |  | **20 AMP** |  |  |  |  |  |  |
|  |  |  |  | AAIAFHTPYTKMGKKALLPM | 228-247  | .921  | .530  | AMP  | \-  | YES |
|  | 6  | ctg1\_15 82 | AraC  319  family  transcriptio  nal  regulator  | **99 AMP** |  |  |  |  |  |  |
|  |  |  |  | CYFNNKVTKAAFILLIVELSHHSEEYLILKDSNISSSVLIKEI LSYIENNIRTASLEELSTKFYFHPNYLSSLIKHQTGLSYSTW LTTYRIKHAKNYLT | 177-275  | .973  | .858  | AMP  | \-  | YES |
|  |  |  |  | **20 AMP** |  |  |  |  |  |  |
|  |  |  |  | ALLLLKQVVKMCYFNNKVTK | 166-185  | .937  | .945  | AMP  | \-  | YES |
|  | 7  | ctg1\_15 69 | LysR  324  family  transcriptio  nal  regulator  | **99 AMP** |  |  |  |  |  |  |
|  |  |  |  | TISLQQLKYFIEVARVGSINQAAEILFITQPSLSKAIKDIEVE VDLSLFQRSSKGISLTADGAEFLGYARQVVEQSDLLETRWL DRKPSRKLCAISTQH | 2-100  | .999  | .962  | AMP  | \-  | YES |
|  |  |  |  | **20 AMP** |  |  |  |  |  |  |
|  |  |  |  | AIKDIEVEVDLSLFQRSSKG | 37-56  | .891  | .574  | AMP  | \-  | YES |

| RaS-RIPP  | 8  | ctg1\_23 09 | Radical  308  SAM  superfamil  y  | 99 AMP |  |  |  |  |  |  |
| ----- | :---: | :---: | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
|  |  |  |  | HVSLLGGEPTECEYFEYIIIQLEKLRISYSFSTNGQKLFRNEE LIRILSKSKYLKEVQISLESPQKLINDAVRGKGTFESAIKSV ALLVKENVPTRLAM | 55-153  | .999  | .961  | AMP  | \-  | YES |
|  |  |  |  | **20 AMP** |  |  |  |  |  |  |
|  |  |  |  | AVRGKGTFESAIKSVALLVK | 125-144  | .874  | .952  | AMP  | \-  | YES |
|  | 9  | ctg1\_23 19 | transcriptio  110  nal  regulator  | **99 AMP** |  |  |  |  |  |  |
|  |  |  |  | MKKISELPDCPVETALVLMGDRWKMLIVRDLLERTMRFGEL QRSVGHISQKVLTQHLRALEESGLVHREVYAEVPPRVEYSL TELGRTLKPIHDTMAAW | 1-99  | .999  | .972  | NAMP  | \-  | NA |
|  |  |  |  | **20 AMP** |  |  |  |  |  |  |
|  |  |  |  | LQRSVGHISQKVLTQHLRAL | 41-60  | .737  | .670  | AMP  | \-  | YES |

**Table 3: AMP Prediction Results Using CAMPR3** 

**References :** 

1\. Gawde U, Chakraborty S, Waghu F H, Barai R S, Khanderkar A, Indraguru R, Shirsat T, Idicula-Thomas S. CAMPR4: a database of natural and synthetic antimicrobial peptides. *Nucleic Acids Research*, 2023, Vol. 51, Database issue: D377–D383.DOI: https://doi.org/10.1093/nar/gkac933