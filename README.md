# RESTful web API for your private blockchain

This project solves the challenge of building a RESTful API using a Node.js framework that will interfaces with the private blockchain.

With this project you can target two endpoints:

GET: /block/blockHeight

POST: /block

## Node framework

The framework selected is Express.js

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

1. Node installed

### Installing

1. Clone this repo
2. cd command to project root folder
3. Install dependencies

```
npm install
```

## Running project

1. Run command

```
node index.js
```

and now you can check the project running in the browser typing:

```
localhost:8000
```

## Endpoints

### GET: /block/blockHeight

```
localhost:8000/block/blockHeight
```

### POST: /block

```
localhost:8000/block
```

With body:

```
{
  "body": "This is body text for block!"
}
```





