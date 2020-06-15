# GGLKS - a simple link retriever

## Running the script

**Prerequisite**
Have Python3 installed!

At the root of this project, install dependencies:

```sh
./install-dependencies
```

Once you've installed the dependencies, re-activate your virtual environment:

```sh
source venv/bin/activate
```

Get the results by running in your terminal:

```sh
./gglks --results 10 find me something
```

### Usage

```text
usage: gglks [-h] [--results N] TERMS [TERMS ...]

Process some url search terms.

positional arguments:
  TERMS        Search terms separated by space

optional arguments:
  -h, --help   show this help message and exit
  --results N  Number of search results. Valid options 10, 20, 30, 40, 50, and
               100
```
