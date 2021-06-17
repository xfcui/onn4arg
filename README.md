# ONN4ARG

ONN4ARG is an Ontology-aware Neural Network model for Antibiotic Resistance Gene (ARG) annotation predictions. It employs a novel ontology-aware layer to encourage annotation predictions satisfying the ontology rules (i.e., the ontology tree structure). The provided programs can be used to predict ARG annotations of a given protein sequence.

##Usage:

./predict.sh FASTA_fileprefix

The program will take "FASTA_fileprefix.fasta" as input and store the predicted annotations in "FASTA_fileprefix.out". Moreover, it depends on the [Diamond](https://github.com/bbuchfink/diamond) and [HHblits](https://github.com/soedinglab/hh-suite) alignment tools and the our pre-built ARG database.



