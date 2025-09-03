***************************************************************************
*    A Multi-Modal Genomic Analysis of Beta-Lactam Resistance Mechanisms in Five Clinical *E. coli* Isolates  *                                
***************************************************************************

* **Project Context and Collaborators**
  * This project was conducted in collaboration with Ashoka University and a partner hospital.
  * Five clinical isolates of *Escherichia coli* were obtained from hospital patients. These were sequenced and analyzed to investigate multidrug resistance to beta-lactam antibiotics, informed by AST results.

* ****************************************************************************

* **Main Objective**
  * To determine the genetic mechanisms (with a focus on PBP3 mutations, beta-lactamase genes, and efflux pumps) underlying resistance to various beta-lactams, using genome sequencing and annotation.

* ****************************************************************************

* **Methods Overview**
  * *Sample Processing & Sequencing:*
    * Five clinical MDR *E. coli* isolates underwent short-read sequencing to facilitate high-quality genome assembly.
  * *Antibiotic Sensitivity Testing and Phenotype:*
    * Antimicrobial resistance profiles were generated for all clinical isolates:
      <img src="images/Cultural%20Sensitivity%20Report%20&%20Resistance%20Profile.jpg" width="600"/>
  * *Genome Annotation & Protein Identification:*
    * Genome features (e.g., candidate penicillin-binding protein genes) were predicted and annotated.
      <img src="images/Proteins%20found%20in%20the%20E.%20Coli%20Sample%201.jpg" width="600"/>
  * *Resistance Gene and Efflux Pump Screening:*
    * ResFinder and CARD-RGI were used to screen for acquired resistance genes and efflux-related mechanisms.
      <img src="images/ResFinder%20&%20CARD-RGI%20Results%20.png" width="600"/>

* ****************************************************************************

* **Key Findings**

 * *PBP3 Sequence of E. Coli Sample 1:*
      <img src="images/PBP3%20Sequence.jpg" width="600"/>

  * *Genomic Mutation in PBP3:*
    * All five clinical isolates showed a 12-bp insertion in the PBP3 gene (*ftsI*), identified by alignment and visualized below.

      <img src="images/PBP3%20INSERTION%20IN%20THE%20PROKKA%20ANNOTATED%20E.%20COLI%20SAMPLE.jpg" width="600"/>

    * BLAST alignments confirmed the exact nature of the insertion.
      <img src="images/BLAST%20Result%20Analysis.jpg" width="600"/>

  * *Acquired Beta-Lactamase Genes:*
    * Multiple beta-lactamase genes conferring resistance to third-generation cephalosporins and carbapenems (incl. blaNDM-5, blaCMY-42, blaCTX-M-15, blaTEM-1B) were detected:
      <img src="images/ResFinder%20Analysis%20Results.jpg" width="600"/>

  * *Efflux Pumps and Additional Mechanisms:*
    * CARD-RGI detected resistance-nodulation-cell division (RND) efflux pumps contributing to the MDR phenotype:
      <img src="images/CARD-RGI%20Analysis%20Results.jpg" width="600"/>

  * *Phenotype-Genotype Concordance:*
    * Every isolate was resistant to aztreonam, carbapenems, and other beta-lactams—demonstrating full concordance between genotype and clinical AST:

      <img src="images/Cultural%20Sensitivity%20Report%20&%20Resistance%20Profile.jpg" width="600"/>

* ****************************************************************************

* **Conclusion**
  * Resistance to beta-lactams in these hospital-derived *E. coli* isolates is driven by a combination of a consistent PBP3 insertion mutation, multiple potent beta-lactamases, and efflux pumps.
  * The PBP3 insertion correlates with broad resistance, including to aztreonam-avibactam.
  * Results highlight the urgent need for routine molecular surveillance and the development of alternative therapies for MDR infections.

* ****************************************************************************

* **Project Credits**
  * Analyses by Ashoka University, hospital faculty, and clinical teams.
  * Core tools: Prokka, Biopython, ResFinder, CARD-RGI.
  * Work supports scientific advancement in clinical antimicrobial resistance research.

***************************************************************************
