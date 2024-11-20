# Maun

This app looks for duplicate files based on their checksum, name or size. Once it finds one, it then shows the two or more files it finds to be repeated on a tree view.

## How to install

### Linux

Run this from a terminal:

```shell
git clone https://github.com/moltenib/maun
cd maun
./maun.pyw
```

Note that PyGObject and Python should be installed beforehand.

### Windows

#### Easy way

Because the latest installer for PyGObject on Windows doesn't work with newer versions of Python, it will be necessary to get an older version instead.

- Get [Python 3.3 or 3.4](https://www.python.org/downloads/release/python-340/) and [PyGObject for Windows](https://sourceforge.net/projects/pygobjectwin32), after downloading this repo to some folder.

- Now you can run the script `maun.pyw` by double clicking it.

#### Less easy way

This would include manually copying the `gi` module to the Python installation folder, installing it with `pip` or some other method.
