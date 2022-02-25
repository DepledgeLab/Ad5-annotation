# Ad5-annotation
"Novel splicing and open reading frames revealed by long-read direct RNA sequencing of adenovirus transcripts"

This repository contains files related to the recent re-annotation of Adenovirus strain Ad5 described here - https://www.biorxiv.org/content/10.1101/2019.12.13.876037v1

Description of files:

Ad5_v10.0_forward.gff3 - GFF3 file denoting all Ad5 transcripts annotated on the top strand of adenovirus strain Ad5
Ad5_v10.0_reverse.gff3 - GFF3 file denoting all Ad5 transcripts annotated on the top strand of adenovirus strain Ad5
Adenovirus-Ad5-AC_000008.1.fasta - original Ad5 genome sequence (Genbank accession AC_000008.1)
Ad5_CHOP.fasta - corrected genome sequence of Ad5 variant used in this study. 

Notes:

Users should ensure the header line in the genome fasta file matches the text used in column #1 of the GFF3 files prior to perform alignment and any downstream analyses

The mRNAs E3.19K and E3.CR1 are identical in terms of sequence and the transcript annotations differ only in the encoded CDS. We thus recommend removing E3.CR1 before performing transcriptome-level alignments.

