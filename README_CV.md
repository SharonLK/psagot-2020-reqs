# Computer Vision Workshop Installation Guide

To be fully prepared for the computer vision workshop, make sure you follow the following instructions to install everything needed on your local machine. If you encounter any problems, please contact your supervisor or Sharon.

## Anaconda Installation

The workshop heavily relies on python and the anaconda package management system. Go to the [anaconda website](https://www.anaconda.com/products/individual) and follow the instruction to install it on your system (all platforms are supported).

## Anaconda\Python Environment Set-up

* Open up the anaconda prompt
    * *Linux* - simply open the terminal after the installation
    * *Windows* - press `WINKEY` and then search for `Anaconda Prompt (anacond3)`
* In the anaconda prompt run the command `conda env create -f cv\environment_cv.yml`
* Then run the command `conda activate psagot-2020-cv`
* Then, to check that everything installed properly, run the command `python cv\check.py`

## Downloading the Project Files

* Download exercise files from [this link](https://drive.google.com/file/d/1Be4ZkFVur4N-tJc05Y9fXkXSXcNOiTVQ/view?usp=sharing)
* Extract the exercise files into your file system
* Download the data files from [this link]() into the exercise directory
* After extracting everything, your working directory should look like this:

![image](https://user-images.githubusercontent.com/38311688/91271310-a4827800-e782-11ea-9270-0e020fdfa610.png)

## Launching the Project

* Open up the anaconda prompt
    * *Linux* - simply open the terminal
    * *Windows* - press `WINKEY` and then search for `Anaconda Prompt (anacond3)`
* In the anaconda prompt `cd` to the exercise directory
* Run the command `conda activate psagot-2020-cv`
* Open up jupyter by running `jupyter notebook`

    ![image](https://user-images.githubusercontent.com/38311688/91271431-d8f63400-e782-11ea-8ac9-8fd323407b02.png)
