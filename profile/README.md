## Introduction to deep learning
This nine-day crash course is part of the course program for incoming Ph.D. students at the University of Bonn's [BIGS-Neuroscience](https://bigs-neuroscience.de/) and [BIGS Clinical and Population Science](https://bigs-clinpopscience.de/). We are releasing it here for those who could not attend the course in person. Furthermore, we hope that it will help a broader audience.

The material currently consists of lecture videos, slides and exercises.
Most exercises come with unit tests, allowing you to verify your solutions independently. The first exercise explains how to do that. Accept exercises by following the exercise links and using the template.

All exercises will run on Ubuntu 22.04.1 with ffmpeg version 4.4.2 and miniconda python.

An extended version of this course is held in person every semester. [Members of the University can register](https://www.hpc.uni-bonn.de/en/events/foundations-of-machine-learning). Attend in person for access to tutoring. 


#### Prerequisites:
Programming in Python. If you are unfamiliar with Python, please consult https://docs.python.org/3/tutorial/ before starting to work on the course.
Exposure to university-level math courses makes it much easier to understand the material. However, participants from our digital humanities groups have completed the course on site.


### Feedback
This is the first public version of this course. You will notice here and there. Unfortunately the recording started to late on days two and three. Fortunately not too much is missing. The slides document what happened. You will notice the slides reflect the feeback we got during the course. We are continuously working on improvements and new content. Make sure you come back next semester! If you have ideas for improvement, [reach out](https://www.dice.uni-bonn.de/hpca/de/hpca-lab-mitarbeiter/dr-moritz-wolter).


## Course contents:

### Part 1, Basics
- Day 1: Introduction
    - How to get started
    - [exercise](https://github.com/Deep-Learning-with-Jax/day_01_exercise_intro)
- Day 2: Optimization
    - The derivative, gradients, optimization via gradient descent.
    - [exercise](https://github.com/Deep-Learning-with-Jax/day_02_exercise_optimization)
- Day 3:   Linear Algebra:
   - Matrix multiplication, singular value decomposition, Linear Regression.
   - [exercise](https://github.com/Deep-Learning-with-Jax/day_03_exercise_algebra)
- Day 4:  Statistics
   - Mean and variance, correlation, Gaussians.
   - [exercise](https://github.com/Deep-Learning-with-Jax/day_04_exercise_statistics)
### Part 2, Deep Learning
- Day 5: Fully connected networks:
    -  The MNIST-data set, artificial neurons, forward and backward pass.
    -  [exercise](https://github.com/Deep-Learning-with-Jax/day_05_exercise_neural_networks)
- Day 6: Convolutional neural networks:
    -  The convolution operation and convolutional neural networks.
    -  [exercise](https://github.com/Deep-Learning-with-Jax/day_06_exercise_cnn)
- Day 7: Optimization for deep neural networks:
    -  Gradient descent with momentum, Adam, early stopping, regularization.
    -  [exercise](https://github.com/Deep-Learning-with-Jax/day_07_exercise_brain_decode)
- Day 8: Interpretability:
    - Visualization of linear classifiers, saliency maps, integrated gradients
    - [exercise](https://github.com/Deep-Learning-with-Jax/day_08_exercise_interpretability)
- Day 9: Sequence models:
    - Long-Short-Term-Memory, Gated recurrent units, text-based language models.
    - [exercise](https://github.com/Deep-Learning-with-Jax/day_09_exercise_sequence_processing)


## Support

We thank the state of North Rhine-Westphalia and the Federal Ministry of Education and Research for supporting this project.

<table>
<tr>
    <td><img src="https://github.com/Machine-Learning-Foundations/.github/blob/main/profile/img/nrw-logo.png" height="150"></td>
    <td><img src="https://github.com/Machine-Learning-Foundations/.github/blob/main/profile/img/BMBF_gefoerdert_2017_en.jpg" height="150"></td>
</tr>
</table>

## Known issues
Github.com and vscode use different markdown specifications. See i.e. https://github.com/microsoft/vscode/issues/190173 . Look at the readmes online if the vscode preview fails to render content correctly. 
