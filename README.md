# fasta_unalignr

Author: Murat Buyukyoruk

Associated lab: Wiedenheft lab

# fasta_unalignr help:

This script is developed to unalign a multi sequence alignment if needed. 

SeqIO package from Bio is required to fetch flank sequences. Additionally, tqdm is required to provide a progress bar since some multifasta files can contain long and many sequences.
        
Syntax:

        python fasta_unalignr.py -i demo.fasta

fasta_unalignr dependencies:
 
    Bio module and SeqIO available in this package          refer to https://biopython.org/wiki/Download
    tqdm                                                    refer to https://pypi.org/project/tqdm/
	
Input Paramaters (REQUIRED):
----------------------------
	-i/--input		FASTA			Specify a multi sequence alignment fasta file.

Basic Options:
--------------
	-h/--help		HELP			Shows this help text and exits the run.
	
# Note:
Demo files are available to use with the basic command line provided in syntax section above. Make sure all the dependencies are installed successfully to the python environment.

    demo.fasta                      Includes aligned protein sequences
