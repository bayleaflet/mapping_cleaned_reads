# Mapping Cleaned Reads Worksheet

<!--- Write name below --->
## Name: Baylee Christensen

<!--- For this worksheet, answer the following questions --->

## Q1: What does it mean to map/align reads to a reference?
Answer: It means that you are comparing your read dataset to a previously existed (and hopefully annotated) read dataset. The reference will hopefully make it easier for you to align the genome you are attempting to puzzle together.

## Q2: What read mapper does the mapping_cleaned_reads.sh script use?
Answer: bwa mem

## Q3: Both Illumina and Nanopore reads are used for this assignment. What are the major differences between the methodology used for these sequencing platforms?
Answer: The major different is that Illumina generates short reads using sequencing by synthesis, and requires clonal amplification. Nanopore methodologies generate long reads, and requires minimal library prep and no synthesis sequencing.

## Q4: What differences do you notice between the Illumina and Nanopre raw_data fastq file sizes? Which are larger?
Answer: It seems that in general the Nanopore files are larger, though not by a massive amount, even for the fasp.json file.

## Q5: What differences do you notice between the Illumina and Nanopore cleaned_reads fastq file sizes? Which are larger?
Answer: In the cleaned reads, the Nanopore files are significantly smalelr!

## Q6: What explains the difference in your responses of Q4 and Q5? (HINT: Take a glimpse at the raw data .fastq files themselves)
Answer: The format of the fastq files are quite different, in which the Illuminana sequence has a pretty concrete format, and the Nanopore raw_data has very different format that has more variables. This is likely the reason the file is larger. In the end though, I would expect the Nanopore to be a smaller file because overall less reads are generated.

## Q7: What is the average read depth for the Illumina data across all samples for the genomic regions that were mapped to?
Answer: I believe it is about 60, a little less.

## Q8: What is the average read depth for the Illumina data across all samples for all genomic regions?
Answer: Not sure how to check this! I am only seeing the reads that are mapped.

## Q9: What is the average read depth for the Nanopore data across all samples for the genomic regions that were mapped to?
Answer: Smaller, closer to 54.

## Q10: What is the average read depth for the Nanopore data across all samples for all genomic regions?
Answer: Once again, only seeing read that are mapped. Not sure the location of this information, as I cannot check the other file types unless it is a sam file.
