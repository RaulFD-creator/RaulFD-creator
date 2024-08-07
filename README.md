# Welcome to my Github repository

Greetings and welcome to my Github repository, my name is Raúl Fernández Díaz and I'm a PhD Student working under the supervision of Prof. Denis Shields (UCD Conway Institute) and Thanh Lam Hoang (IBM Research) on Foundation Models for Protein Representation Learning. I hold a BSc. in Biotechnology and a MSc. in Bioinformatics, which allow me to tackle the complex idiosyncrasies of working at the interface between computation, statistics, biology, and chemistry with a holistic approach. In this repository, you may find some projects I am working on. 


##  Generalisation of Biochemical Foundation Models to new data

One of my professional focuses is the application of novel Foundation Models on the fields of biochemistry and drug discovery (like Protein Language Models) for accelerating scientific discovery, particularly evaluating and improving their generalisation to new data. This section contains my work in that area:

- **AutoPeptideML:** an end-to-end, user-friendly application and web service that enables experimental researchers to build their own custom models for peptide bioactivity prediction for drug discovery. This is an Automated Machine Learning (AutoML) tool to tackle challenges ranging from data acquisition (small dataset sizes, sparse labeling) to peptide representation, independence of evaluation datasets and interpretation of results. It does so by leveraging large FMs (Protein Language Models), a novel homology partitioning algorithm and simplifying the process for users with limited ML knowledge, promoting reproducibility and best practices. There is a dedicated [webserver](http://peptide.ucd.ie/AutoPeptideML) and a [Github Repository](https://github.com/IBM/AutoPeptideML). There is more information available on the [paper pre-print](https://www.biorxiv.org/content/10.1101/2023.11.13.566825).
- **Hestia:** a suite of tools for introducing similarity correction and analysis techniques to biochemical data including similarity calculation, clustering, similarity reduction, and similarity partitioning (for creating generalisation-evaluating training/test dataset splits. There is a dedicated [webserver](http://peptide.ucd.ie/Hestia) and a [Github Repository](https://github.com/IBM/Hestia-OOD).


## Development of new Foundation Models for Biochemistry

The main focus of my thesis is the development of new Foundation Models for Biochemistry. Here are some of the projects, I've been working on:

- **Otter-Knowledge:** a system that allows for generating multi-modal knowledge graphs from diverse sources and training GNNs on them for enhancing entity representation. The approach has been developed with biochemical applications in mind, particularly for drug discovery. Early results show improved performance on protein-ligand binding affinity prediction in three different benchmark datasets. More information in the [paper pre-print](https://arxiv.org/abs/2306.12802) and the [Github Repository](https://github.com/IBM/otter-knowledge).


## Webserver Building and Maintenance

One important step on Bioinformatics tool development is making them accesible to users that may not have a computational background and, therefore, require user-friendly deployment.

- **ShieldsLab webserver:** This webserver can be accessed at the [http://peptide.ucd.ie](http://peptide.ucd.ie) and contains the main Bioinformatics tools developed in the group.
- **ShieldsLab website:** Not technically a webserver, but I also work on maintaining the group website, which can be accessed from [this link](https://shields-lab.github.io/shieldslab/).

## Science communication

Though my professional focus is on AI development, I also find scientific communication and teaching fascinating. Here are some of the projects related to that aspect of my work.

- **VII SECUAH Congress:** Workshop titled "Aprendizaje profundo en biomedicina" - Deep Learning on Biomedicine. I've taught a cohort of biosciences students (undergrad and graduate) about artificial intelligence, machine learning, and deep learning techniques and how to apply them to biomedical research. The workshop lasted 4 h and finished with a guided practical example where every student was able to build their own deep convolutional neural network for diagnosing skin lessions as either bening or cancerous. Materials can be found in this [Github Repository](https://github.com/RaulFD-creator/SECUAH).
- **IX SECUAH Congress:** Workshop titled "Modelos que aprenden el lenguaje de las moléculas" - Models that learn the language of molecules. I've taught a cohort of biosciences students (undergrad and graduate) about artificial intelligence, particularly language models, and their main applications in biomedical and biochemical research. The workshop lasted 4 h and finished with a guided practical example where every student was able to re-train MolFormer-XL to build their own small molecule toxicity predictive model. Materials can be found in this [Github Repository](https://github.com/RaulFD-creator/SECUAH).


