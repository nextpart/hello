# Getting started @ [nextpart](https://nextpart.io)

## Tools

**Development**
* Versioning: [git](https://git-scm.com)
* `Python` - [Fastapi](https://fastapi.tiangolo.com)
  * python dependency management: [poetry](https://python-poetry.org)
  * linting: [pylint](https://pylint.pycqa.org/en/stable/) & [flake8](https://flake8.pycqa.org/en/latest/)
  * formatting: [black](https://black.readthedocs.io/en/stable/)
* `JavaScript` - [Svelte.js](https://svelte.dev)
  * linting & formatting: [eslint](https://eslint.org) & [prettier](https://prettier.io)
* Editor: [vscode](https://code.visualstudio.com)

**DB's**
* Graph: [arango](https://www.arangodb.com)
* Relational: [postgres](https://www.postgresql.org)
* Blob: [minio](https://min.io)

**Infrastructure**
* [`docker-compose`](https://docs.docker.com/compose/)
* [`kubernetes`](https://kubernetes.io/de/)

**Services**
* [Azure DevOps](https://azure.microsoft.com/de-de/services/devops/) - PM, Repos & Pipelines

## If you want a headstart

**STIX**

Our datamodel, spec can be found [here](https://docs.oasis-open.org/cti/stix/v2.1/csprd01/stix-v2.1-csprd01.html), a more non-formal intro [here](https://oasis-open.github.io/cti-documentation/stix/intro.html). Latter one is recommended as first read, specs only for the brave / bored.
Additionally within this repository there is a mini notebook (located under `/python/stixdemo`) demonstrating the stix datamodel in action.

To run the demo:
1. Clone this repository: `git clone https://github.com/nextpart/hello.git`
1. Ensure you have installed the following:
   - [python3.8](https://www.python.org/downloads/release/python-3814/)
   - [poetry](https://python-poetry.org)
   - [vscode](https://code.visualstudio.com) with [python extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python) and [jupyter extension](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
1. run `cd /python/stixdemo`
1. configure poetry by running `poetry config virtualenvs.in-project true`
1. run `poetry install`
1. Reopen vscode: to activate new venv  
**hint**: hit <kbd>⌘ Command</kbd> / <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> and execute 'Reload Window' command
1. Open [demo.ipynb](python/stixdemo/demo.ipynb) and click 'Run All'  
**hint**: ensure you selected the correct kernel for the notebook, this should happen automatically but sometimes doesn't work

This will also introduce you to our tool for dependency management (poetry).

**Decorators (Python)**

We often utilize decorators as they are a powerful and easy way to abstract functionality.

A good Intro can be found [here](https://realpython.com/primer-on-python-decorators/).
