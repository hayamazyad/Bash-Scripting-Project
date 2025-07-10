# PDB Structure Analysis – Shell Scripting Project
This project demonstrates the use of Linux shell commands to automate the retrieval, filtering, and amino acid frequency analysis of PDB (Protein Data Bank) files.  
The primary objective was to efficiently handle multiple protein structures and extract amino acid residue frequency information using command-line scripting techniques.

<div align="right" style="font-size:16px; color:black; font-family:Segoe UI, sans-serif;">
Developed by Haya Mazyad
    
As part of the *Introduction to scipt programming* course
</div>

---
## Overview
- Protein structures in PDB format are widely available from databases like RCSB. This project simulates real-world scenarios faced by bioinformatics researchers who routinely process and clean structural datasets. The implemented workflow covers:
- Batch downloading PDB files using pattern matching
- Identifying and removing invalid or unavailable files
- Extracting amino acid residues by selecting alpha carbon (CA) atoms
- Calculating residue frequency from processed structural files
- The project highlights the importance of automation, accuracy, and reproducibility in bioinformatics data analysis.

## Tools Used
- Bash Shell (Linux terminal)
- curl
- grep
- cut
- sort
- uniq
- xargs
