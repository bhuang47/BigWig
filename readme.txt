(1) input files:
(1.1) bedgraph file
(1.2) chrom size file (in this folder, hg19.chrom.sizes, mm9.chrom.sizes) --> can also be downloaded from http://hgdownload.soe.ucsc.edu/goldenPath/${i}/bigZips/${i}.chrom.sizes ($i is mm9, hg19...)


(2) code
in /Users/hbb/Dropbox/common_code.
export PATH=/Users/hbb/Dropbox/common_code:$PATH


(3) command line
bedGraphToBigWig in.bedGraph chrom.sizes myBigWig.bw
(Note that the bedGraphToBigWig program DOES NOT accept gzipped bedGraph input files.)


