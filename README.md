# Dockerfile of writing paper using R Markdown

This is a repository of Dockerfile including packages and add-ins that are useful for writing articles with R Markdown in Rstudio. This Dockerfile is based on rocker/binder. This image include Juala and Python.

Maintainer is Yoshihiko Kunisato (ykunisato@psy.senshu-u.ac.jp)

Keywords: psychology, cognitive science, rstudio, rmarkdown, stan, julia, python

## Usage

1. Install ["Docker Desktop"](https://www.docker.com/products/docker-desktop)

2. Open "terminal"(Mac) or "Command Prompt"(Windows)

3. Type the following code to pull a Docker container.

```
docker run -v `pwd`:/home/rstudio/home -p 8888:8888 --name paperb ykunisato/paper-b:latest
```

4. Open the web browser and type "http://localhost:8888/" in the URL bar.
