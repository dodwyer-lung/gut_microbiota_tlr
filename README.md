# gut_microbiota_tlr
Data repository for gut microbiota and TLR experiments
gut_tlr_family_16s.csv ---- raw 16S counts binned at family level taxonomic classification
gut_tlr_metadata.csv ---- biological metadata variables
gut_tlr_otu_16S.csv ---- raw 16S counts per specimen
gut_tlr_taxonomy.csv ---- taxonmy data
GZ files are available at SRA accession number PRJNA695499 ---- however, they do not all match. 5 controls specimens from a seperate experiment were mistakeningly uploaded with these gz files 
These are as follows-  
d1930_instrument1_S254
d1930_instrument2_S255
d1930_instrument3_S279
d1930_instrument4_S280
d1930_instrument5_S281

Rownames in this project may be used to select variables - are coded as follows:
d1930_m10c10_f0_wt_non_S45 ---- d1930 experient
                                m10 - mosue ID
                                C10 - cage number
                                f0 - time day 0
                                fe - time day 21
                                wt/t2/t4/t5 - wildtype, tlr2-/-, tlr4-/-, tlr5-/- 
                                non - co-hosued by genotype 
                                ran - randomly housed
                                S45 - run ID

