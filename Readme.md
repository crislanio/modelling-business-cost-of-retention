
## Installation

Git clone this repository:

```
git clone https://github.com/kyso-io/template
```

Download and install the [Anaconda Python distribution](https://www.anaconda.com/distribution/).
Then active a conda virtual environment with

```
conda env create -f environment.yml
conda activate dev
```

Install libraries with

```
conda install <library>
```

## Usage

Start programming! Open jupyter with

```
jupyter lab
```

## Sharing

Make sure to export your conda environment if you will be sharing with others:

```
conda env export --no-builds > environment.yml
```