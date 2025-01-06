# Rakesh Personal Website
This is Rakesh Kumar personal website which is still work in progress.


# Development

## Environment Setup
1. Install virtualenv wrapper

```shell
brew install virtualenvwrapper
```
2. Create a virtual env

```shell
mkvirtualenv githubpages
```

3. Run the following command to install the python dependencies.
```shell
pip install -r requirements.txt
```
4. Run the following command to install `pre-commit` hooks. This is one time step. Once it is done then you do not need to repeat it.
```shell
pre-commit install
```

5. Run the following command to run the pre-commit before commiting any changes.
```shell

```

## Build locally
```shell
# Build
mkdocs build

# To launch local website
mkdocs serve
```
