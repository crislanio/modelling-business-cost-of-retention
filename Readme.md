# Modelling Business Cost of Retention

This is a project about customer attrition analysis and customer attrition rates to identify potential customer churn

## Installation

Git clone this repository:

```
git clone https://github.com/KyleOS/modelling-business-cost-of-retention.git
```

Download and install the [Anaconda Python distribution](https://www.anaconda.com/distribution/).
Then active a conda virtual environment with

```
conda env create -f environment.yml
conda activate dev
```
## Some tips
- Connect to [Mongo Atlas](https://studio3t.com/knowledge-base/articles/connect-to-mongodb-atlas/)

Tutorial: Given reference contain various examples of MongoDB operations
- https://www.w3schools.com/python/python_mongodb_getstarted.asp

For more information see this: 
- https://docs.atlas.mongodb.com/import/mongoimport/,
- https://docs.atlas.mongodb.com/connect-to-cluster/


## Installing libraries

Install any libraries you need with

```
conda install <library>
```

Make sure to run the following command to save the installed libraries into the environment.yml file,
this allows others to run the report easily

```
conda env export --no-builds > environment.yml
```

## Usage

Start programming! Open jupyter with

```
jupyter lab
```

And start working.

## Sharing

Push to Github and import into Kyso.

