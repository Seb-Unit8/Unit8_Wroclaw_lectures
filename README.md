# Unit8 Wroclaw lectures

## Python setup

### Graphical User interface (GUI)
This will take more time to do, download more data and consume more disk space. However, you get a GUI most of the way instead of using the command line if you're not already familiar with it.

1. Download and install [anaconda](https://docs.anaconda.com/anaconda/install/)
2. Open anaconda navigator
3. Follow [this guide](https://docs.anaconda.com/anaconda/navigator/tutorials/manage-environments/#importing-an-environment) using the file environment.yml at the top level of this repo.
4. Use anaconda navigator to launch jupyter lab in the created environment `bayes_env`

### Command line
This is frankly the better way however you will need to use the command line.

1. Download and install [miniconda](https://docs.conda.io/en/latest/miniconda.html)
2. Open the terminal of your choice (e.g. cmd for windows, terminal for mac/linux)
3. Navigate to folder containing this file.
4. Run `conda env create -f environment.yml`
5. Activate the environment using `conda activate bayes_env`
6. Launch jupyter with `jupyter lab`