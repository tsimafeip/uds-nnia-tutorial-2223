# UdS NNIA Tutorials

Slides for Neural Networks Implementation and Application tutorials of Winter semester 2022 at University of Saarland. Adapted from [the slides](https://github.com/tsimafeip/uds-nnia-tutorial-2223) created by Vilém Zouhar and Noon Pokaratsiri Goldstein for the previous edition of this class.

## Outline

Schedule (links provided only to semi-finished materials):
- [Introduction + Assignment 0](01-introduction/handout.pdf)
- [Regression + Assignment 1,2](02-regression/handout.pdf)
- [Neural Networks Hello World + Assignment 2,3](03-nn-hello-world/handout.pdf)
- [Optimization + Assignment 3,4](04-optimization/handout.pdf)
- [Backpropagation + Assignment 4,5](05-backpropagation/handout.pdf)
- [Regularization + Assignment 5,6](06-regularization/handout.pdf)
- [Optimizers + Assignment 6,7](07-optimizers/handout.pdf)
- [CNN + Assignment 7,8](08-cnn/handout.pdf)
- [RNN + Assignment 8,9](09-rnn/handout.pdf)
- [Methodology, Representation + Assignment 9,10 (no content)](10-representation/handout.pdf)
- [Contemporary NLP + Assignment 10 (no content)](11-contemporary-nlp/handout.pdf)

## Contributing

Compile slides using pandoc and the provided script (handout includes notes and disables iterative lists):
- Slides: `./build.sh 01-introduction tutorial`
- Handout version: `./build.sh 01-introduction handout`
- Both: `./build.sh 01-introduction`

Make sure you have `pandoc` and `texlive` installed.
Usually the following should suffice `sudo apt install pandoc texlive-latex-base texlive-pictures texlive-latex-recommended`. For Mac `brew install pandoc` and reopening terminal worked fine.
You don't need to build the presentations if you want to contribute - editing the markdown is enough.

## License

Feel free to update, present and distribute on your own accord.
In all cases, however, preserve the names of the previous contributors
