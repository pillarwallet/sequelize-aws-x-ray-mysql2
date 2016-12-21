# sequelize-aws-x-ray-mysql2

The `sequelize-aws-x-ray-mysql2` module is a [`Sequelize`](http://sequelizejs.com/) extension for [AWS X-Ray](https://aws.amazon.com/xray/) to capture MySQL queries.
This module requires the `mysql2` module not the `mysql` module.

## Installation

```
npm install --save sequelize-aws-x-ray-mysql2
```

## Usage

```
var Sequelize = require('sequelize');

var db = new Sequelize({
    dialect: 'mysql',
    dialectModulePath: 'sequelize-aws-x-ray-mysql2',
});
```
