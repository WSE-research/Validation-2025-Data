================
Experimental data for Instruction-Tuned Language Models as Judges for SPARQL Query Correctness in KGQA
================

All results are in the files in the folder data/, named after used KGQA system, language and LLM model.

Files structure
----------------

All files are in jsonlines format. Each line is a dictionary with the next keys:

* custom_id: ID, stores important information about experimen and particular record
* prompt: what was sent to a model
* answer: model's answer


