4/20/2020

\#python \#conda \#EE148-Caltech

Issue: sublime text 3 python interpreters cannot find numpy, numba

Tried: 
1. deleted Win10's embedded python interpreters from user environment variable PATH
2. added miniconda's python interpreter to user environment variable PATH
3. installed numpy with conda only 
	a. turns out removing numpy with conda also removes matplotlib package. Annoying! 
4. installed numpy with pip only 
5. installed numba with conda only 
6. installed numba with pip only 
7. configured(made sure) sublime text 3 is running with minicoda's python 
	a. path to configure pythonCUDA.sublime-build:
		C:\Users\di111\AppData\Roaming\Sublime Text 3\Packages\User\pythonCUDA.sublime-build
8. tried to run with sublime text 3's SublimeREPL python(linked to miniconda path)
	a. path to configure SublimeREPL: 
		C:\Users\di111\AppData\Roaming\Sublime Text 3\Packages\SublimeREPL\config\Python\Main.sublime-menu
	b. tried to activate conda base with Sublime's Conda package 
		i. see C:\Users\di111\AppData\Roaming\Sublime Text 3\Packages\User\Conda (Windows).sublime-settings
		ii. create .condarc with `conda config --write-default`
Current Status: issue persists but the code can run smoothly in conda's command window 