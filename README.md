# Animation of Parsing Algorithms

Our purpose was to provide students with an enhanced understanding of parsing algorithms, by offering a visual representation that highlights the most significant detail, while simultaneously animating these key features. </br>

To extended the current basic representation of parsing algorithms in Jupyter notebooks we animated the operations of various algorithms in execution.
We focused on animating the features of sentence derivations, and finite state machines such as NFA minimized to DFA, subset conversion and minimization, Earleys Parsing Algorithm, and String Parsing. 

 
![alt text](https://github.com/NikouKalbali/AnimatingParsingAlgorithms/blob/master/anim2.gif "Logo Title Text 1")

#### INPUT:
nltk.tree.Tree, generated by inputting a grammar and phrase into nltk Parser
#### METHOD:
Iterate through tree, and extend branch for each new node, creating model of the tree 
Iterate through this model, highlighting each node to demonstrate how the sentence is derived
#### OUTPUT:
Animation of the derivation tree for the specified sentence


# Software and Modules 
The implementation was written in Python, version 3.8.1. </br>
The animations were generated with the installation of the module GraphviAniz. </br>
We used module GraphvizAnim to generate the animation, </br>
The entirety of the project was written, executed, and tested in a series of Jupyter notebooks. </br>

# Required Software:
The following open source programs need to be installed on your computer:
1) To install fysom
pip install fysom
2) To install Gvanim
pip install GraphvizAnim
3) To install nose.tools
pip install nose
4) To install timeit
pip install pytest-timeit


# CITATION
Santini, M., Thomas, D., & Wimmer, R. (2019, February 17). mapio/GraphvizAnim: Upgrading to Python 3 (and new Binder configs). Zenodo. http://doi.org/10.5281/ZENODO.1037283

Riehl, M. (2013). fysom. GitHub repository. Retrieved from https://github.com/mriehl/fysom

(n.d.). (Finite-) State Machines in practice. Retrieved from https://www.electricmonk.nl/docs/finite_state_machines_in_practice/finite_state_machines_in_practice.html