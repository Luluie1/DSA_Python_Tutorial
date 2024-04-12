# Deployment

I tried to allign the python version and all the pip-dependencies as good as possible with the modules available on EBRAINS. 
At the time of  writing (May 2023), the EBRAINS-23.02 python kernel is used.

## For using this tutorial:

TODO

## For contributing:

We use nb-stripout as a precommit-hook for formatting jupyter notebooks before
commiting. 

0. Make sure that python 3.8 is installed on your system.
1. Clone the repo: `git clone git@github.com:timomit/dsa-python-course.git` and move to directory: `cd dsa-python-course`.
2. Create a virtual environment. Use one the following options:
   - Conda: `conda env create -n dsa-tut python=3.8`, then `conda activate dsa-tut`
   - Python venv: `python3.8 -m venv "dsa-tut"`, then `source dsa-tut/bin/activate`
3. Install python dependencies: `pip install -r requirements.txt`
4. Install the pre-commit hooks: `pre-commit install`.
5. Happy coding!
