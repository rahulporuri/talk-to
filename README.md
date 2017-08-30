# talk-to

to be able to build the docs, do the following
```
$ virtualenv .venv
$ pip install -e deps
$ python setup.py build_sphinx
```

Note : The last command needs to be from the dir where the `setup.py` file is.

Once the `$ ... build_sphinx` command has been run, html pages from the rst
source files should have been generated. The html pages should be in `doc/build`

If you want to update the website, copy the contents of the `doc/build`
directory into the `gh-pages` branch.
