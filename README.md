# Pygame Experiments

A simple repo to play with Pygame. Where code taken from the internet, attribution in sub-dir README's.

## Requirements

Python3 (if not already present on your machine).

Install Visual Studio Code (VSCode) from https://code.visualstudio.com/download

In VSCode, install the Python extension provided by Microsoft.

## Setup

Create a virtual environment for your Python code so it does not affect any other Python code on your machine:

```sh
python3 -m venv .venv
```

You must activate the virtual environment:

```sh
source .venv/bin/activate
```

Test Pygame:

```sh
python3 -m pygame.examples.aliens
```

## Edit the game code

Run VSCode in the folder where this file is. For example, from the terminal:

```sh
code .
```

Alternatively, you can use the `File | Open Folder` menu option.

## Run a game

In VSCode, use the Explorer on the left of your screen. Click `breakout` so it opens the directory and then click `breakout.py`. Then press F5 which will run the game.