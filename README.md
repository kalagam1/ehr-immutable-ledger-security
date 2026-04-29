# Enhancing Electronic Health Record Security with Immutable Ledger Databases

**Course:** CPS 592 – Research Topics in Database 
**Institution:** University of Dayton  
**Date:** April 2026  

## Overview
This paper investigates how immutable ledger databases, specifically 
Amazon QLDB and blockchain-based architectures can address the 
fundamental architectural vulnerability that makes traditional RDBMS 
systems susceptible to ransomware attacks on healthcare data.

## Key Topics Covered
- Ransomware threat landscape in healthcare (2016–2024 data)
- Why traditional RDBMS architecture creates vulnerability
- How append-only cryptographic ledgers work
- Real-world implementation: Team fEMR + Amazon QLDB
- HIPAA compliance considerations
- Performance and scalability trade-offs
- Comparative security analysis: RDBMS vs Immutable Ledgers

## Key Argument
The mutability of traditional relational databases is not a 
configuration flaw — it is an inherent architectural property that 
ransomware directly exploits. Immutable ledger databases eliminate 
this attack vector at the storage layer through append-only design 
and cryptographic hash chaining.

## Files
- `EHR_ImmutableLedger_Paper.pdf` — Full research paper
- `references.md` — All 13 references with working links

## Disclaimer
This paper was written for academic purposes as part of CPS 592 
at the University of Dayton. It is not intended for publication.
