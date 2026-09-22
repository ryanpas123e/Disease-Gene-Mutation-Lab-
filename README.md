# Disease-Gene-Mutation-Lab

## Student Information

**Name:** Mark Ryan Pasculado  
**Disease/Phenotype:** Lynch syndrome  
**Gene:** MSH2  
**Reference Transcript:** NM_000251.3  
**Reference Protein:** NP_000242.1  
**Documented Variant:** NM_000251.3(MSH2):c.942+3A>T  
**ClinVar Accession:** RCV000030256.15  
**Galaxy History:** Pasculado_Lynch_syndrome_MSH2_Mutation_Lab  
**Date of Analysis:** September 22, 2026  

## Project Overview

This laboratory investigation examines the relationship between an MSH2
variant and its predicted protein-level consequence in Lynch syndrome.

The documented variant, c.942+3A>T, is an intronic splice-site variant
associated with exon 5 skipping. The resulting transcript consequence was
modeled computationally by removing the corresponding 150 nucleotides from
the coding sequence.

An additional artificial three-nucleotide deletion was introduced into the
MSH2 coding sequence to examine the effect of a small in-frame deletion.

## Computational Workflow

The sequences were analyzed using Galaxy. Coding sequences were translated
to predicted protein sequences, and protein sequences were compared using
EMBOSS Needle.

The workflow included:

1. Translation of the wild-type MSH2 CDS
2. Translation of the documented mutant CDS
3. Translation of the artificial mutant CDS
4. WT protein versus reference protein comparison
5. WT protein versus documented mutant comparison
6. WT protein versus artificial mutant comparison
