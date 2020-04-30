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
│   │   ├── BLCA_top_2_mutations_vs_95controls_ZNF_classification.png
│   │   ├── BLCA_top_mutations_vs_95controls_ZNF_classification-10perc.png
│   │   ├── Mutated_Genes.txt
│   │   ├── gdac.broadinstitute.org_BLCA.Mutation_Packager_Calls.Level_3.2016012800.0.0
│   │   ├── gdac.broadinstitute.org_BLCA.Mutation_Packager_Calls.Level_3.2016012800.0.0.tar.gz
│   │   └── sample_top_mutations_nonSilentSNPS.csv
│   ├── BRCA
│   │   ├── BRCA_top_2_mutations_vs_95controls_ZNF_classification.png
│   │   ├── BRCA_top_2_mutations_vs_ZNF_classification-10perc.png
│   │   ├── BRCA_top_2_mutations_vs_ZNF_classification.png
│   │   ├── BRCA_top_mutations_vs_ZNF_classification-10perc.png
│   │   ├── Mutated_Genes.txt
│   │   ├── gdac.broadinstitute.org_BRCA.Mutation_Packager_Calls.Level_3.2016012800.0.0
│   │   ├── gdac.broadinstitute.org_BRCA.Mutation_Packager_Calls.Level_3.2016012800.0.0.tar.gz
│   │   └── sample_top_mutations_nonSilentSNPS.csv
│   ├── HNSC
│   │   ├── HNSC_top_2_mutations_vs_95controls_ZNF_classification.png
│   │   ├── HNSC_top_mutations_vs_95controls_ZNF_classification-10perc.png
│   │   ├── Mutated_Genes.txt
│   │   ├── gdac.broadinstitute.org_HNSC.Mutation_Packager_Raw_Calls.Level_3.2016012800.0.0
│   │   ├── gdac.broadinstitute.org_HNSC.Mutation_Packager_Raw_Calls.Level_3.2016012800.0.0.tar.gz
│   │   └── sample_top_mutations_nonSilentSNPS.csv
│   ├── KIRC
│   │   ├── KIRC_top_2_mutations_vs_95controls_ZNF_classification.png
│   │   ├── KIRC_top_mutations_vs_95controls_ZNF_classification-10perc.png
│   │   ├── Mutated_Genes.txt
│   │   ├── gdac.broadinstitute.org_KIRC.Mutation_Packager_Raw_Calls.Level_3.2016012800.0.0
│   │   ├── gdac.broadinstitute.org_KIRC.Mutation_Packager_Raw_Calls.Level_3.2016012800.0.0.tar.gz
│   │   └── sample_top_mutations_nonSilentSNPS.csv
│   ├── KIRP
│   │   ├── KIRP_top_2_mutations_vs_95controls_ZNF_classification.png
│   │   ├── KIRP_top_2_mutations_vs_ZNF_classification.png
│   │   ├── Mutated_Genes.txt
│   │   ├── gdac.broadinstitute.org_KIRP.Mutation_Packager_Raw_Calls.Level_3.2016012800.0.0
│   │   ├── gdac.broadinstitute.org_KIRP.Mutation_Packager_Raw_Calls.Level_3.2016012800.0.0.tar.gz
│   │   └── sample_top_mutations_nonSilentSNPS.csv
│   ├── LIHC
│   │   ├── LIHC_top_2_mutations_vs_95controls_ZNF_classification.png
│   │   ├── LIHC_top_2_mutations_vs_ZNF_classification-10perc.png
│   │   ├── LIHC_top_2_mutations_vs_ZNF_classification.png
│   │   ├── LIHC_top_3_mutations_vs_ZNF_classification-10perc.png
│   │   ├── LIHC_top_mutations_vs_ZNF_classification-10perc.png
│   │   ├── Mutated_Genes.txt
│   │   ├── gdac.broadinstitute.org_LIHC.Mutation_Packager_Raw_Calls.Level_3.2016012800.0.0
│   │   ├── gdac.broadinstitute.org_LIHC.Mutation_Packager_Raw_Calls.Level_3.2016012800.0.0.tar.gz
│   │   └── sample_top_mutations_nonSilentSNPS.csv
│   ├── LUAD
│   │   ├── LUAD_top_2_mutations_vs_95controls_ZNF_classification.png
│   │   ├── LUAD_top_2_mutations_vs_ZNF_classification-10perc.png
│   │   ├── LUAD_top_2_mutations_vs_ZNF_classification.png
│   │   ├── LUAD_top_5_mutations_vs_ZNF_classification-10perc.png
│   │   ├── LUAD_top_mutations_vs_ZNF_classification-10perc.png
│   │   ├── Mutated_Genes.txt
│   │   ├── gdac.broadinstitute.org_LUAD.Mutation_Packager_Calls.Level_3.2016012800.0.0
│   │   ├── gdac.broadinstitute.org_LUAD.Mutation_Packager_Calls.Level_3.2016012800.0.0.tar.gz
│   │   └── sample_top_mutations_nonSilentSNPS.csv
│   ├── OV
│   │   ├── Mutated_Genes.txt
│   │   ├── OV_top_2_mutations_vs_95controls_ZNF_classification.png
│   │   ├── OV_top_2_mutations_vs_ZNF_classification.png
│   │   ├── OV_top_mutations_vs_ZNF_classification-10perc.png
│   │   ├── gdac.broadinstitute.org_OV.Mutation_Packager_Calls.Level_3.2016012800.0.0
│   │   ├── gdac.broadinstitute.org_OV.Mutation_Packager_Calls.Level_3.2016012800.0.0.tar.gz
│   │   └── sample_top_mutations_nonSilentSNPS.csv
│   ├── PAAD
│   │   ├── Mutated_Genes.txt
│   │   ├── PAAD_top_2_mutations_vs_95controls_ZNF_classification.png
│   │   ├── PAAD_top_2_mutations_vs_ZNF_classification.png
│   │   ├── PAAD_top_mutations_vs_ZNF_classification-10perc.png
│   │   ├── gdac.broadinstitute.org_PAAD.Mutation_Packager_Calls.Level_3.2016012800.0.0
│   │   ├── gdac.broadinstitute.org_PAAD.Mutation_Packager_Calls.Level_3.2016012800.0.0.tar.gz
│   │   └── sample_top_mutations_nonSilentSNPS.csv
│   ├── PRAD
│   │   ├── Mutated_Genes.txt
│   │   ├── PRAD_top_2_mutations_vs_95controls_ZNF_classification.png
│   │   ├── PRAD_top_2_mutations_vs_ZNF_classification.png
│   │   ├── PRAD_top_mutations_vs_ZNF_classification-10perc.png
│   │   ├── gdac.broadinstitute.org_PRAD.Mutation_Packager_Raw_Calls.Level_3.2016012800.0.0
│   │   ├── gdac.broadinstitute.org_PRAD.Mutation_Packager_Raw_Calls.Level_3.2016012800.0.0.tar.gz
│   │   └── sample_top_mutations_nonSilentSNPS.csv
│   └── STAD
│       ├── Mutated_Genes.txt
│       ├── STAD_top_2_mutations_vs_95controls_ZNF_classification.png
│       ├── STAD_top_mutations_vs_95controls_ZNF_classification-10perc.png
│       ├── gdac.broadinstitute.org_STAD.Mutation_Packager_Raw_Calls.Level_3.2016012800.0.0
│       ├── gdac.broadinstitute.org_STAD.Mutation_Packager_Raw_Calls.Level_3.2016012800.0.0.tar.gz
│       └── sample_top_mutations_nonSilentSNPS.csv
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
