# Steps to Create End to End Project

* create folder and initialize git

* create template.py file that creates a template/framework for the project

* create init_setup.sh file to create virtual environment and install all required package. command to run init_setup.sh file: 
```
bash init_setup.sh
```

* In git, create LICENCE file and select licence from the options given.

* In git, create .gitignore file and select python from the dropdown. github will create script for gitignore file.

* create setup.py file that helps to create local python package, that can be imported form anywhere. we can use any one below commands to install the package:
```
python setup.py install
```
OR
```
-e .
``` 
(`-e`: stands for editable, `.`: stands for current directory)




