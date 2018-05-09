# Python 3 based virtual environment

This project can be used to jump-start python project with virtual env. It uses default virtual environment provided by python3 (this project has been built using python3.6).


You may start a new project by cloning this project as:

`git clone git@github.com:neovasolutions/Python-Virtual-Environment.git myproj`

where `myproj` is the name of your project.

`cd myproj`

`python3.6 -m venv _venv_`

`source _venv_/bin/activate`

Now you can install packages as needed with `pip install <package-name>`


All the instructions about how to go about building the project with virtual environment are [here](https://github.com/neovasolutions/Python-Virtual-Environment/blob/master/docs/Python_Neova.pdf)

#### NOTE
This project includes `.gitignore` file that ignores the virtual environment dependencies. Dependencies can be managed as described in the instructions document in `docs/` folder.
