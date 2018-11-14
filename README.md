# YEdit

A super simple tool to make editing JSON files more human-friendly.

## Why?

I have been doing a lot of work with manipulating trees of JSON data recently. JSON was never really designed for humans, and as such it is non-trivial to read.

## What?

YEdit will open your JSON file of choice, in your editor of choice, but will convert it to YAML for your ease of viewing.

## Limitations

YEdit currently only works on Unix systems, I haven't needed to use it on Windows yet. Feel free to Pull Request.

## Installation

Currently, you have to clone the repository, run `pipenv install`, and then run `yedit`.

I'll add it to PyPI and AUR, possibly a PPA when I have time.

## Usage

```
Usage: yedit [OPTIONS] FILENAME

Options:
  --help  Show this message and exit.
```