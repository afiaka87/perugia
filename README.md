# `perugia`

> "Those who do not want to imitate anything, produce nothing."
>  \- Dali

`perugia` is a text-to-image generator. 

Give it a phrase - it tries to recreate an image. 


## Disclaimer
This is a fork of the repository https://github.com/lucidrains/DALLE-pytorch designed to be a bit easier to use.

I've changed the name to reflect my position that this isn't the exact same thing as DALL-E and it is confusing to imply otherwise.

This is _not_ the same DALL-E that OpenAI have presented. It is an attempt at recreating its architecture based on the details released by those researchers. There's not a pretrained model yet, but I believe one is right around the corner.

I have not been able to test this code out on Windows 10 yet. I hope that it works using the conda instructions, but please file an issue if it doesn't. 

## Dependencies
- llvm-9-dev
- cmake
- gcc
- python3.7.x
- pytorch=1.6.0
- cudatoolkit=10.1

## Installation

https://github.com/afiaka87/perugia/wiki/Installation

## Training From Scratch
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1dWvA54k4fH8zAmiix3VXbg95uEIMfqQM?usp=sharing) Train in Colab
- https://github.com/afiaka87/perugia/wiki/Train-with-your-Own-Dataset

## Generate images from text
(WIP)

## VRAM Optimizations:
https://github.com/afiaka87/perugia/wiki/Memory-Speed-Optimizations


## Citations

https://github.com/afiaka87/perugia/wiki/Citations
