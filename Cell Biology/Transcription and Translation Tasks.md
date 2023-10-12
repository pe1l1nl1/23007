### Tasks for understanding TRANSCRIPTION and TRANSLATION

**Task 1. Understanding the complementarity principle.**
1. a) Write down what would the complementary strand look like:
DNA:

- plus strand (leading): 5’ - TAC TAC GGT AGG TAT ACC TTG - 3’  (template)
- minus strand (lagging): 3’ - ATG ATG CCA TCC ATA TGG AAC - 5‘ (coding)

```text

- Watson = Sense = Plus Strands = Template strand
- Crick = Antisense = Negative Strands = Coding strand

The strand names actually depend on which direction you are writing the sequence that contains the information for proteins (the "sense" information), not on which strand is on the top or bottom (that is arbitrary). The only real biological information that is important for labeling strands is the location of the 5' phosphate group and the 3' hydroxyl group because these ends determine the direction of transcription and translation. A sequence 5' CGCTAT 3' is equivalent to a sequence written 3' TATCGC 5' as long as the 5' and 3' ends are noted. If the ends are not labeled, convention is to assume that the sequence is written in the 5' to 3' direction. Watson strand refers to 5' to 3' top strand (5' → 3'), whereas Crick strand refers to 5' to 3' bottom strand (3' ← 5').[4] Both Watson and Crick strands can be either sense or antisense strands depending on the gene whose sequences are displayed in the genome sequence database. For example, YEL021W, an alias of URA3 gene used in NCBI database, defines that this gene is located on the 21st open reading frame (ORF) from the centromere of the left arm (L) of Yeast (Y) chromosome number V (E), and that the expression coding strand is Watson strand (W). YKL074C defines the 74th ORF to the left of the centromere of chromosome XI and denotes coding strand from the Crick strand (C). Another confusing term referring to "Plus" and "Minus" strand is also widely used. Whatever the strand is a sense (positive) or antisense (negative), the default query sequence in NCBI BLAST alignment is "Plus" strand.

A DNA molecule is double-stranded. One strand of the molecule is the template strand and one is called the coding strand. 

template:
ACACGGCTTAA
TGTGCCGAATT
coding:

The bases will always pair A with T and C with G.

When the RNA polymerase transcribes the DNA it reads only the template strand. It will pair the appropriate nucleotides with their partners on the template strand of DNA using A, C, G and U (U replaces T in RNA)

template:
ACACGGCTTAA
UGUGCCGAAUU
RNA:
```

2. b) Transcribe the DNA sequence given above into a mRNA (hint: you should pay attention to which of the two strands is actually transcribed?)
- the template strand is transcribed
- mRNA: 3’ - AUG AUG CCA AUA UGG AAC - 5’

```text

In transcription, the DNA sequence of a gene is "rewritten" in RNA. In eukaryotes, the RNA must go through additional processing steps to become a messenger RNA or mRNA.

In translation, the sequence of nucleotides in the mRNA is "translated" into a sequence of amino acids in a polypeptide (protein chain).


- A single strand of a nucleic acid molecule has a phosphoryl end, called the 5′-end, and a hydroxyl or 3′-end. These define the 5′→3′ direction.

- There are three reading frames that can be read in this 5′→3′ direction, each beginning from a different nucleotide in a triplet. In a double-stranded nucleic acid, an additional three reading frames may be read from the other, complementary strand in the 5′→3′ direction along this strand.

- As the two strands of a double-stranded nucleic acid molecule are antiparallel, the 5′→3′ direction on the second strand corresponds to the 3′→5′ direction along the first strand.
```
**Task 2. Understanding translation (use the printouts of Genetic code tables).**
- a) Translate the given mRNA molecules into an amino acid sequence (hint: first codon starts at 1st nucleotide, i.e., first reading frame)! You can use either the 1-letter or 3-letter code, or both!
  
1. AUG GGG AUU GUA CUA ACU UGC CAC CGC UAA
- Met, Gly, Ile, Val, Leu, Thr, Cys, His, Arg, Stop.
   
2. GGG AAC UUC UGG CAG GUU CCC AGG UCU UAG
- Gly, Asn, Phe, Trp, Gin, Val, Pro, Arg, Ser, Stop.

How would example No. 2. above look if you translated it in the second reading frame?
 G] [GGA] [ACU] [UCU] [GGC] [AGG] [UUC] [CCA] [GGU] [CUU] [AG
 Gly Thr Ser Gly Arg Phe Pro Gly Leu  
 GTSGRFPGL

- b) By using the genetic code table, write down the possible nucleotide sequence that has been encoded for the given peptide!


1. Met-Val-Ile-Leu-Ser-Ser-Ala-Trp-Stop
- AUG GUU/GUC/GUA/GUG AUU/AUC/AUA CUU/CUC/CUA/CUG UCU/UCC/UCA/UCG UCU/UCC/UCA/UCG GCU/GCC/GCA/GCG UGG UAA/UAG/UGA
  
2. M-W-G-E-P-R-L-L-*
Met- Trp - Gly -Glu- Pro- Arg - Leu- Leu
ATG TGG GGT/GGC/GGA/GGG GAA/GAG 


![image](https://github.com/pe1l1nl1/23007/assets/19546253/38e4975c-b74f-4218-bf45-df189beeda91)



**Task 3. The codon/anticodon issue.**

Fill in the anticodons based on the given codons. Name the second amino acid. (Hint: use the genetic code tables and the example of the first anticodon given in the table).


| Amino Acid   | Possible codon (5’-3’)  | Corresponding Possible Anticodon (3’-5’) |
|--------------|-------------------------|------------|
| Threonine    |   ACU                   |UGA         |
|              |   ACC                   |UGG         |
|              |   ACA                   |UGU         |
|              |   ACG                   |UGC         |
  Alanine      |   GCU                   |CGA         |
|              |   GCC                   |CGG         |
|              |   GCG                   |GGA         |
|    Proline   |   CCU                   |GGG         |
|              |   CCC                   |GGG         |
|              |   CCA                   |GGU         |
|              |   CCG                   |GGC         |
