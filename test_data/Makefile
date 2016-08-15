all:
	-rm -rf report
	./../src/QSpipeline -z -x \
		-p ~/third-party/PEAR/src/pear \
		-b /Users/ratan/third-party/bwa-0.7.10/bwa \
		-s /Users/ratan/third-party/samtools-1.1/samtools \
		-q ~/third-party/QuasiRecomb.jar \
	    -l /Users/ratan/third-party/lastz-distrib-1.03.62/src/lastz \
		~/projects/HIV/references/A1_92_UG029.fa \
		DT10_S67_L001_R1_001.fastq.gz DT10_S67_L001_R2_001.fastq.gz
