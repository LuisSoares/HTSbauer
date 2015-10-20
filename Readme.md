# Instructions to use HTS pipeline
This pipeline works for raw files coming from the Bauer center sequencing facility.
It works in the HMS Orchestra cluster as of 10/20/2015

Make sure to have in the directory where you plan to analyze the results, aside from the sequencing file,
the following files:
*analysis.sh
*analysis.py
*log_parser.py
*BDGtoWIG.py
*fastq_trimmer.py
*a config file

The output of the script will be in mochiview compatible *.wig files in the mochiview directory
There are also two pdf containing some statistics of the script.