# langchain-jupyter-01
---
To be able to run the notebooks from the [LangChain Short Course](https://learn.deeplearning.ai/langchain/lesson/7/agents) one must be able to run jupyter notebooks.

This repo will build a jupyter environment with the proper modules installed in order to run the notebooks in this lessons, but locally.

Step 0:
clone the repo.

Step 1:
Build the image

`docker build --rm -t docker-jupyter-extensible .`

Step 2:
using docker compose, run a container using that image

Step 3:
access the jupyter environment from https://127.0.0.1:8888

the token/password can be found in the console from Step 2
