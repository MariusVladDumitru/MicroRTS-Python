# Dissertation thesis projects
This project is part of a series of 3 projects, available at:   
[1] [https://github.com/MariusVladDumitru/MicroRTS](https://github.com/MariusVladDumitru/MicroRTS) - fork of MicroRTS.  
[2] [https://github.com/MariusVladDumitru/MicroRTS-Python](https://github.com/MariusVladDumitru/MicroRTS-Python) - python api for the above fork of MicroRTS.  
[3] [https://github.com/MariusVladDumitru/BIOSINF-Dissertation](https://github.com/MariusVladDumitru/BIOSINF-Dissertation) - dissertation thesis code.

These projects are the source code for my dissertation thesis.

Thank you to the original authors of MicroRTS, available at [https://github.com/Farama-Foundation/MicroRTS](https://github.com/Farama-Foundation/MicroRTS).  
Thank you to the original authors of MicroRTS-py, available at [https://github.com/Farama-Foundation/MicroRTS-py](https://github.com/Farama-Foundation/MicroRTS-py).

# Introduction
MicroRTS-Python is a python API for my fork of MicroRTS, available at [https://github.com/MariusVladDumitru/MicroRTS](https://github.com/MariusVladDumitru/MicroRTS).  
The intention of this API is external control of the game using the python programming language.  
No RL, DRL algorithms will be implemented here.

# Goals
- External control of players
- Exposing game state information

# Tools
- IDE or text editor of choice.
- Miniconda or Anaconda.
- Python.

# Setup
- Install a text editor or IDE of your choice. Recommandations: [Pycharm(free or pro)](https://www.jetbrains.com/pycharm/), [Spyder](https://www.spyder-ide.org/), [Visual Studio Code](https://code.visualstudio.com/), [Sublime Text](https://www.sublimetext.com/), [Notepad++](https://notepad-plus-plus.org/), [Kate](https://kate-editor.org/).
- Install Miniconda or Anaconda available [here](https://www.anaconda.com/download/). Documentation: [Conda documentation](https://docs.conda.io/projects/conda/en/latest/index.html), [Getting Started Guide](https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html).  
- Create new conda environment: 
```shell
conda create -n MicroRTS-Python
```
- Activate the new environment: 
```shell
conda activate MicroRTS-Python
```
- Clone this repository: 
```shell
git clone https://github.com/MariusVladDumitru/MicroRTS-Python.git
```
- cd into repository folder: 
```shell
cd MicroRTS-Python
```
- Install packages from requirements.txt: 
```shell
conda install --yes --file requirements.txt
```
***CHECK IF THIS WORKS***