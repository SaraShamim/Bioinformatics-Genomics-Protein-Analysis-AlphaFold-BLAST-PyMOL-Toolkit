# BLAST Sequence Homology Search - NCBI
## Objective 
To find homology sequence and confirm the identity if protein KRN92659.1 from Lactobacillus amylovours using NCBI BLAST.
## Method 
- Tool: NCBI BLASTp (https://blast.ncbi.nlm.nih.gov/Blast.cgi?PROGRAM=blastp)
- Database: Non-redundant protein sequence (nr)
- Query: Protein ID KRN92659.1 - Lactobacillus amylovours
- Organism: Lactobacillus amylovours (TaxID:1604) - a probiotic lactic acid bacterium
 ## Procedure
 Retrieved FASTA sequence for KRN92659.1 from NCBI Protein database.
 Pasted the FASTA sequence into BLASTp query box.
 Selected database as "nr" and organism filter as "Lactobacillus".
 Clicked BLAST
 Analyzed top hits based on E-Value, % identity, and Query Coverage.
 ## Result 
 -Top hit showed 100% identity with Lactobacillus amylovours strain, Accession KRN92659.1 with E-Value 0.0 and 100% query coverage, confirming sequence retrieval.
 - All top 10 hits belonged to Lactobacillaceae family, indicating high conservation within genus Lactobacillus.
 - Low E-Value (0.0 to e-150) indicate highly significant homology, not by chance.
## Conclusion
BLASTp analysis confirmed that protein KRN92659.1 is highly conversed within Lactobacillus genus, especially in amylovours. This conservation suggests an important structural role, likely related s-layer formation and probiotic function in gut adhesion. This result will be used for further phylogenetic analysis and AlphaFold2 structure prediction.
## Tools Used
NCBI Protein Database, BLASTp, Lactobacillus amylovours TaxID 1604
    
  
