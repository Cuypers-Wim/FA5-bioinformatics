# pwd 

# on my system
# /mnt/d/postdoc/01_projects/2024_FA5BioInf/FA5-bioinformatics/training/data/fastq

# on your system
# ~/Desktop/Fa/FA5-bioinformatics/training/data/fastq


fastqc \
-o ../../results/fastqc \
-t 8 \
*.fastq.gz

