---
title: "[Preprint] OpenFold: Retraining AlphaFold2 yields new insights into its learning mechanisms and capacity for generalization"
collection: publications
permalink: /publication/2022-11-24-openfold_preprint
excerpt: 'Here we report OpenFold, a fast, memory-efficient, and trainable implementation of AlphaFold2, and OpenProteinSet, the largest public database of protein multiple sequence alignments. We use OpenProteinSet to train OpenFold from scratch, fully matching the accuracy of AlphaFold2. Having established parity, we assess OpenFold&#39;s capacity to generalize across fold space by retraining it using carefully designed datasets.'
date: 2022-11-24
venue: 'bioRxiv'
paperurl: 'https://www.biorxiv.org/content/10.1101/2022.11.20.517210v2'
citation: 'OpenFold: Retraining AlphaFold2 yields new insights into its learning mechanisms and capacity for generalization. Gustaf Ahdritz, Nazim Bouatta, Sachin Kadyan, Qinghui Xia, William Gerecke, Timothy J O’Donnell, Daniel Berenberg, Ian Fisk, Niccolò Zanichelli, Bo Zhang, Arkadiusz Nowaczynski, Bei Wang, Marta M Stepniewska-Dziubinska, Shang Zhang, Adegoke Ojewole, Murat Efe Guney, Stella Biderman, Andrew M Watkins, Stephen Ra, Pablo Ribalta Lorenzo, Lucas Nivon, Brian Weitzner, Yih-En Andrew Ban, Peter K Sorger, Emad Mostaque, Zhao Zhang, Richard Bonneau, Mohammed AlQuraishi; bioRxiv 2022.11.20.517210; doi: https://doi.org/10.1101/2022.11.20.517210'
---
*This paper is a preprint.*  

AlphaFold2 revolutionized structural biology with the ability to predict protein structures with exceptionally high accuracy. Its implementation, however, lacks the code and data required to train new models. These are necessary to (i) tackle new tasks, like protein-ligand complex structure prediction, (ii) investigate the process by which the model learns, which remains poorly understood, and (iii) assess the model's generalization capacity to unseen regions of fold space. Here we report OpenFold, a fast, memory-efficient, and trainable implementation of AlphaFold2, and OpenProteinSet, the largest public database of protein multiple sequence alignments. We use OpenProteinSet to train OpenFold from scratch, fully matching the accuracy of AlphaFold2. Having established parity, we assess OpenFold's capacity to generalize across fold space by retraining it using carefully designed datasets. We find that OpenFold is remarkably robust at generalizing despite extreme reductions in training set size and diversity, including near-complete elisions of classes of secondary structure elements. By analyzing intermediate structures produced by OpenFold during training, we also gain surprising insights into the manner in which the model learns to fold proteins, discovering that spatial dimensions are learned sequentially. Taken together, our studies demonstrate the power and utility of OpenFold, which we believe will prove to be a crucial new resource for the protein modeling community.

**Available:** bioRxiv [[External Link]](https://www.biorxiv.org/content/10.1101/2022.11.20.517210v2)  
**Collection:** *bioRxiv*  
**Subject Area:**: *Bioinformatics*      
**Paper:** [[bioRxiv Link]](https://www.biorxiv.org/content/10.1101/2022.11.20.517210v2)  
**Citation:** This is a preprint paper. Please refer to the final published paper.
