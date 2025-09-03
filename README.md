***************************************************************************
*    A Multi-Modal Genomic Analysis of Beta-Lactam Resistance Mechanisms   *
*     in Five Clinical E. coli Isolates        *
***************************************************************************

* **Project Context and Collaborators**
  - This project was conducted in collaboration with Ashoka University and a partner hospital.
  - Five clinical isolates of *Escherichia coli* were collected directly from patient samples at the hospital, sequenced, and analyzed to understand their resistance to beta-lactam antibiotics.
  - The isolates represented multidrug-resistant (MDR) strains and were chosen based on clinical resistance patterns observed in routine healthcare diagnostics.

****************************************************************************

* **Main Objective**
  - To determine whether resistance to beta-lactam antibiotics (including carbapenems, cephalosporins, and monobactams) in these isolates is due to:
    * Mutations in penicillin-binding protein 3 (PBP3, encoded by *ftsI*), especially insertions or substitutions.
    * The presence of acquired antibiotic resistance genes (ARGs), specifically beta-lactamase genes.
    * Additional mechanisms, such as efflux pump systems.

****************************************************************************

* **Methods Overview**

  * **Sample Processing & Sequencing:**
    - Five clinical *E. coli* isolates were cultured and subjected to whole-genome sequencing.
    - High-quality genomic assemblies were generated for downstream bioinformatics analyses.

  * **Genome Annotation:**
    - Genomes were annotated using *Prokka* to identify coding sequences, resistance determinants, and PBP genes.
    - Special focus was placed on extracting genes encoding PBPs: PBP1a, PBP1b, PBP2, PBP3 (ftsI), PBP4, PBP5, and PBP6.

  * **PBP Gene Extraction & Mutation Analysis:**
    - Biopython-based custom scripts were used to extract all PBP genes from each annotated genome.
    - Multiple sequence alignment (MSA) was performed against wild-type *E. coli* reference sequences to identify mutations, with particular attention to insertions, deletions, and point mutations in PBP3.
    - Alignments were visually inspected to confirm notable changes relative to the reference.

  * **Resistance Gene & Efflux System Detection:**
    - ResFinder was used to screen for acquired ARGs, with a particular focus on beta-lactamases (e.g., NDM, CMY, CTX-M, TEM types).
    - The Comprehensive Antibiotic Resistance Database (CARD) Resistance Gene Identifier (RGI) tool was also employed to confirm findings and screen for efflux pumps and other resistance mechanisms.

  * **Phenotypic/Genotypic Correlation:**
    - AST (Antibiotic Sensitivity Testing) results from the clinical microbiology lab were compared with genotypic findings for each isolate, focusing on beta-lactam and aztreonam/avibactam resistance.

****************************************************************************

* **Key Findings**

  * *Genomic Mutation Analysis:*
    - In all five clinical isolates, a **12-bp insertion (ATTAACTATCGA)** was found in the PBP3 (ftsI) gene, not present in the reference genome.
    - The presence of this insertion and a few other subtle mutations is predicted to disrupt beta-lactam/monobactam binding, contributing directly to aztreonam-avibactam resistance.
    - Other PBP genes were also analyzed. Some harbored individual mutations, but changes in PBP3 were most consistent and significant.

  * *Antibiotic Resistance Genes (ARGs):*
    - Several high-impact, horizontally-acquired beta-lactamase genes were identified:
      - **blaNDM-5** – Metallo-β-lactamase conferring resistance to carbapenems, cephalosporins, and penicillins.
      - **blaCMY-42** – AmpC-type β-lactamase with extended-spectrum activity.
      - **blaCTX-M-15** – ESBL (Extended-Spectrum Beta-Lactamase) active against cephalosporins.
      - **blaTEM-1B** – Hydrolyzes penicillins, aminopenicillins.
    - The presence of multiple beta-lactamases in all isolates correlates with observed resistance to nearly all beta-lactams during clinical testing.

  * *Efflux-Mediated and Additional Resistance:*
    - CARD-RGI results revealed resistance-nodulation-cell division (RND) **efflux pump genes** in each isolate.
    - These efflux systems likely contribute to resistance across various antibiotic classes, enhancing the MDR phenotype.

  * *Phenotype/Genotype Concordance:*
    - Clinical AST results showed resistance to aztreonam, avibactam, and virtually all tested beta-lactams in every isolate, matching genotypic predictions.
    - No isolate was found to be susceptible to last-resort beta-lactams, indicating critical clinical concern.

****************************************************************************

* **Conclusion and Implications**

  - Resistance in these five clinical *E. coli* isolates is **multi-factorial**, involving:
    * A unique and consistent PBP3 insertion mutation, likely disrupting drug binding.
    * The presence of multiple potent β-lactamase enzymes (NDM-5, CMY, CTX-M, TEM).
    * Widespread efflux pump systems.
  - The **PBP3 mutation** shows a strong correlation with resistance to aztreonam/avibactam, as recently described in clinical studies of emerging MDR E. coli.
  - These results highlight the need for combined molecular and phenotypic surveillance in managing hospital antibiotic resistance.
  - Standard beta-lactam therapies, including those with avibactam, are predicted to be largely ineffective; novel or combination therapies must be considered.
  - This research demonstrates the power of genomics and bioinformatics in unraveling the complex genetic architecture of antimicrobial resistance.

****************************************************************************

* **Project Credits**
  - Genomic analyses, annotation, and mutation detection performed at Ashoka University under faculty and hospital collaboration.
  - Custom bioinformatics pipelines utilized (Prokka, Biopython, ResFinder, CARD RGI).
  - Results will aid clinical teams in antibiotic stewardship and inform further surveillance research.

***************************************************************************
