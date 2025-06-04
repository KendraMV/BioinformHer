# HBB Gene Evolutionary Conservation Project

## Overview

This project investigates the evolutionary conservation of the Hemoglobin Subunit Beta (HBB) gene across six species. The project includes sequence retrieval, BLAST searches, pairwise sequence alignment, multiple sequence alignment, sequence logo generation, and phylogenetic tree construction.

## Project Tasks

1.  **Sequence Retrieval & BLAST Search:**
    *   The human HBB gene sequence was retrieved from the NCBI gene database by searching for "human HBB" and selecting the entry with the description "hemoglobin subunit beta [Homo sapiens (human)]".
    *   The protein reference sequence (NP_000509.1) was selected from the NCBI Reference Sequences section.
    *   A BLAST search was performed using the reference sequence, excluding *Homo sapiens*, with the maximum target sequence parameter increased to 250.
    *   The following species were analyzed:

        | Species Name          | Accession Number   | % Identity with Human HBB |
        | :-------------------- | :----------------- | :------------------------ |
        | *Pan paniscus*        | XP\_003819077.1    | 100                       |
        | *Gorilla gorilla gorilla* | XP\_018891709.1    | 99.32                     |
        | *Pongo abelii*        | XP\_002822173.1    | 98.64                     |
        | *Nomascus leucogenys*   | XP\_004090697.3    | 97.96                     |
        | *Vulpes vulpes*       | XP\_025844209.1    | 91.16                     |

2.  **Pairwise Sequence Alignment:**
    *   Pairwise sequence alignments were performed between the human HBB sequence and *Pan paniscus* (closely related) and *Vulpes vulpes* (distantly related) sequences.
    *   *Pan paniscus* showed 100% identity with the human HBB sequence, indicating high conservation.
    *   *Vulpes vulpes* showed a lower match percentage, indicating less conservation, as expected due to its more distant relationship to humans.

3.  **Multiple Sequence Alignment (MSA):**
    *   FASTA sequences for the selected species, including human HBB, were used as input for Clustal Omega.
    *   The MSA results highlighted highly conserved regions.

4.  **Sequence Logo Generation:**
    *   The MSA was exported in FASTA format and converted using Seqret.
    *   The converted alignment file was uploaded to Skylign to generate a sequence logo.
    *   The sequence logo displayed highly conserved residues, with taller letters indicating greater conservation, matching the highlighted regions in the MSA.
    *   High conservation in these regions suggests biological significance across the aligned organisms.

5.  **Phylogenetic Tree Construction:**
    *   A phylogenetic tree was constructed, showing *Pan paniscus* (*chimpanzee*) as the most closely related organism to *Homo sapiens* based on the HBB gene.
    *   The tree confirmed the expectation that primates are more closely related to humans than *Vulpes vulpes* (*Red fox*).

## Conclusion

The project successfully investigated the evolutionary conservation of the HBB gene across the selected species, demonstrating the expected relationships based on sequence identity and phylogenetic analysis.
