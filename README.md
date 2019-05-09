# sample-graphviz

A very quick demo of how to visualize sklean decision trees.

## Setup

For most purposes, viewing the notebook here on Github is all you
need. That said, if you want to clone the repo and play around with
it, I recommend using a virtual environment:

    $ git clone https://github.com/wbadart/sample-graphviz \
        && cd sample-graphviz \
        && virtualenv -p `which python3` .venv \
        && source .venv/bin/activate \
        && pip install -r requirements.txt \
        && jupyter lab

This command should pop open a tab in your browser with a Jupter lab
session up and running. You'll be able to open up `demo.ipynb` from
the file explorer tab.
