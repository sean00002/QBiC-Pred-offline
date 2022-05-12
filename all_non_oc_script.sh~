#! /bin/zsh

for filename in /Users/shengyuli/Dropbox/Research/Schizophrenia/Data_pipeline/all_oc_for_qbic/*.vcf; do
    python3 qbic.py -i "$filename" -g QBiC_gene_names_for_supported_TFs.txt -c hg38 -f p-value -v 2 -o "/Users/shengyuli/Dropbox/Research/Schizophrenia/Data_pipeline/all_oc_from_qbic/output_$(basename "$filename" .vcf).csv"
done
