# Build a Python Package and upload it to Pypi repo

 - First clone this repo and install dependencies `pip install -r requirements.txt`
 - Create a setup.py file and fill it with your package info (use the one provided in this repo as template)
 - Put your package code into a subfolder
 - Build your package `python setup.py bdist_wheel`. It will create a `dist` folder with your built package.
 - Create a `~/.pypirc` file with your pypi repo data (use the one provided in this repos as template)
 - Upload your package with `python -m twine upload dist/*`

