# UTC-0500

UTC-500 team submission for the [AI Genomics Hackathon](https://sv.ai/hackathon/), 23-25 June 2017.

The data for the hackathon include a whole genome sequence data set for NF2: a genetic condition that
causes tumors to grow from Schwann cells. The dataset has a tumor/normal pair and a sibling. All three
samples were whole genome sequenced at 60-90X, aligned to the hg19 human genome assembly, and made
available as BAM files. The dataset was acquired in the context of finding the driver mutations for
a particular NF2 patient.

This submission plans to transform the data in VCF and BAM formats into the [Big Data Genomics](http://bdgenomics.org/)
[Parquet + Avro format](https://github.com/bigdatagenomics/adam), partitioned for efficient performance
on an Apache Spark cluster. Then as time allows, re-align the reads against the most recent human genome
assembly (GRCh38), and re-call variants with [FreeBayes](https://github.com/ekg/freebayes) via
[Cannoli](https://github.com/bigdatagenomics/cannoli) and [Avocado](https://github.com/bigdatagenomics/avocado).

## Transform VCF and BAM data into Big Data Genomics Parquet + Avro format

## Re-align reads to GRCh38 with BWA

## Re-call variants with FreeBayes

## Re-call variants with Avocado
