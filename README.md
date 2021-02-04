# python
## What I learn about python.

* wrapping my head around managing python 'environments':
  * never add the `python.exe` that is installed with anaconda, to your sysmtem PATH. This python file is better to be used in the 'base' environment of your anaconda setup.
  * Add only a stock python installation `python.exe` file into your system PATH.
  * Later when you need to create projects, you would install your selected version of python in a virtual environment. In this environment every package you install is contained and have nothing to do with packages that came with the anaconda installation. 
  * In terminal, use this command to create a new environment: `python -m venv myenv`.
  * Remember to use ` Terminal: Create New Integrated Terminal` to activate your new environment. If the enviroment is successfully activated, its name would be shown at the begining of the terminal command line.
  * In bash, use this command to install a package: `python -m pip install packagename`.
  * always update `pip` after creating a new virtual environment `python -m pip install --upgrade pip`.
  * for more information about how to create an environment follow this guide: https://code.visualstudio.com/docs/python/tutorial-flask
* If while installing a package like `pandas` you get a `permission denied` error, consider installing it using `--user` flag: `pip install --user pandas`. This would install `pandas` in a different directory: `C:\Users\Saeed\AppData\Roaming\Python\Python37\site-packages` (on windows).
* In order to make a `requirement.txt` file which contains the package names and versions of the current environment, first make sure that you have activated the environment and `pip freeze > requirements.txt`.


