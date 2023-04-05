![image](https://user-images.githubusercontent.com/65184350/229837923-8815daae-fdcc-45fe-8e59-e5e78e580ed4.png)

# **Resource of AF2 predicted structures of autophagy pathway**
***
Welcome to our GitHub repository! Here, we present a resource package that utilizes AlphaFold2, a state-of-the-art deep learning model, for improving the structural spectrum of autophagy proteins. The protein structural bandwidth of multiple proteomes has been greatly improved with the release of Google DeepMind’s AI-driven AlphaFold (https://github.com/deepmind/alphafold) which can be utilized as an open-source tool .This  has significantly improved structural coverage of the proteins, which earlier lacked atomistic resolution with reasonable confidence, over previous protein prediction methods. Using this tool, we have analysed the autophagic interactome, which is comprised of key autophagic proteins and several interacting partners.

With AF2 It is now possible to explore and predict the structures of monomeric and multimeric protein complexes that were previously not accessible. 
This user-friendly framework called Resource of AF2 predicted structures of autophagy pathway contains structural information on the proteins that are involved in the autophagic process. Moreover, the resource contains predicted protein structures that can be downloaded and utilized for further analysis and study, facilitating understanding of autophagic processes. With the help of our resource, researchers can comprehensively analyse the protein structures, and potentially use them for drug development and other research inferences. We are excited to share this resource with the scientific community and hope that it can contribute to further advances in the structural understanding of proteins and aid researchers in gaining a comprehensive view of the structural basis of protein-protein interactions involved in the autophagic process.


![RAPSAP_Fig](https://user-images.githubusercontent.com/65184350/229787425-64bf8d7b-4fa6-46c0-8623-86a652d126a1.png)


## **Contents**
***
* Autophagic Protein Interactome contains information on mammalian autophagic proteins’  comprising structural data which  is in two separate folders. To determine the structural bandwidth in the network of interactions between autophagic proteins, these proteins have been evaluated based on their structural coverage. The first folder includes the structural data in .pdb format for all the proteins that have a structural coverage of less than 90 percent. The second folder, on the other hand, contains the structural data for the remaining proteins with a structural coverage of 90 percent or more. Additionally, a table highlighting relevant information about each protein is also provided.

* Core Autophagic proteins directory contains list of key autophagic proteins. Each folder contains a comprehensive list of proteins categorized into high, medium, and low structures based on the percentage of atomistic resolution available for each protein. The inclusion of a table of proteins in the folder provides a convenient and organized way to access information on the Core Autophagic proteins.

* The Multimer directory contains protein models generated by the standalone AF2 program, including structures of the ATG7-ATG10 complex. The top 5 ranked structures are available for download to serves as a resource for investigating the structure and dynamics of multimer proteins, particularly the ATG7-ATG10 complex. To further understand the dynamics of the tetramer assembly, we conducted molecular dynamics simulations of the ATG7-ATG10 tetramer. This allowed us to identify three critical interactions that crucial for interaction which were further mutated to understand the disruptions.We also included both wildtype and mutant ATG7-ATG10 tetramer structures at different time steps, providing insight into the evolution of protein assembly in the tetramer.


* Three different proteins, ATG2, ATG10, and ATG14, are represented by a collection of.pdb files in the "Simulation of High Confidence Structures" folder. These proteins are arranged into distinct subfolders, each of which contains .pdb structural files that reflect their conformational states along a trajectory of 1 microsecond and at various timescales. This repository will make it possible to thoroughly investigate and analyse the structural characteristics of these proteins.


### **Downloading RAPASAP repository and Usage**

1. git clone into the RAPSAP repository into your home directory 

2. cd into your working directory. This is where you can find all the PDBs segreagated  
       
3. You  can view and analyse them using any interactive and molecular visualization tools like vmd, chimeraX etc.



#### **Acknowledgments**
***
This project was made possible through the use of AlphaFold, developed by DeepMind. We thank the AlphaFold team for their work and contributions to the field of protein structure prediction. We also acknowledge the support from CSIR-IGIB for infrastructure and supercomputing facilities.


**Get in Touch**

If you have any questions or queries please contact the CSB team at lipi.thukral@igib.in

#### Citing RAPSAP

If you use this software in your publication please cite:


**Thank You**
