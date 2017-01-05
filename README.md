#MPAS User's Guide

This repository includes the most up-to-date tex sources and registries as well as python scripts to produce new tex sources as the registries are modified over the course of MPAS development.

###Build

To re-make the chap_fields.tex, chap_init_namelist.tex and chap_model_namelist.tex files, simply run the python scripts: python *.py

To typeset, run 

pdflatex users_guide.tex

twice, then a pdf is produced.
