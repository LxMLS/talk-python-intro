# Python Introduction

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/LxMLS/talk-python-intro/master)

Luis Pedro Coelho<br />
luis@luispedro.org<br />
[@luispedrocoelho](https://twitter.com/luispedrocoelho)

(modified by Ramón Astudillo)

## Install

    pip install -r requirements.txt

## Serving Non-Interactive Presentation Locally

    jupyter-nbconvert index.ipynb --to slides --post serve

## Serving Interactive Presentation Locally

first you need to install raise

    pip install raise
    jupyter-nbextension install rise --py --sys-prefix

an additional button will appear on the notebook to toggle presentation mode
on/off. Click on the interrogan ot get on comands (e.g. space to advance)
