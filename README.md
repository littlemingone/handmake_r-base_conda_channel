# About this repository
This repository contains a conda channel with the latest version(4.4.0) of r-base [(R programming language)](https://www.r-project.org/) conda package.  
<strong>Only for windows now!!</strong>

# What does it solve?
It helps you to use <strong>lastest</strong> version of r-base in conda environments. Only for Windows users now!


conda is a convenient tool to install and manager R environment. 
There are many benifits to use R in a conda environment. 
But the version of r-base in conda-forge and r channel are far too old. 
Currently, the latest official version of the R programming language is <strong>4.4.0</strong>, but the latest version of r-base for Windows in the conda channel is <strong>4.1.3</strong>. 

# Usage
2 ways to install r-base 4.4.0 in conda environments on Windows.
 ## 1. Install r-base 4.4.0 by conda channel.
Add this channel [(https://littlemingone.github.io/handmake_r-base_conda_channel)](https://littlemingone.github.io/handmake_r-base_conda_channel) into your conda sources.
```
conda config --add channels https://littlemingone.github.io/handmake_r-base_conda_channel
```
Then install r-base 4.4.0.
```
conda install r-base=4.4.0
```  
 ## 2. Install r-base 4.4.0 locally.
 [Download](https://github.com/littlemingone/handmake_r-base_conda_channel/releases/download/v4.4.0/r-base-4.4.0-littleming.tar.bz2) the conda package in release. Install it locally. Replace <path/to/r-base4.4.0> with the actual path of your download file.
```
conda install path/to/r-base4.4.0
```
# How dose it build?
In fact, I didn't compile the R base again when I bulit the package. I just installed the [r-base 4.4.0.exe](https://cloud.r-project.org/bin/windows/base/R-4.4.0-win.exe) and packaged the binary files. It sounds handmake but it work, I guess.

# I am a linux user, can I use it?
Not for now, at least. It is possible and not difficult to make a linux conda package in the same way, I guess. Maybe someday I will update the linux version.



