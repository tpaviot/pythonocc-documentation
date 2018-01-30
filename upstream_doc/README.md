An update over official OCCT documentation.

Code snippets are converted from c++ to Python.

To compile user_guides :

$ ./gendoc -overview -ug=user_guides/modeling_data/modeling_data.md -pdf

Workflow to convert the original .md file into a pythonocc related .md:

* in the introduction, credt open cascade, recall document conventions, assume every module is loaded

* convert all code snippets to python. Don't forget to place {.py} for each code block.

* replace all occurrences of "package" with "module". Indeed an occt package is wrapped as a python module