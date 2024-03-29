# Climate data for over 100 cities

## Description of the data

This dataset features over one-hundred destinations. It includes the average high and low temperature, dry days, snow days, and rainfall, for every month.
It is adapted from [here](https://michaelxander.com/climate-data/).


## How to use

### 1. Clone GitHub repository

Get started by cloning the repo and navigating into this directory:

```
git clone git@github.com:prisma/prisma-datasets.git
cd prisma-datasets/datasets/sqlite/climate
```

### 2. Explore the dataset

Open the `.db` file in an [SQLite browser](https://sqliteonline.com/).


### 3. Explore the dataset with Prisma development mode

A Prisma schema based on the dataset is provided for you already, which will allow you to run Prisma's development mode. 

Prisma's development mode provides you with an endpoint for Prisma Studio (note that you need to install the Node.js dependencies first since the `prisma2` CLI is included there):

```sh
npm install
npm run prisma2 dev
```

You can now open Prisma Studio on: [`http://localhost:5555`](http://localhost:5555).

![](https://i.imgur.com/W8Sp2bDr.png)

The development mode lets you make quick changes to your data model as you develop your application without the need to persist these changes in a migration.  Learn more [here](https://github.com/prisma/prisma2/blob/master/docs/development-mode.md).


### 3. (Optional) Run demo script

A demo script showcasing some sample Photon API calls has been created.  Run:

```sh
npm run start
```
