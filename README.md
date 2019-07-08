# Python Introduction

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org:/repo/luispedro/talk-python-intro)

[Launch this on binder](http://beta.mybinder.org:/repo/luispedro/talk-python-intro)

Luis Pedro Coelho<br />
luis@luispedro.org<br />
[@luispedrocoelho](https://twitter.com/luispedrocoelho)

## Install

    pip install -r requirements.txt

## Serving Non-Interactive Presentation Locally

    jupyter-nbconvert index.ipynb --to slides --post serve

## Serving Interactive Presentation Locally

first you need to install raise

    pip install raise
    jupyter-nbextension install rise --py --sys-prefix

