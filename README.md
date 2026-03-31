# 🧬 Spirulina-BLAST-Phylogenetic-Analysis

## 📌 Project Overview

This project focuses on the comparative analysis of the 16S rRNA gene sequence of *Arthrospira platensis* (commonly known as Spirulina) using the NCBI BLAST tool. Spirulina is a cyanobacterium widely used as a nutritional supplement and is known for its high protein content and potential health benefits.

---

## 🎯 Objective

* To identify homologous 16S rRNA gene sequences in different microorganisms
* To analyze sequence similarity using BLAST (blastn)
* To study evolutionary relationships using a phylogenetic tree
* To explore closely related microalgae and assess their biological relevance

---

## 🧪 Tools and Databases Used

* NCBI BLAST (blastn)
* NCBI Nucleotide (nr/nt) database
* MEGA Software (for phylogenetic analysis)

---

## 🧬 Sequences Used

The 16S rRNA gene sequence of *Arthrospira platensis* was used as the query. Homologous sequences from closely related cyanobacteria were selected for comparison, including:

* *Arthrospira platensis*
* *Arthrospira maxima*
* *Spirulina subsalsa*
* Other related cyanobacterial species

---

## 🔬 Methodology

1. The 16S rRNA gene sequence of *Arthrospira platensis* was retrieved from the NCBI nucleotide database in FASTA format.
2. BLAST (blastn) was performed against the non-redundant nucleotide database (nr/nt).
3. Top significant hits were selected based on:

   * High percentage identity
   * High query coverage
   * Low E-value
4. Selected sequences were downloaded in FASTA format.
5. Multiple sequence alignment was performed using MUSCLE in MEGA software.
6. A phylogenetic tree was constructed using the Neighbor-Joining (NJ) method.

---

## 📊 Results

### 1. BLAST Analysis

BLAST results showed that *Arthrospira platensis* shares high sequence similarity with other *Arthrospira* species.

* Query coverage: ~99–100%
* Percentage identity: ~97–100%
* E-value range: 1e-103 to 5e-102

These results indicate strong genetic similarity and conservation among closely related cyanobacteria.

---

### 2. Phylogenetic Tree Analysis

The phylogenetic tree constructed using the Neighbor-Joining method illustrates evolutionary relationships among selected organisms.

* *Arthrospira platensis* clustered closely with *Arthrospira maxima*
* Other cyanobacteria formed separate but related branches
* The tree confirms close evolutionary relationships within the genus *Arthrospira*

---

## 🧠 Interpretation

The clustering of *Arthrospira* species in both BLAST results and the phylogenetic tree indicates strong evolutionary conservation of the 16S rRNA gene. This conservation reflects the fundamental role of this gene in ribosomal function and microbial identification.

Closely related species such as *Arthrospira maxima* are also widely studied and considered biologically similar to Spirulina.

---

## ⚠️ Biological Insight

While sequence similarity indicates evolutionary closeness, it does not directly determine safety for consumption. Some cyanobacteria may produce toxins; therefore, only well-studied species like *Arthrospira platensis* are considered safe for dietary use.

---

## ✅ Conclusion

This study demonstrates that BLAST and phylogenetic analysis are effective tools for identifying homologous sequences and understanding evolutionary relationships. Spirulina shows strong similarity with other *Arthrospira* species, supporting its classification and biological consistency.

---

## 📁 Files Included

* `spirulina_sequence.fasta` → Query sequence
* `blast_results.txt` → BLAST output
* `phylogenetic_tree.png` → Phylogenetic tree
* `alignment.meg` → Sequence alignment file

---

## 📚 References

* National Center for Biotechnology Information (NCBI)
* BLAST: Basic Local Alignment Search Tool
* MEGA Software Documentation

---

## 👩‍🔬 Author

Name: *Prakriti Prakash*
Course: B.Tech Biotechnology

