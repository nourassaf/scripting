# scripting
project objectives and parts:
Data is a fasta file that contains multiple DNA sequences. These sequences are made up of upper and lower cases. The upper cases indicate exons, the lower cases indicate introns. As you might know, only the exons are translated and transcribed to proteins based on the codon mapping. Each 3 nucleotides map for one amino acid. Each sequence has its own ID and header starting with “>”.
These were printed out, computed, organized and categorized as exons and introns. The proportion of each aminoacid was also calculated


In part 2. sequences had 2 exons and one intron. The lower case before the first exon and after that last exon are not considered as introns but rather upper stream and lower stream sequences. The script prints out a table (tab delimited) with proper spacing indicating the following :
headlines of table: SequenceID
#Exons
#Introns
AvgExonLength
AvgIntronLeng
%A in Exon 
%C In Exon 
%G In Exon 
%T In Exon 
%A in Intron 
%C In Intron 
%G In Intron 
%T In Intron

Part 3 is user friendly,can take in any sequence provided and prints out the statistics of any file provided,checks for errors from user and double checks the accuracy of the aminoacids entered.
The program also calculated different probabilities of mRNA sequences according to the the DNA sequence provided and the peptide protein sequence that corresponds to it. The mRNA is the combination of all the exons for that sequence.
the RANGE and AVERAGE of melting temperature of the primers for that sequence. the melting temperature wa computed using the following formula Tm = ( A + T ) ´ 2°C + ( C + G ) ´ 4°C  then the Range, minmax, and the average are printed

