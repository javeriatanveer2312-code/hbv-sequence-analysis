# HBV Sequence Analysis

A beginner Python project analysing the genome of Hepatitis B virus (HBV), a major cause of liver cancer.

## Data
- **Genome:** Hepatitis B virus reference genome, NCBI RefSeq **NC_003977.2**
- **Format:** FASTA, downloaded from NCBI Nucleotide
- **Length:** 3,182 bp

## What the notebook does
1. Loads the HBV DNA sequence as a string
2. Cleans the sequence by removing line breaks and spaces
3. Prints each base with its position
4. Splits the sequence into codons (groups of 3 bases)
5. Finds the first ATG start codon
6. Searches the genome for all ATG start codons
7. Calculates GC content

## Results
- First ATG start codon at position **157**
- **41** ATG start codons found across the genome
- GC content: **48.49%**

## Tools
Python in Google Colab: strings, slicing, `replace()`, `find()`, `count()`, `for` loops, `if` statements and f-strings.

Built as practice for the course *Intro to Python and R Programming for Biologists*.

## Author
**Javeria Tanveer**
Research Associate, Jamil-ur-Rahman Center for Genome Research, ICCBS, University of Karachi
