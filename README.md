# Rakesh Personal Website

This is Rakesh Kumar personal website which is still a work in progress.

## Development

### Environment Setup

1. Install virtualenv wrapper

```shell
brew install virtualenvwrapper
```

1. Create a virtual env

```shell
mkvirtualenv githubpages
```

1. Run the following command to install the python dependencies.

```shell
pip install -r requirements.txt
```

1. Run the following command to install `pre-commit` hooks. This is
   one time step. Once it is done then you do not need to repeat it.

```shell
pre-commit install
```

1. Once this is done the `pre-commit` command will automatically execute
   before `git commit` command. In case you want to manually run it you
   can run this command:

```shell
pre-commit run --all-files
```

### Build locally

```shell
# Build
mkdocs build

# To launch local website
mkdocs serve
```
