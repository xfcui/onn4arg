# ONN4ARG

ONN4ARG is an Ontology-aware Neural Network model for Antibiotic Resistance Gene (ARG) annotation predictions. It employs a novel ontology-aware layer to encourage annotation predictions satisfying the ontology rules (i.e., the ontology tree structure). The provided programs can be used to predict ARG annotations of a given protein sequence. In order to make predictions, it requires the [Diamond](https://github.com/bbuchfink/diamond) and the [HHblits](https://github.com/soedinglab/hh-suite) alignment tools, our pre-built ARG database and our pre-trained model (see https://zenodo.org/record/4973566).


##Usage:

./predict.sh FASTA_fileprefix

The program will take "FASTA_fileprefix.fasta" as input and store the predicted annotations in "FASTA_fileprefix.out".


