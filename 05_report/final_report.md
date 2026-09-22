# Investigating the Molecular Basis of Lynch Syndrome: A Sequence Analysis of MSH2 Mutation

**Author:** Mark Ryan Pasculado  
**Institution:** Negros Oriental State University  
**Date:** September 22, 2026

---

## 1. Disease Background

Lynch syndrome is an inherited cancer-predisposition disorder caused by pathogenic variants in genes involved in DNA mismatch repair, including MSH2.

* **Clinical Characteristics:** Lynch syndrome increases the risk of developing colorectal, endometrial, ovarian, stomach, small-intestinal, and urinary-tract cancers.
* **Affected Tissues:** The colon, rectum, endometrium, ovaries, stomach, small intestine, and urinary tract are among the major tissues and organs affected.
* **Genetic Basis & Inheritance:** Lynch syndrome is associated with defects in DNA mismatch repair genes and is inherited in an autosomal dominant pattern.

## 2. Gene and Normal Protein Function

* **Gene Symbol:** MSH2
* **Chromosome Location:** Chromosome 2
* **Protein Encoded:** MSH2 DNA mismatch repair protein
* **Cellular Location:** Primarily in the nucleus.
* **Biological Function:** MSH2 is part of the DNA mismatch repair system. It forms complexes with MSH6 or MSH3 to recognize DNA mismatches and help maintain genome stability.

## 3. Documented Mutation

* **Gene:** MSH2
* **Reference Transcript Accession:** NM_000251.3
* **Reference Protein Accession:** NP_000242.1
* **Exact Variant Notation:** c.942+3A>T
* **Nucleotide Change:** Adenine is substituted by thymine at the +3 position of intron 5.
* **Predicted Protein Consequence:** 50-amino-acid in-frame deletion due to exon 5 skipping.
* **Mutation Type:** Intronic splice-site substitution
* **ClinVar Accession:** RCV000030256.15
* **Clinical Interpretation:** Pathogenic

## 4. Hypothesis

* **Mutation and Nucleotide Change:** c.942+3A>T
* **Predicted Mutation Type:** Splice-site substitution
* **Predicted Effect on Reading Frame:** The modeled 150-nucleotide deletion is expected to preserve the reading frame.
* **Predicted Effect on Protein Length:** The protein is expected to decrease from 934 to approximately 884 amino acids.
* **Predicted Effect on Protein Function:** The 50-amino-acid deletion may affect the DNA-binding region of MSH2 and impair DNA mismatch repair.

## 5. Methods

The normal MSH2 coding sequence (CDS) from NM_000251.3 was obtained in FASTA format and translated using Galaxy. The documented mutation was modeled by removing the 150-nucleotide exon sequence associated with exon 5 skipping. The mutant sequence was translated and compared with the wild-type protein using EMBOSS Needle.

A secondary experiment was performed by introducing an artificial three-nucleotide deletion into the MSH2 CDS. The artificial mutant was translated and compared with the wild-type protein.

## 6. Results

**Wild-Type (WT) Control:**

* CDS Length: 2,805 nucleotides
* Predicted Protein Length: 934 amino acids
* Start Codon: ATG
* Stop Codon: TGA

**Documented Mutant (c.942+3A>T):**

* Mutant CDS Length: 2,655 nucleotides
* Predicted Protein Length: 884 amino acids
* Amino Acids Deleted: 50
* Premature Stop Codon?: No

**Artificial Mutant:**

* Mutant CDS Length: 2,802 nucleotides
* Predicted Protein Length: 933 amino acids
* Premature Stop Codon?: No

## 7. WT versus Mutant Protein Comparison

* **First Amino-Acid Difference:** Position 264.
* **Number of Amino Acids Affected:** Approximately 50 amino acids.
* **Deleted Region:** Amino acids 264–313.
* **Insertions/Deletions:** 50 amino acids were deleted.
* **Reading Frame & Length:** The reading frame was preserved, and protein length changed from 934 to 884 amino acids.
* **Needle Identity:** 885/935 (94.7%).
* **Final Mutation Type Classification:** In-frame deletion at the protein level caused by an intronic splice-site mutation.

## 8. Artificial Mutation Experiment

* **Chosen Artificial Mutation:** Three-nucleotide deletion.
* **WT CDS Length vs Artificial Mutant CDS Length:** 2,805 nucleotides vs 2,802 nucleotides.
* **Protein Length Effect:** The artificial mutant protein was 933 amino acids compared with 934 amino acids in the WT.
* **Reading Frame Effect:** The three-nucleotide deletion preserved the overall reading frame.
* **Comparison to Documented Mutation:** The documented mutation produced a 50-amino-acid deletion, whereas the artificial three-nucleotide deletion produced a much smaller predicted protein-level change.

## 9. Molecular Interpretation

**Mechanism:**  
**Gene → mutation → protein → cellular effect → phenotype**

The MSH2 c.942+3A>T mutation is an intronic splice-site substitution that causes exon 5 skipping. This produces a predicted 150-nucleotide deletion in the coding sequence and a 50-amino-acid in-frame deletion in the MSH2 protein.

The deleted region begins at amino acid 264 and is reported to affect the DNA-binding domain. Alteration of this region may impair MSH2 function in DNA mismatch repair, allowing DNA replication errors to accumulate and contributing to the increased cancer susceptibility associated with Lynch syndrome.

## 10. Limitations

The translation and sequence alignment performed in Galaxy only predict the protein sequence. They do not directly demonstrate RNA splicing, protein expression, protein folding, localization, or protein activity.

The original c.942+3A>T mutation is located in an intron, which is not present in the CDS sequence. Therefore, the experiment modeled its documented exon-skipping consequence by removing the corresponding 150 nucleotides.

## 11. Conclusion

This computational sequence analysis demonstrated that the MSH2 c.942+3A>T variant can be modeled as a 150-nucleotide in-frame deletion, resulting in a predicted 50-amino-acid reduction in the MSH2 protein.

The artificial three-nucleotide deletion preserved the reading frame and produced a much smaller predicted protein change. These results demonstrate how a mutation can be traced from a DNA sequence change to a predicted protein consequence.

## 12. References

1. *Cell and Molecular Biology Laboratory: From Gene Mutation to Disease*. Laboratory Manual.
2. National Center for Biotechnology Information (NCBI). MSH2 Reference Transcript NM_000251.3 and Protein NP_000242.1.
3. NCBI ClinVar. MSH2 c.942+3A>T. ClinVar accession RCV000030256.15.
