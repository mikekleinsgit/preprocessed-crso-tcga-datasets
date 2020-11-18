# preprocessed-crso-tcga-datasets
Preprocessed datasets from 19 TCGA cancer types that were used in the CRSO study.

The file "mean_tissue_penalties.RData" contains simplified tissue passenger probabilities and penalty values for all 19 tissue types. The last row corresponds to a PANCANCER passenger probability vector / penalty vector for each observation type (e.g., hotspot, weak amplification, indel, etc.). The PANCANCER penalty vec is a good option when users are unable to calculate patient-specific, event-specific penalties directly. 

