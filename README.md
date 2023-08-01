# Title

In this repo we will have a look at various topics related to {Title}.

### The way to success:

Please work in pairs through all the notebooks in this particular order:

1. [Notebook template](1_Notebook_template.ipynb)


Keep in mind, you succeed better as a team. There are NO stupid questions! If you already feel comfortable with the concepts, you might even learn more from teaching them!


## Testing

Some of the notebooks, the ones with exercises for you also have tests. These tests work as long as you use the signature we provided. 
How to run the tests:
```bash
pytest # this will run all the tests
pytest test/test_1_Notebook_template.py # this runs only tests for first notebook
```

In case you are wondering if your code is right or not, you can use the tests to see if your code returns the correct outputs.


### Environment

Same procedure as last time...

Use the requirements file in this repo to create a new environment. If you use `make setup` to install the environment make sure to activate it afterwards using the `source` command.

```BASH
make setup

#or 

pyenv local 3.9.4
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```
