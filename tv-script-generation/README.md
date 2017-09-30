# RNN to Generate Scripts of the TV Show 'The Simpsons'

Using a LTSM-Cell and embedding to generate scripts for tv show 'The Simpsons'.

## How to get started with floydhub
# Prerequisites
- `pip install floyd-cli`

# Running
- `floyd login`

- setup tv-script-generation in floydhub web interface

- `floyd init tv-script-generation`

- `floyd run --mode jupyter --gpu` <br>
displays a `<jobname>` on the console, e.g. meiermark13/projects/tv-script-generation/1

# Finishing
- `floyd stop <jobname>` <br>
e.g.: `floyd stop meiermark13/projects/tv-script-generation/1`
