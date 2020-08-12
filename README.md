Welcome to the HATAM course. In this course you will learn a plethora of subjects. In order to participate in these workshops some software must be installed on your local computers. Follow the instructions in the sections below to install everything needed for the various workshops.

- [Discord](#discord)
- [Introduction Week Installations](#introduction-week-installations)
  * [Non-Linux Users](#non-linux-users)
  * [Linux Users](#linux-users)
- [Advanced Week Installations](#advanced-week-installations)
  * [Anaconda](#anaconda)
    + [Windows](#windows)
    + [Linux](#linux)
  * [Algorithmics Workshop Installations](#algorithmics-workshop-installations)
  * [Machine Learning Workshop Installations](#machine-learning-workshop-installations)
  * [Computer Vision Workshop Installations](#computer-vision-workshop-installations)
  * [PyCharm Installation](#pycharm-installation)

# Discord

1. Download the installation file from this [link](https://discord.com/new/download).
2. Follow the instructions and install discord.
3. Join the HATAM server by clicking on this [link](https://discord.gg/EJcysAY).

# Introduction Week Installations

If you don't have a local Linux machine, or if you have but would rather use an already set-up virtual machine, follow the instructions in sub-section `Non-Linux Users`. For those who have a local Linux machine and would prefer downloading everything locally, follow the instructions in the sub-section `Linux Users`.

## Non-Linux Users

1. Download the newest Virtual Box version from this [link](https://www.virtualbox.org/wiki/Downloads).
2. Go to this [link](https://drive.google.com/drive/folders/1K_uQZUQykIimW44xKx2Azrn1jXxGuR49) and do one of the following:
    * If you have a consistent internet connection, download the whole virtual machine image named `HataMachine.ova` (~7GB)
    * If you don't have a consistent internet connection, download the separate ZIP files from the folder `HataMachine` and then extract the virtual machine image from them.
4. Open Virtual Box and choose `Import`.

    ![image](https://user-images.githubusercontent.com/38311688/90002771-c5839d00-dc9b-11ea-9773-6c4ec16d4b4b.png)

5. Choose the `.ova` file you downloaded and click on `continue`.
6. In the next screen you will see the recommended settings for the virtual machine:

    ![image](https://user-images.githubusercontent.com/38311688/90002795-d3d1b900-dc9b-11ea-9ff8-45d5880a8498.png)
    
    If you have less than 8GB of RAM on your local machine, reduce the RAM requirements of the virtual machine (it should be no less than 2048MB).

## Linux Users

1. Make sure you have Python 3. If not, download using the command `sudo apt-get install python3`.
2. Download and install on your local machine the latest anaconda version for Python3 from [here](https://www.anaconda.com/products/individual).
3. Download the script `install.sh` from [here]().
4. Add run permissions by running `chmod +x install.sh`.
5. Make sure `anaconda` is not being run by default in your terminal by running `conda deactivate`.
6. Download and install the latest version of `IDA-Free` from [here](https://www.hex-rays.com/products/ida/support/download_freeware/).

# Advanced Week Installations

## Anaconda

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

## Algorithmics Workshop Installations

1. Run the command `conda env create -f algo\environment_algo.yml`
2. Run the command `conda activate psagot-2020-algo`
3. Run the command `python algo\check.py`
4. Run the command `conda deactivate`

## Machine Learning Workshop Installations

1. Run the command `conda env create -f ml\environment_algo.yml`
2. Run the command `conda activate psagot-2020-ml`
3. Run the command `python ml\check.py`
4. Run the command `conda deactivate`

## Computer Vision Workshop Installations

1. Run the command `conda env create -f cv\environment_algo.yml`
2. Run the command `conda activate psagot-2020-cv`
3. Run the command `python cv\check.py`
4. Run the command `conda deactivate`

## PyCharm Installation

Since we are civil, non barbaric, duck loving creatures we will be using PyCharm as the main IDE for python development in these workshops (alongside `jupyter` which you have installed in the previous sub-sections). You can download the latest PyCharm version from the following link:

`https://www.jetbrains.com/pycharm/`

The installation is straightforward.
