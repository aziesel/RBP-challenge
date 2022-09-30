# RBP-challenge
Work performed by our team to characterize RNA binding targets of the human protein PRPF17/CDC40.

This repository contains the work product produced by each phase of our analysis. All utilities used are publicly, freely available and many are offered as web servers, simplifying analysis for those labs without appropriate computer hardware to run analyses locally. 


#### Index ####

1_protein_domain_prediction/

  * TriPepSVM/              output produced by the TriPepSVM RNA binding domain prediction utility  
  * drna/                   intermediate output produced by the DRNAPred RNA binding domain prediction utility 
  * spotseq/                output produced by the SPOT-SEQ-RNA RNA binding domain prediction utility   
  * BP_AARNA4260136W_W.pdf  output produced by the AARNA RNA binding domain prediction utility 
  * CDC40-DRNAPred.txt      final output produced by the DRNAPred RNA binding domain prediction utility 
  * CDC40-FastRNA.txt       output produced by the FastRNA RNA binding domain prediction utility 
  * CDC40-HybridNap.csv     output produced by the HybridNAP RNA binding domain prediction utility  
  * CDC40-PPrint.txt        output produced by the PPrint RNA binding domain prediction utililty 
  * KYG.pdf                 output produced by the KYG RNA binding domain prediction utility 
  
  
2_RNA_motif_target_prediction/

  * streme/                 enriched motifs identified from PRPF17/CDC40 eCLIP data 
  * FIMO_output.tar.gz      found locations of motifs identified by STREME  
  * annotated_eclip.tar.gz  eCLIP data for PRPF17/CDC40 mapped to hg38  
  * annotated_fimo.bed.zip  FIMO output locations mapped to hg38, .bed file format  
  * annotated_fimo.tar.gz   FIMO output locations mapped to hg38, .gff file format  
  * fimo.gff.tar.gz         found locations of motifs identified by STREME, .gff file format  
  * results.tar.gz          found locations of motifs identified by STREME, .bed file format  
  * subtracted.tar.gz       found locations of motifs identified by STREME, less those found in PRPF17/CDC40 eCLIP data  
