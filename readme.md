# Titanic

## What is it?
This library provides notebooks that train machine learning models to predict the 
probability of survival for [Titanic](https://en.wikipedia.org/wiki/Titanic) passengers. 
The library is used as an example in the course "Data Analytics with Python" at the Nuremberg Institute 
of Technology ([Technische Hochshule Nürnberg Georg Simon Ohm](https://www.th-nuernberg.de/)).

## Where to get it
The source code is currently hosted on GitHub at:
https://github.com/c4ristian/titanic

## Setup
```sh
conda env create -f environment.yml

conda activate titanic
```

### Install Kernel 
```sh
python -m ipykernel install --user --name=titanic
```

### Run Notebooks
```sh
jupyter notebook --notebook-dir="./notebooks"
```

## License
[Apache 2.0](LICENSE.txt)
