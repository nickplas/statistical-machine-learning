# Statistical Machine Learning

## News

- Please open the notebooks using jupyter, you will not be able to see pictures from the github preview.
- Assignments will be uploaded in `homeworks/`.

## Useful links

- [Stackexchange](https://stackexchange.com/)
- [Github guide](https://guides.github.com/activities/hello-world/)
- [Virtualenvs in python3](https://docs.python.org/3/library/venv.html)
- [Beginners numpy tutorial](http://cs231n.github.io/python-numpy-tutorial/)
- [Beginners pandas tutorial](https://www.learndatasci.com/tutorials/python-pandas-tutorial-complete-introduction-for-beginners/)
- [Pyro 1.2.1 documentation](http://docs.pyro.ai/en/1.2.1/)

## Linux Setup

Download, clone or fork (your choice) this repository in a directory `PATH_TO_DIR/`.

Create a virtual environment using `python3`
```
cd PATH_TO_DIR/statistical-machine-learning/
sudo apt-get install python3-pip
pip3 install virtualenv
virtualenv -p /usr/bin/python3 venv
```

Now you should see `PATH_TO_DIR/statistical-machine-learning/venv/` folder.
Activate the enviroment and install the requirements:
```
source venv/bin/activate
ipython kernel install --name=python3 --user
pip3 install -r requirements.txt 
```

Open your notebooks using jupyter-notebook (or jupyter-lab):
```
python3 -m notebook
```

To deactivate the environment use `deactivate` command.


