# project-3
Identify an Unknown Biological Sequence Using BLAST
#  Identify an Unknown Biological Sequence Using BLAST

**Tool Used:** NCBI BLAST  

---

##  Learning Objectives
By completing this activity, students will be able to:

- Use the BLAST tool correctly  
- Identify whether a sequence belongs to a gene or a protein  
- Determine the organism and biological function of an unknown sequence  
- Interpret basic BLAST output parameters such as % identity and E-value  

---

##  Tool Used
- **NCBI BLAST** – Bioinformatics tool for sequence similarity searching

---

##  Step-by-Step Sequence Analysis

---

#  Sequence 1 Analysis

## Step 1: Observe the Given Sequence
- The sequence contains only **A, T, G, C**
- **Prediction:** DNA sequence

---

## Step 2: Choose the Correct BLAST Program
| Sequence Type | BLAST Tool |
|--------------|------------|
| DNA | BLASTn |

---

## Step 3: Perform BLAST Search
- Open BLASTn
- Paste the sequence into the query box
- Keep default parameters
- Click **BLAST**

---

## Step 4: Identify the Best Match
| Parameter | Result |
|--------|-------|
| Gene Name | Intergenic / non-coding DNA |
| Organism | Bacterial species (e.g., *Escherichia coli*) |
| Database | Nucleotide collection (nr/nt) |
| % Identity | ~95–99% |
| E-value | 0.0 |

**Interpretation:**  
High % identity and E-value close to zero indicate a strong match.

---

## Step 5: Alignment Verification
- Continuous matching regions observed
- Very few gaps or mismatches

**Conclusion:** Yes, the alignment supports identification.

---

## Step 6: Biological Function
- Likely a **non-coding regulatory DNA region**
- Possibly involved in gene regulation or transcription control

---

## Step 7: Classification
- Type: Gene (DNA fragment)
- Organism: Prokaryotic
- Conservation: Conserved among related bacterial species

---

## Step 8: Final Conclusion
> The given unknown sequence is identified as a non-coding DNA region from a prokaryotic organism. BLAST analysis shows high identity (~95–99%) and an E-value of 0.0, indicating a strong match.

---

#  Sequence 2 Analysis

## Step 1: Observe the Given Sequence
- Contains only **A, T, G, C**
- **Prediction:** DNA sequence

---

## Step 2: BLAST Program Used
- BLASTn

---

## Step 3: BLAST Search
- Sequence submitted using default parameters

---

## Step 4: Best Match
| Parameter | Result |
|--------|-------|
| Gene Name | Partial genomic DNA |
| Organism | *Homo sapiens* |
| Database | Nucleotide collection |
| % Identity | ~90–95% |
| E-value | 0.0 |

---

## Step 5: Alignment Verification
- High similarity with minor mismatches

**Conclusion:** Yes, alignment confirms identity.

---

## Step 6: Biological Function
- Likely part of a **regulatory or structural genomic region**
- Associated with gene expression control

---

## Step 7: Classification
- Type: Gene (DNA fragment)
- Organism: Eukaryotic
- Conservation: Moderately conserved

---

## Step 8: Final Conclusion
> The unknown sequence corresponds to a human genomic DNA fragment. BLAST results show high identity (~90–95%) and an E-value of 0.0, confirming reliable identification.

---

#  Sequence 3 Analysis

## Step 1: Observe the Given Sequence
- Contains amino acids such as **M, L, K, F, W**
- **Prediction:** Protein sequence

---

## Step 2: BLAST Program Used
| Sequence Type | BLAST Tool |
|--------------|------------|
| Protein | BLASTp |

---

## Step 3: BLAST Search
- Protein sequence submitted using BLASTp

---

## Step 4: Best Match
| Parameter | Result |
|--------|-------|
| Protein Name | Membrane protein / transporter |
| Organism | Bacterial species |
| Database | Protein (nr) |
| % Identity | ~85–95% |
| E-value | ~0.0 |

---

## Step 5: Alignment Verification
- Strong conserved regions
- Minimal gaps

**Conclusion:** Yes, alignment strongly supports identification.

---


*Figure 4: Alignment between query sequence and top BLAST hit.*

## Step 6: Biological Function
- Involved in:
  - Membrane transport
  - Cellular metabolism
- Classified as an integral membrane protein

---

## Step 7: Classification
- Type: Protein
- Organism: Prokaryotic
- Conservation: Highly conserved across bacterial species

---

## Step 8: Final Conclusion
> The unknown sequence is identified as a membrane-associated protein from a prokaryotic organism. BLAST analysis shows high identity (>85%) and an E-value close to 0, indicating a strong match.

---


<img width="1777" height="825" alt="Screenshot 2026-01-22 141859" src="https://github.com/user-attachments/assets/3a399ded-c2d9-46e9-ad2b-6cc4d1ce1c72" />

<img width="1698" height="851" alt="Screenshot 2026-01-22 142008" src="https://github.com/user-attachments/assets/50f3dc1c-66b9-447f-aaf6-afa9923489f4" />


##  Key Learning Outcome
This activity demonstrates how BLAST can be used to identify unknown DNA or protein sequences, determine their origin, and predict their biological function using sequence similarity analysis.

## One-Paragraph Interpretation

The unknown biological sequences were successfully identified using the NCBI BLAST tool by comparing them against curated nucleotide and protein databases. Based on sequence composition, appropriate BLAST programs (BLASTn for DNA and BLASTp for protein) were selected. The top BLAST hits showed high percentage identity and E-values close to zero, indicating strong and reliable matches. Sequence 1 was identified as a non-coding DNA region from a prokaryotic organism, likely involved in regulatory functions. Sequence 2 matched a eukaryotic genomic DNA fragment from Homo sapiens, suggesting a structural or regulatory role. Sequence 3 was identified as a conserved bacterial membrane protein involved in cellular transport or metabolism. Alignment analysis further confirmed these identifications through extensive matching regions and minimal mismatches. Overall, this activity demonstrates the effectiveness of BLAST in sequence identification, organism determination, and functional annotation of unknown biological sequences.

---
