# Ad5-annotation
"Novel splicing and open reading frames revealed by long-read direct RNA sequencing of adenovirus transcripts"

This repository contains files related to the recent re-annotation of Adenovirus strain Ad5 described [in our recent PLoS Pathogens paper](https://journals.plos.org/plospathogens/article?id=10.1371/journal.ppat.1010797). If you use this annotation, please cite this paper.

Description of files:

Ad5_v10.1_forward.gff3 - GFF3 file denoting all Ad5 transcripts annotated on the top strand of adenovirus strain Ad5

Ad5_v10.1_reverse.gff3 - GFF3 file denoting all Ad5 transcripts annotated on the top strand of adenovirus strain Ad5

Ad5_v10.1.complete.fasta - multi-fasta file containing the nucleotide sequences for all Ad5 transcripts present in our v10.1 annotation

Adenovirus-Ad5-AC_000008.1.fasta - original Ad5 genome sequence (Genbank accession AC_000008.1)

Ad5_CHOP.fasta - corrected genome sequence of Ad5 variant used in this study. 

OlderVersions/ - folder containing prior versions of the Ad5 annotation

*Last update: 24.06.2023*

Notes:

Users should ensure the header line in the genome fasta file matches the text used in column #1 of the GFF3 files prior to perform alignment and any downstream analyses

The mRNAs E3.19K and E3.CR1 are identical in terms of sequence and the transcript annotations differ only in the encoded CDS. We thus recommend removing E3.CR1 before performing transcriptome-level alignments.

