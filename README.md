# Dockerfile of writing paper using R Markdown

This is a repository of Dockerfile including packages and add-ins that are useful for writing articles with R Markdown in Rstudio. This Dockerfile is based on rocker/binder. This image include Juala and Python.

[日本語解説(Japanese)](https://github.com/ykunisato/paper-r/blob/master/README_jp.md)

Maintainer is Yoshihiko Kunisato (ykunisato@psy.senshu-u.ac.jp)

Keywords: psychology, cognitive science, rstudio, rstan, rmarkdown, julia, python

## Usage

1. Install ["Docker Desktop"](https://www.docker.com/products/docker-desktop)

2. Open "terminal"(Mac) or "Command Prompt"(Windows)

3. Type the following code to pull a Docker container. Change the "password" and "name_of_container" as you like.


**Mac**


```
docker run -p 8888:8888 --name paperb -e JUPYTER_ENABLE_LAB=yes ykunisato/paper-b
```
start-notebook.sh --NotebookApp.token="paperb"

4. Open the web browser and type "http://localhost:8888/" in the URL bar.
