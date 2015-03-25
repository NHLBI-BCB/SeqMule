# v1.1.4
2015-02-13 Yunfei Guo <yunfeigu@usc.edu>

* fixed a bug for file names containing whitespace.

# v1.1.3
2015-01-31 Yunfei Guo <yunfeigu@usc.edu>

* Illumina TruSight Capture Kit BED files added
* Replace Picard duplicate removal with SAMtools rmdup for faster speed
* Improved runtime output
* Bug fixes for /bin/sh, GATK3.3.0

# v1.1.2
2015-01-13 Kai Wang <kaichop@gmail.com>, Yunfei Guo <yunfeigu@usc.edu>

* Add SNAP aligner for faster alignment
* Better support for gzipped FASTQ input
* Add Mendelian statistics calculation
* Add variant normalization
* Faster variant calling under quick mode
* Add separate Venn diagrams for SNVs and non-SNVs
* Better variant consensus generation
* Improved stability
* Bug fixes

# v1.1.1
2014-10-17 Yunfei Guo <yunfeigu@usc.edu>

* Add '-tmpdir' option in 'seqmule stats' and 'seqmule pipeline'
* Add 'seqmule update' to make allow automatic update.

# v1.1.0
2014-05-29 Yunfei Guo <yunfeigu@usc.edu>

* Add GATK full version, Freebayes
* Fix bugs related to multiple-sample variant calling
* Improve performance under quick mode
* Automatic detection and correction of chromosome naming across input
* Other bug fixes