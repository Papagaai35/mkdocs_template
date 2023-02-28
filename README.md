# mkdocs_template
A empty Python-project to setup a good documentation-site based on python-docstrings

## Install
Use `pip` or `conda env` to install the nessesary packages

```bash
$ pip install -r requirements.txt
```

or

```bash
$ conda env update --file conda.yml
```

or

```bash
$ conda env create -n <env_name> --file conda.yml
```

## Use
Place your documentation documents, as markdown-files in `/docs`, and put them in the nav
section of the `mkdocs.yml`. 

Python files in `/src/<package_name>` are automaticaly parsed and included.

`$ mkdocs serve` to start the live-reloading docs server.  
`$ mkdocs build` to build the documentation site (in `/site`)
