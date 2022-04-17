Bioinformatics coding challenge was provided by a Institute and in the challenge it is requested to extract and translate several genes with defined coordinates from their chromosome sequences. In this challenge 

Three input files have been provided:

sequences.fasta A FASTA file with two chromosome sequences.
intervals.gff A GFF file with a set of mRNA coordinates for the sequences in sequences.fasta.
standard_code.txt A tab delimited table mapping codons to single letter amino acids.
Using these three files, it is requested to write a non-interactive command line tool that:

Takes the three files as arguments,
Extracts the mRNA sequences from sequences.fasta given the coordinates in intervals.gff,
Translates all six reading frames of the mRNA sequence given the genetic code in standard_code.txt,
Prints the longest translation of each mRNA sequence to standard output in FASTA file format.
When evaluating the code, special attention will be given to the use of clean coding practices, maintainability and extensibility without over-engineering. The output for the given input files can be found in genes.fasta. Your solution will also be tested on additional input.