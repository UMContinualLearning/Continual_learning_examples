This is a repository for continual learning tutorials and demos running on Jupyter Notebook and Google Colaboratory. The central idea is to collaboratively create notebooks and scripts which can be directly imported in Google Colab and are related to Continual Learning. 

---

## How to run it

### Running on Google Colab
There are several advantages to running on Colab, such as availability of better computing resources including GPU support.

1. Sign in to [Google Colab](https://colab.research.google.com).

2. Go to the "*GitHub*" tab and type "*UMContinualLearning*"

3. Pick a notebook an run it.


### Locally on your machine

#### Requirements

1. Ubuntu 18.04 or newer. You can get a desktop image from [here](https://releases.ubuntu.com/18.04).
2. Anaconda. Get the latest version from [here](https://www.anaconda.com/products/distribution).

#### Installation and Execution

1. Assuming you are already using Ubuntu and have installed Anaconda. From the command prompt (Ctrl-Alt-T), create a new Python 3.7 environment called "py37" and pre-install a few necessary softwares by typing the commands below and wait for the installation to finish:
```
conda create -n py37 python=3.7 anaconda pytorch>=1.8 --y
```

2. Activate the newly-installed environment: 
```
conda activate py37
```

3. Clone this repository by typing
```
git clone https://github.com/UMContinualLearning/Continual_learning_examples.git continualai
```
The repository should have been downloaded into your computer in the folder named "continualai".
If you encountered an error regarding "git", make sure you have installed it by typing "pip install git".

4. To run a notebook locally on your machine, you need to use Jupyter Notebook which has already been installed in Step 1. Run it in your browser by typing
```
jupyter-notebook
```

5. Navigate to the folder "continualai/notebooks/" and pick any notebook to run. 
