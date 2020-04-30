# ZNF154_Manuscript
Code to reproduce manuscript figures

Note that the input files are too large to host here. Please contact on obtaining the input files if you would like to rerun yourself.

The directory structure is as follows:
```
.
├── Figures.ipynb
├── methylationArrayData
│   ├── BLCA_450K_ZNF154.txt
│   ├── BRCA_450K_ZNF154.txt
│   ├── Bartlett
│   │   ├── 2015_Bartlett_fallopian_tube_samples_GSE74845_series_matrix_2.txt
│   │   ├── GSE72021_AverageBetaValues\ 2.csv
│   │   └── GSE72021_series_matrix.txt
│   ├── COAD_450K_ZNF154.txt
│   ├── HNSC_450K_ZNF154.txt
│   ├── KIRC_450K_ZNF154.txt
│   ├── KIRP_450K_ZNF154.txt
│   ├── LAML_450K_ZNF154.txt
│   ├── LIHC_450K_ZNF154.txt
│   ├── LUAD_450K_ZNF154.txt
│   ├── LUSC_450K_ZNF154.txt
│   ├── OV_27K_ZNF154.txt
│   ├── OV_450K_ZNF154.txt
│   ├── PAAD_450K_ZNF154.txt
│   ├── PRAD_450K_ZNF154.txt
│   ├── READ_450K_ZNF154.txt
│   ├── STAD_450K_ZNF154.txt
│   ├── TCGA_earlyStage_samples.txt
│   ├── UCEC_450K_ZNF154.txt
│   ├── noncancerDiseases
│   │   └── noncancer_disease_samples_beta_values.csv
│   └── peripheralBlood
│       ├── GSE55763_normalized_betas_ZNF154.txt
│       └── GSE55763_series_matrix.txt
├── mutationFreqs
│   ├── BLCA
│   │   ├── Mutated_Genes.txt
│   │   ├── gdac.broadinstitute.org_BLCA.Mutation_Packager_Calls.Level_3.2016012800.0.0
│   │   └── gdac.broadinstitute.org_BLCA.Mutation_Packager_Calls.Level_3.2016012800.0.0.tar.gz
│   ├── BRCA
│   │   ├── Mutated_Genes.txt
│   │   ├── gdac.broadinstitute.org_BRCA.Mutation_Packager_Calls.Level_3.2016012800.0.0
│   │   └── gdac.broadinstitute.org_BRCA.Mutation_Packager_Calls.Level_3.2016012800.0.0.tar.gz
│   ├── HNSC
│   │   ├── Mutated_Genes.txt
│   │   ├── gdac.broadinstitute.org_HNSC.Mutation_Packager_Raw_Calls.Level_3.2016012800.0.0
│   │   └── gdac.broadinstitute.org_HNSC.Mutation_Packager_Raw_Calls.Level_3.2016012800.0.0.tar.gz
│   ├── KIRC
│   │   ├── Mutated_Genes.txt
│   │   ├── gdac.broadinstitute.org_KIRC.Mutation_Packager_Raw_Calls.Level_3.2016012800.0.0
│   │   └── gdac.broadinstitute.org_KIRC.Mutation_Packager_Raw_Calls.Level_3.2016012800.0.0.tar.gz
│   ├── KIRP
│   │   ├── Mutated_Genes.txt
│   │   ├── gdac.broadinstitute.org_KIRP.Mutation_Packager_Raw_Calls.Level_3.2016012800.0.0
│   │   └── gdac.broadinstitute.org_KIRP.Mutation_Packager_Raw_Calls.Level_3.2016012800.0.0.tar.gz
│   ├── LIHC
│   │   ├── Mutated_Genes.txt
│   │   ├── gdac.broadinstitute.org_LIHC.Mutation_Packager_Raw_Calls.Level_3.2016012800.0.0
│   │   └── gdac.broadinstitute.org_LIHC.Mutation_Packager_Raw_Calls.Level_3.2016012800.0.0.tar.gz
│   ├── LUAD
│   │   ├── Mutated_Genes.txt
│   │   ├── gdac.broadinstitute.org_LUAD.Mutation_Packager_Calls.Level_3.2016012800.0.0
│   │   └── gdac.broadinstitute.org_LUAD.Mutation_Packager_Calls.Level_3.2016012800.0.0.tar.gz
│   ├── OV
│   │   ├── Mutated_Genes.txt
│   │   ├── gdac.broadinstitute.org_OV.Mutation_Packager_Calls.Level_3.2016012800.0.0
│   │   └── gdac.broadinstitute.org_OV.Mutation_Packager_Calls.Level_3.2016012800.0.0.tar.gz
│   ├── PAAD
│   │   ├── Mutated_Genes.txt
│   │   ├── gdac.broadinstitute.org_PAAD.Mutation_Packager_Calls.Level_3.2016012800.0.0
│   │   └── gdac.broadinstitute.org_PAAD.Mutation_Packager_Calls.Level_3.2016012800.0.0.tar.gz
│   ├── PRAD
│   │   ├── Mutated_Genes.txt
│   │   ├── gdac.broadinstitute.org_PRAD.Mutation_Packager_Raw_Calls.Level_3.2016012800.0.0
│   │   └── gdac.broadinstitute.org_PRAD.Mutation_Packager_Raw_Calls.Level_3.2016012800.0.0.tar.gz
│   └── STAD
│       ├── Mutated_Genes.txt
│       ├── gdac.broadinstitute.org_STAD.Mutation_Packager_Raw_Calls.Level_3.2016012800.0.0
│       └── gdac.broadinstitute.org_STAD.Mutation_Packager_Raw_Calls.Level_3.2016012800.0.0.tar.gz
└── plasma
    ├── DREAMingNormalizedCounts.csv
    ├── KRASddPCRcounts.csv
    ├── TableS2_plasmaSamples.csv
    ├── colonNormalizedMethylatedZNFCounts.csv
    ├── liverNormalizedMethylatedZNFCounts.csv
    ├── ovarianNormalizedMethylatedZNFCounts.csv
    ├── pancreasEarlyNormalizedMethylatedZNFCounts.csv
    └── pancreasLateNormalizedMethylatedZNFCounts.csv

```
