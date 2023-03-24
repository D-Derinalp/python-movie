# Python - Spacy: Semantic Similarity of Texts

This is a Python project that imports Spacy and ready to run on Docker. 
It has sensible defaults for security.

## Table of Contents
1. Requirements
2. Setup
3. What does the project do?
4. Contribute

## 1. Requirements
- Python 3.7 or later versions
- Docker

## 2. Setup

Firstly install [Docker](https://docs.docker.com/get-docker/) on your computer.
Now launch pycharm and configure a project on this working directory.
All following commands must be run only once at project installation.

The first clone of the repository:

```bash
$ git clone https://github.com/D-derinalp/python-movie.git
$ cd python-movie
```

Then install the all dependencies:
```bash
$ pip install -r requirements.txt
```

### Docker Image
Run the following command to create docker image:

```bash
docker build -t python-movie .
```

To create docker container you should run the image with following command:

```bash
docker run python-movie
```

## 3. What does the project do?

This project imports SpaCy and uses Natural Language Processing (NLP) and 'en_core_web_md' language model to find similarities between the texts. 
The project has a function to compare a movie description with a list of movie descriptions to find the most similar movie to watch next.

## 4. Contribute

Contributions are always welcome! 