# coverage_analysis
Assume following tools are already installed: wget samtools, bedtools, GATK, Picard (the pseudo path is $PICARD)
Reference GRCH38 has been downloaded and name it as reference_file, which is already indexed by “samtools faidx”.
The input is bam file. The ouput is bed file containing genome location and corresponding coverage information
