This is a repository for continual learning tutorials and demos running on Jupyter Notebook and Google Colaboratory. The central idea is to collaboratively create notebooks and scripts which can be directly imported in Google Colab and are related to Continual Learning. 

---

## Content

- **Intro to Continual Learning** [notebook](./notebooks/intro_to_continual_learning.ipynb)
- **Intro to Deep Learning Frameworks** [notebook](./notebooks/intro_to_dl_frameworks.ipynb)
- **Replay Strategy** [notebook](./notebooks/CL_via_simple_rehearsal.ipynb)
- **Generative Replay** [notebook](./notebooks/intro_to_generative_replay.ipynb)
- **Progressive Neural Networks** [notebook](./notebooks/CL_via_PNN.ipynb)
- **Genetic Pseudo Rehearsal** [notebook](./notebooks/Genetic_Pseudo_Rehearsal_Demo.ipynb)
- **Permuted and split mnist** [notebook](./notebooks/permuted_and_split_mnist.ipynb)
- **Forgetting with one neuron** [notebook](./notebooks/forgetting_with_one_neuron.ipynb)
- **Avalanche Demo** [notebook](./notebooks/avalanche_demo.ipynb)

## Requirements: 
1. Ubuntu 18.04 or newer. You can get a desktop image from [here](https://releases.ubuntu.com/18.04).
2. Anaconda. Get the latest version from [here](https://www.anaconda.com/products/distribution).

## How to run it

### Locally on your machine
1. Assuming you are already using Ubuntu and have installed Anaconda. From the command prompt (Ctrl-Alt-T), create a new Python 3.7 environment called "py37" and pre-install a few necessary softwares by typing: 
```
conda create -n py37 python=3.7 anaconda --y
```
Wait for the installation to finish.

2. Activate the newly-installed environment and install the Avalanche toolbox by typing
```
conda activate py37
pip install avalanche-lib==0.2.0
```

3. Clone this repository by typing
```
git clone https://github.com/UMContinualLearning/Continual_learning_examples.git
```
The repository should have been downloaded into your computer in the folder named "Continual_learning_examples".
If you encountered an error regarding "git", make sure you have installed it by typing "pip install git".

4. To run a notebook locally on your machine, you need to use Jupyter Notebook which has already been installed in Step 1. Run it in your browser by typing
```
jupyter-notebook
```

5. Navigate to the folder "Continual_learning_examples/notebooks/" and pick any notebook to run. 


### Running on Google Colab
There are several advantages to running on Colab, such as availability of better computing resources including GPU support.

1. Sign in to [Google Colab](https://colab.research.google.com).

2. Go to the "*GitHub*" tab and type "*UMContinualLearning*"

3. Pick a notebook an run it.
