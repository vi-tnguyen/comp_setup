# comp_setup
## installations from command line for windows
### install git from: https://git-scm.com/download/win

## set up windows to run python in command prompt
### install python using the directions here: https://docs.python.org/3.5/using/windows.html 
  * try selecting the option "add Python 3.5 to PATH" (I missed this when I did it and had to add it to my PATH manually to enable a call to Python from the command prompt)
  * If you missed it as well, and get errors "not recognized" or "bad command" when you run "python" in the command line, follow the directions here to set your PATH: https://docs.python.org/2/faq/windows.html
  * once you've set up python and can go into the interactive interface, you can run your python programs and make functions in your programs accessible by importing (i.e. my program is called helloworld.py, and I have a function greet that takes no arguments. By running "from helloworld import *", I can then run greet() and call my function
  
### install Anaconda for Python, which has many of the key packages; and comes with an Anaconda Command Prompt that functions like Command Prompt but allows you to get in and out of the python interactive interface faster: https://www.continuum.io/sites/default/files/Anaconda-Quickstart.pdf
 

## install the following packages
  * pip install: pandas, matplotlib, numpy, random, skilearn, scipy
