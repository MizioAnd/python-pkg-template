# Example Package

Prequisites is build package and python 3
$ python3 -m pip install --upgrade build

Now run this command from the same directory where pyproject.toml is located:
$ python3 -m build

which generates two files in the dist folder

To install the package into your local env run:

$ python3 -m pip install --no-deps example-pkg-mizioand-0.0.1.tar.gz