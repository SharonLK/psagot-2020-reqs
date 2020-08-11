# Algorithmics & Data Science Installation

### Windows

1. Clone this repository to your local machine.
2. Download `Anaconda` from the following website: `https://www.anaconda.com/products/individual`
3. Install `Anaconda` using the default options.
4. Continue the set-up according to your operation system
5. Bring up the start menu by pressing on the windows key.
6. Search for `Anaconda Prompt (anaconda3)` and open it.
7. Navigate to the directory where you cloned the repo.
8. Follow the instructions in the following sections to create python environments for the upcoming workshops.

### Linux

1. Clone this repository to your local machine.
2. Download `Anaconda` from the following website: `https://www.anaconda.com/products/individual`.
3. Use `chmod 777` so you can run the shell installation file.
4. Run the installer `./Anaconda3-2020.07-Linux-x86_64.sh`.
5. When prompted to install anaconda and append to `.bashrc`, answer with `yes`.
6. After installation close and re-open the terminal and make sure that anaconda is recognized by running the command `conda -h` and checking if there is any output.
7. Follow the instructions in the following sections to create python environments for the upcoming workshops.

# Algorithmics Workshop Installations

1. Run the command `conda env create -f algo\environment_algo.yml`
2. Run the command `conda activate psagot-2020-algo`
3. Run the command `python algo\check.py`
4. Run the command `conda deactivate`

# Machine Learning Workshop Installations

1. Run the command `conda env create -f ml\environment_algo.yml`
2. Run the command `conda activate psagot-2020-ml`
3. Run the command `python ml\check.py`
4. Run the command `conda deactivate`

# Computer Vision Workshop Installations

1. Run the command `conda env create -f cv\environment_algo.yml`
2. Run the command `conda activate psagot-2020-cv`
3. Run the command `python cv\check.py`
4. Run the command `conda deactivate`

# IDE Installation

Since we are civil, non barbaric, duck loving creatures we will be using PyCharm as the main IDE for python development in these workshops (alongside `jupyter` which you have installed in the previous sub-sections). You can download the latest PyCharm version from the following link:

`https://www.jetbrains.com/pycharm/`

The installation is straightforward.
