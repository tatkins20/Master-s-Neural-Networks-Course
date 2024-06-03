## UdS NNIA Tutorials
Slides for Neural Networks Implementation and Application tutorials of Winter semester 2022 at University of Saarland. Adapted from the slides created by Vilém Zouhar and Noon Pokaratsiri Goldstein for the previous edition of this class.

## Outline
Schedule (links provided only to semi-finished materials):

Introduction + Assignment 0
Regression + Assignment 1,2
Neural Networks Hello World + Assignment 2,3
Optimization + Assignment 3,4
Backpropagation + Assignment 4,5
Regularization + Assignment 5,6
Optimizers + Assignment 6,7
CNN + Assignment 7,8
RNN + Assignment 8,9
Methodology, Representation + Assignment 9,10 (no content)
Contemporary NLP + Assignment 10 (no content)
Contributing
Compile slides using pandoc and the provided script (handout includes notes and disables iterative lists):

Slides: ./build.sh 01-introduction tutorial
Handout version: ./build.sh 01-introduction handout
Both: ./build.sh 01-introduction
Make sure you have pandoc and texlive installed. Usually the following should suffice sudo apt install pandoc texlive-latex-base texlive-pictures texlive-latex-recommended. For Mac brew install pandoc and reopening terminal worked fine. You don't need to build the presentations if you want to contribute - editing the markdown is enough.

## License
Feel free to update, present and distribute on your own accord. In all cases, however, preserve the names of the previous contributors
