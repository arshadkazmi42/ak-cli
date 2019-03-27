### Deploy python package to PyPI

`twine upload dist/* --skip-existing`

- <b>DIST_DIRECTORY: </b> `dist` directory name or path

#### Example:

`twine upload dist/* --skip-existing`

**Note**: `twine` should be preinstalled, before running this. You can get twine [here](https://pypi.org/project/twine/)

<img src="../../gifs/pypi-deploy.gif" alt="Python Deploy"/> <br>

#### Related

- [Build python project](python-build.md)