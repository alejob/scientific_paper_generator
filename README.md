# Scientific Paper Generator (SPG)
Project to generate in the most standard way a scientific paper by guiding the user by questions to fullfill. 

Use
---

(IN DEVELOPMENT, many options still not available, including the automatic .tex creation)
Just answer the questions and choose your journal format (currently just "draft paper"). The program will create a .tex file with the choosen format and will create a pdf file. The output text are just the answers in the right position on the paper.

The purpose of SPG is to help you to have a 3/4 already paper in a simple way. The 1/4 of the paper is up to you (connect in a human way the text, put figure, and check any detail).

I expect in the future to add some Natural Language Processing and machine learning to automatize the paper generation.

Any suggest and improve is accepted.


Dependencies
------------
texlive

texlive-humanities


User's manual
-------------
To create your paper use:

`make paper_format`

where _paper_format_ is the chosen format. The output will be saved
in the _output_ directory

Ex:

`make draft` 

creates _draft.pdf_ in _output_ directory.
