# Mathematics with Python workshop

A short workshop describing how Mathematics can be studied using Python.

This covers:

- Basic symbolic mathematics
- Calculus
- Linear algebra

All notebooks are in the `nbs` folder.

A `conda` environment is defined in `environment.yml`.

## Running tests (for contributors)

To test the outputs in the notebooks. 

Create the environment:

```
$ conda env create -f environment.yml
```

Activate the environment:

```
$ source activate mwp
```

Run the tests:

```
$ pytest --nbval --current-env
```
