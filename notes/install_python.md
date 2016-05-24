##how to install python

since we will be using the cloud 9 environment you really won't have to worry about this for most of the class.

however if you would prefer to work locally on your home computer here are two options for you to consider.

download from [python.org](https://www.python.org)  
[python downloads](https://www.python.org/downloads/)  
download version 3.5.x for your operating system

anaconda, or miniconda(the full anaconda is overkill for this course)  
[miniconda](http://conda.pydata.org/miniconda.html)


### python2 to python3  
by default cloud 9 uses python 2. to use python 3.5 enter the following commands in a terminal  

`$ sudo mv /usr/bin/python /usr/bin/python2`  
`$ sudo ln -s /usr/bin/python3.5 /usr/bin/python`


### the REPL  
Read Eval Print Loop  
cloud 9 comes with iPython, a slightly more sophisticated python REPL.  
to start ipython simply enter `ipython` in a terminal or `ipython3` if you have not completed the step above
