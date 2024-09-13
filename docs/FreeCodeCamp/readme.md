## Getting Started

### Requirements

- Python >= 3.10 (can be installed with pyenv or with asdf)
- [Poetry](https://python-poetry.org/) == 1.8.1
- [direnv](https://direnv.net/)
- [Docker](https://www.docker.com/)

### Setup

The project is automated using `make` and the [`Makefile`](Makefile)

In the first run, use `make setup` to bootstrap the project setup in your local. This will install dependencies using poetry and create the necessary files. It will also run `make all` for you so you can verify that everything is working in your local.