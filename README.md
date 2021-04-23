# README #

This code contains some useful patterns which can be resued across multiple datsci projects.

### How do I get set up? ###

This code requires python 3.x.

This code assumes the data is available in the following folder structure:

parent_folder/
├── src
│    ├── current notebook.ipynb
├── data
│   ├──raw
│   │   ├── data.csv
│   ├──train
│   ├──test

In order to install the requirements please run (in the folder containing the requirements file):
```
pip install -r requirements.txt
```

In order to avoid clashes with current version it's suggested to run a virtual environment. 
This can be done by running the following in cmd (it is suggested to use the anaconda python distro):

```
python -m venv ENVIRONMENT_NAME  
```

A jupyter kernel can then be created for the vitual environment as below:

```
ipython kernel install --user --name=ENVIRONMENT_NAME
```


### how do I run the code ###

This code has been developed on the windows operating system and may not work on others.

Follow set up instructions above and open the jupyter notebook and run the cells in the order from top to bottom.
