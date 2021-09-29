# setting-up-simple-python-environment
Lab for setting up simple python environment using venv and pip

1. Make a directory named 'simple-env' by running the command `mkdir simple-env`.
2. Change to this directory by running the command `cd simple-env`.
3. Create a virtual environment named 'env' by running the command `python -m venv env`.
4. Activate the virtual environment by running the command `source env/bin/activate`
5. Get the path for python by running `which python` and confirm that the path to the enabled python points to your virtual environment directory.
6. Run `python -c "import pandas"` to see that pandas is not installed (you should get an error).
7. Use pip to install the library pandas by running the command `pip install pandas`.
8. Run `python -c "import pandas"` again. Now you should get no output.
9. Write your environment to a file by running the command `pip freeze > requirements.txt`
10. See the contents of your requirements file by running `cat requirements.txt`. You should see some package names and versions, including a line for pandas.
