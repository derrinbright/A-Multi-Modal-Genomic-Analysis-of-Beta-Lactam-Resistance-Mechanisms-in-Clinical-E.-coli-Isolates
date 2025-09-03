***************************************************************************
*    A Multi-Modal Genomic Analysis of Beta-Lactam Resistance Mechanisms   *
*    in Five Clinical *E. coli* Isolates                                  *
***************************************************************************

* **Project Context and Collaborators**
  * This project was conducted in collaboration with Ashoka University and a partner hospital.
  * Five clinical isolates of *Escherichia coli* were collected directly from patient samples at the hospital, sequenced, and analyzed to understand their resistance to beta-lactam antibiotics.
  * The isolates represented multidrug-resistant (MDR) strains and were chosen based on clinical resistance patterns observed in routine healthcare diagnostics.

* ****************************************************************************

* **Main Objective**
  * To determine if resistance to beta-lactam antibiotics (including carbapenems, cephalosporins, monobactams) in these isolates is due to:
    * Mutations in penicillin-binding protein 3 (PBP3, encoded by *ftsI*), especially insertions or substitutions.
    * The presence of acquired antibiotic resistance genes (ARGs), specifically beta-lactamase genes.
    * Additional mechanisms such as efflux pump systems.

* ****************************************************************************

* **Methods Overview**

  * *Sample Processing & Sequencing:*
    * Five clinical *E. coli* isolates were cultured and subjected to whole-genome sequencing.

  * *Cultural Sensitivity / AST Data:*

    <img src="images/Cultural%20Sensitivity%20Report.jpg" width="600"/>
  
  * *Protein Annotation Example:*

    <img src="images/Proteins%20found%20in%20the%20E.%20Coli%20Sample%201.jpg" width="600"/>
  
  * *PBP Gene Extraction and Mutation Analysis:*

    <img src="images/PBP3%20Sequence.jpg" width="600"/>
  
    <img src="images/PBP3%20INSERTION%20IN%20THE%20PROKKA%20ANNOTATED%20E.%20COLI%20SAMPLE.jpg" width="600"/>
  
    <img src="images/BLAST%20Result%20Analysis.jpg" width="600"/>

  * *Resistance Gene Identification via ResFinder & CARD-RGI:*

    <img src="images/ResFinder%20%26%20CARD%20RGI%20Results.png" width="600"/>

    <img src="images/ResFinder%20Analysis%20Results.jpg" width="600"/>
  
    <img src="images/CARD%20RGI%20Analysis%20Results.jpg" width="600"/>

* ****************************************************************************

* **Key Findings**

  * *Genomic Mutation:*
    * A 12-bp insertion (ATT… sequence) in PBP3 was observed in all isolates correlating with aztreonam/avibactam resistance.

    <img src="images/PBP3%20INSERTION%20IN%20THE%20PROKKA%20ANNOTATED%20E.%20COLI%20SAMPLE.jpg" width="600"/>
  
    <img src="images/BLAST%20Result%20Analysis.jpg" width="600"/>

  * *Beta-lactamase Genes:*
    * blaNDM-5, blaCMY-42, blaCTX-M-15, blaTEM-1B detected in isolates.

    <img src="images/ResFinder%20%26%20CARD%20RGI%20Results.png" width="600"/>
  
    <img src="images/ResFinder%20Analysis%20Results.jpg" width="600"/>

  * *Efflux Pumps and Additional Resistances:*

    <img src="images/CARD%20RGI%20Analysis%20Results.jpg" width="600"/>

  * *Phenotype-Genotype Concordance:*
    * AST shows resistance profiles matching genomic predictions (see AST image above).

* ****************************************************************************

* **Conclusion**

  * Resistance is driven by:

    * PBP3 insertion mutation affecting drug binding.
    * Multiple acquired beta-lactamases.
    * Efflux pump genes increasing MDR phenotype.

  * Results stress the need for molecular surveillance and alternate therapies beyond traditional beta-lactams.

* ****************************************************************************

* **Project Credits**

  * Analysis by Ashoka University and clinical collaborators.
  * Tools: Prokka, Biopython, ResFinder, CARD-RGI.
  * Outputs aimed to guide antibiotic stewardship and further resistance research.

***************************************************************************
