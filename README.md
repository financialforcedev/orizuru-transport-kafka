# Orizuru Transport Kafka.

[![Build Status](https://travis-ci.org/financialforcedev/orizuru-transport-redis.svg?branch=master)](https://travis-ci.org/financialforcedev/orizuru-transport-redis)
[![NSP Status](https://nodesecurity.io/orgs/ffres/projects/62120cff-b6b1-4eb6-a608-338d22302f65/badge)](https://nodesecurity.io/orgs/ffres/projects/62120cff-b6b1-4eb6-a608-338d22302f65)

Orizuru Transport Kafka is a transport library for the [Orizuru](https://www.npmjs.com/package/@financialforcedev/orizuru) framework.

## Install

```
$ npm install @financialforcedev/orizuru-transport-kafka
```

## Usage

Use this dependency to specify the transport layer that ```@financialforcedev/orizuru``` uses as Kafka.

	const
		// get classes from orizuru
		{ Server, Handler, Publisher } = require('@financialforcedev/orizuru'),

		// get the transport
		transport = require('@financialforcedev/orizuru-transport-kafka'),

		// configure the transport
		transportConfig = {
		};

	new Server({ transport, transportConfig }))...
	new Handler({ transport, transportConfig })...
	new Publisher({ transport, transportConfig })...


## API Docs

Click to view [JSDoc API documentation](http://htmlpreview.github.io/?https://github.com/financialforcedev/orizuru-transport-kafka/blob/master/doc/index.html).