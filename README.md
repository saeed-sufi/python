# python
## What I learn about python.

* wrapping my head around managing python 'environments':
  * never add the `python.exe` that is installed with anaconda, to your sysmtem PATH. This python file is better to be used in the 'base' environment of your anaconda setup.
  * Add only a stock python installation `python.exe` file into your system PATH.
  * Later when you need to create projects, you would install your selected version of python in a virtual environment. In this environment every package which is installed is contained and have nothing to do with packages that came with the anaconda installation. 
  * In terminal, use this command to create a new environment: `python -m venv myenv` 
  * In bash, use this command to install a package: `python -m pip install packagename`
  * for more information about how to create an environment follow this guide: https://code.visualstudio.com/docs/python/tutorial-flask
* In order to make a `requirement.txt` file which contains the package names and versions of the current environment, first make sure that you have activated the environment and `pip freeze > requirements.txt`


