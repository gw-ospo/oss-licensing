# jupyter-book-example

This repository demonstrates a working implementation of [Jupyter Book](https://jupyterbook.org/en/stable/publish/gh-pages.html), hosted on GitHub Pages, with automated deployments setup via GitHub Actions.

## Setup

[Make a copy](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template) of this repository template. Then clone your copy of the repository onto your local computer, and navigate there from the command line.

Setup virtual environment:

```sh
conda create -n jbook-env python=3.10
conda activate jbook-env
```

Install packages (including Jupyter Book):

```sh
pip install -r requirements.txt
```

## Managing the Book

### Initialization

The following command was used to create the structure for this book (where "example-book" was chosen as the name of the book):

```sh
jupyter-book create example-book

# consider alternatively:
#jupyter-book create --cookiecutter example-book
```

### Building

Build book as LaTeX (see "example-book/_build/latex"):

```sh
jupyter-book build example-book/ --builder latex
```

Build book as PDF (see ["example-book/_build/latex/book.pdf"](/example-book/_build/latex/book.pdf)):

```sh
jupyter-book build example-book/ --builder pdflatex
```

Build book as HTML: (see "example-book/_build/html/index.html"):

```sh
#jupyter-book build example-book/
jupyter-book build example-book/ --builder html
```

### Deployment

Configure GitHub Pages for your repository to deploy from "GitHub Actions" source.

FYI - the [".github/workflows/deploy-book.yml"](/.github/workflows/deploy-book.yml) file controls the build process. If you use your own book name, customize "example-book" to refer to the book name you chose.

Commit and push to trigger an automated build of your HTML site. Visit the hosted site at your repository's GitHub Pages URL.
