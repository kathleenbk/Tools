Pino
A very low overhead Node.js logger.

Installation:

npm install pino
yarn add pino

Usage:

const logger = require('pino')()

logger.info('hello world')

const child = logger.child({ a: 'property' })
child.info('hello child!')

API:

https://getpino.io/#/docs/api 
