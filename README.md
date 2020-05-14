## make sure we are using python

1. $ which python : tell which directory python is installed in
2. $ ls /home/gitpod/.pyenv/shims/ | grep python : filter the word "python" in our results, so that only the file names that
have "python" in it will be displayed to screen
3. $ python : open the current python interpreter
4. $ python3 : open python3

## executing python code 

1. $ python3 xxx.py : execute xxx.py file in terminal window
2. $ python3 : open python3 and write code to execute in interpreter

## pip3

1. python libraries are installed in Python Package Index, or Pypi
2. pip3 is the tool to get libraries from Pypi
3. python standard library contains modules like operation system, math, text, file handling, etc.
4. $ pip3 install flask : speak to the Python package index and install Flask
5. $ pip3 freeze : tell us all of the packages that we've installed
6. $ pip3 freeze --local > requirements.txt : redirect all libraries to the .txt file
7. $ pip3 uninstall flask : uninstall flask
8. $ pip3 install -r requirements.txt : tells pip to install from the requirements.txt

