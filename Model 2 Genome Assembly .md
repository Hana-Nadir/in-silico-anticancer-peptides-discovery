**Materials and Method** 

**Quality Control and Genome Assembly** 

A clean WGS sample from Lactoccocus Lactis KCKM0851 was processed on the Illumina  platform, through the Bv-brc genome assembly pipeline (v3.6.9), following the method  described by Davis et al. (2020) and Parrello et al. (2021). To enhance assembly outcomes,  rectify bases, perform quality checks, and trim, correct misassemblies, and fill gaps, the  Unicycler (v0.4.8) assembler, samtools (v1.17), and Pilon (v1.23) were employed, with a  minimum contig length set at a coverage of 300 pb and a minimum contig coverage of 5.0 (Antipov et al. 2020). Additionally, assembly quality was assessed using QUAST (v5.0.2) (Taş et  al. 2021).