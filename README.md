# Load2DDBJsubmit
Load to DDBJ submit genome
## Prepare Genome FASTA file
``` perl -pe 'print "//\n" if /^>/ && $. > 1' my_genome.fa > submit_genome.fa ```
## Make Annotation file
Use https://github.com/yamaton/gff3toddbj

1. 
