# A Multi-Modal Genomic Analysis of Beta-Lactam Resistance Mechanisms in Five Clinical *E. coli* Isolates

---

### Project Context and Collaborators
- This project was conducted in collaboration with Ashoka University and a partner hospital.
- Five clinical isolates of *Escherichia coli* were collected directly from patient samples at the hospital, sequenced, and analyzed to understand their resistance to beta-lactam antibiotics.
- The isolates represented multidrug-resistant (MDR) strains and were chosen based on clinical resistance patterns observed in routine healthcare diagnostics.

### Main Objective
- To determine whether resistance to beta-lactam antibiotics (including carbapenems, cephalosporins, and monobactams) in these isolates is due to:
  - Mutations in penicillin-binding protein 3 (PBP3, encoded by *ftsI*), especially insertions or substitutions.
  - The presence of acquired antibiotic resistance genes (ARGs), specifically beta-lactamase genes.
  - Additional mechanisms, such as efflux pump systems.

### Methods Overview
- **Sample Processing & Sequencing:**
  - Five clinical *E. coli* isolates were cultured and subjected to whole-genome sequencing.
  - High-quality genomic assemblies were generated for downstream analyses.
- **Genome Annotation:**
  - Genomes annotated using *Prokka*; extraction of PBP genes (PBP1a, PBP1b, PBP2, PBP3, PBP4, PBP5, PBP6).
- **PBP Gene Extraction & Mutation Analysis:**
  - Extracted PBP genes via Biopython scripts.
  - Multiple sequence alignment (MSA) against wild-type *E. coli* references to detect mutations.
- **Resistance Gene & Efflux System Detection:**
  - Used ResFinder and CARD-RGI to identify resistance genes and efflux pumps.
- **Phenotypic Correlation:**
  - Compared genomic findings with AST results, focusing on beta-lactams and aztreonam/avibactam.

### Key Findings
- **Genomic Mutation:**
  - Identified a 12-bp insertion (ATTAACTGACGA) in the PBP3 gene of all isolates.
  - Other PBP mutations are less consistent.
- **Resistance Genes:**
  - Detection of multiple beta-lactamases: **blaNDM-5, blaCMY-42, blaCTX-M-15, blaTEM-1B**.
- **Efflux and Other Mechanisms:**
  - Presence of RND family efflux pump genes.
- **Phenotype-Genotype Concordance:**
  - Resistance profile matches presence of PBP3 insertion and beta-lactamases.
  - High-level resistance to aztreonam and carbapenems observed.

### Conclusion
- Resistance is multifactorial, involving PBP3 insertion mutation, multiple beta-lactamase enzymes, and efflux systems.
- PBP3 insertion is likely a key contributor to aztreonam-avibactam resistance.
- Findings stress the need for genomic surveillance and alternative therapies.

### Project Credits
- Work conducted via collaboration of Ashoka University and hospital clinical teams.
- Computational analyses using Prokka, Biopython, ResFinder, and CARD.
- The results inform clinical antibiotic stewardship and further research.
