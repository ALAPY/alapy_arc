# ALAPY COMPRESSOR
ABOUT ALAPY COMPRESSOR
-
ALAPY Compressor – is a cross-platform software tool used for efficient compression of NGS data. Latest version utilizes lossless compression algorithm developed by our data scientists for fastq files and optimized for the latest sequencing machines from Illumina. Our users say ALAPY Compressor works fast and uses very little cpu and memory. They see 2-3 times reduction in storage space compared to gziped fastq files (fastq.gz).

We assembled a benchmark for fastq compression algorithms testing based on representative public samples from NCBI Sequence Read Archive (SRA). Our benchmark includes gene panel testing, WES (and WXS), WGS, RNA-seq, ChIP-seq, BS-seq and other types of experiments from human samples and model organisms like Mouse, Zebrafish, Drosophila, Rhesus macaque, different Yeasts, Roundworm, Arabidopsis, Rice, Maize, Medicago, E. coli and the list is growing.

![Benchmark](https://github.com/ALAPY/alapy_arc/blob/master/Content/Benchmark.png)

We see the minimum reduction in file size over gziped fastq file (fastq.gz) of 1.5 and maximum of 2.9 with an average of 1.9 and standard deviation of 0.4 on over 230 samples. On the bar graph, you can see compression levels between gzipped, SRA archived and ALAPY Compressed files for several of human and mouse samples as a compression ratio compared to fastq file. Compression ratios between gziped and ALAPY compressed fastq files are given on top of each bar.

License
-
By installing and/or using this software you agree to the license agreement located at [http://alapy.com/alapy-compressor-eula/](http://alapy.com/alapy-compressor-eula/)
Copyright © 2017 ALAPY Inc. All rights reserved.
