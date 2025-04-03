# RAG_fahim

this is teaching platform powered by ai

## Requirments

- python 3.8 or later

### install python using miniconda

1) download and install miniconda from [here](https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh)

2) create a new environment using the following command:

```bash
$ conda create -n mini-rag-fahim python=3.8
```
3) activate the environment:
```bash
$ conda activate mini-rag-fahim
```
## Installation
### install required package:

```bash
$ pip install -r requirements.txt  
```
### setup environment variables
```bash
$ cp .env.example .env
```
set your environment variables `.env` file like `OPENAI_API_KEY` value
### run server
```bash
$ uvicorn main:app --reload --port 2000
```