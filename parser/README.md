to run ipython notebooks in virtual environment you need to run: 
1. "sudo apt-get install python3-pip" 
2. "sudo pip3 install virtualenv" 
3. "python3 -m venv /path/to/new/virtual/env" 
4. activate virtual env: "source /path/to/new/virtual/env/bin/activate" 
5. install all requirements: "pip install requirements.txt" \
we want jupyter-notebook kernel to run in our current environment, \
so we need to install it (it's included in requirements.txt") \
to deactivate environment simply run: "deactivate"
6. If you want to update requirements.txt after installing new packages in your venv, run "pip freeze > requirements.txt", when your shell is running in (venv).
