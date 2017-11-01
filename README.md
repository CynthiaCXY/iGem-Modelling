# iGem-Modelling


The deterministic model is written in Jupyter Notebook (IPython) environment, for easier visualisation of plots. Please follow the instructions in order to view and modify the content of the code.


## Instructions for setting up the environment:


  *  If you already have Python 2.7+ installed on your computer, ignore this step. Otherwise, go to [Python website](https://www.python.org/downloads/) and install python 2.7.14. The website should automatically recognise your operating system and suggest a download for you.


  *  If you already have Miniconda or Anaconda installed, ignore this step. Otherwise, go to [Miniconda](https://conda.io/miniconda.html) and download the Python 2.7 version according to your operating system.


  *  Download our .ipynb code files, save them and them only (for security reasons) into a directory that you’d like to work in.


  *  Open the terminal, do the following:

	- To create conda environment:
		```conda create -n dModel python = 2```

	- To activate conda environment, if you have Mac OS X or Linux:
		```source activate dModel```

	- If you have Windows:
		```activate dModel```
Note: You need to activate the environment every time you wish to work with the files. The whole point of setting up this environment is to separate it from the rest of your computer, since it’s written in Python 2.7, if you ever update your Python to higher version, and if some functions being used in our code files are modified/updated by Python, our code might not work anymore properly anymore.

	- Install relevant Python packages:
		```conda install numpy scipy matplotlib jupyter```
	- Free up disk space from package tarballs:
		```condo clean -t```
	- Go to the directory where you saved the code files:
		```cd ~/pathToDirectory```
	- Open files with Jupyter Notebook
		```jupyter notebook```
	- The terminal should then open your default web browser to view the code files. Do not close the terminal while you’re working on the code files. 

  *  To quit Jupyter Notebook, close windows in browser, go to your terminal, hit ctrl+c twice to quit.

If you have any questions or difficulties, contact us at igem2017edinburgh@gmail.com