# Lisbon.ai workshop: Deep Learning with Tensorflow

# Quick workshop description

The goal of this workshop is to give you a thourough understanding of Tensorflow and how you can use it to effectively build and train neural network models.

We will not be running big models since we have limited time and hardware, but hopefully this will give you the skills and tools to go home later and confidently start running different experiments.

This workshop will be extremely practical. You will be led to code your small neural network training and evaluation pipeline from scratch throughout the session. It is up to me to guide you appropriately in order to provide the necessary bits of knowledge needed at each stage, but each one of you will be doing the coding yourselves (I will be coding live alongside you, so you have a reference at all time!). Code for visualization or plotting will be the only thing provided by me, as this it too dull and error-prone to be created during the workshop.

Theoretical explanations will be introduced where necessary and there will be time for you to play with the neural network's settings by yourselves, in order to gain some empirical intuition for how neural networks work.

# Skills required
You should be comfortable working with Python. Tensorflow's sythax and way of thinking is very similar to Numpy, so knowledge of Numpy/Scipy is a big plus. There will be a very brief introduction to the Numpy way of thinking in the beginning of the workshop nonetheless. 

I will assume you have attended Wang Ling's lecture in the morning, where the fundamentals of neural networks will be covered. Basic knowledge of linear algebra, calculus and probabilities (please brush up on Maximum Likelihood Estimation beforehand) will be necessary.

# Setup and packages required (very important)
You will be coding in a Jupyter (formerly IPython) notebook, in order to guarantee everyone's setup is the same, and to allow for quick code iteration.

We will be using Python3. The packages to be installed are in the requirements.txt file (found in this repo). You can install them in a virtual environment using pip3 via the command:
```
pip3 install -r requirements.txt
```

In order to guarantee that your installation was successful, run the cell inside the notebook `dependency_tester.ipynb` (found in this repo). It should run without errors. Fix your installation setup until it does, so we can jump straight into coding during the workshop.
