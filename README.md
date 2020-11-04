# Node.js Fundamentals
Node.js fundamentals challenge applied for the GoStack Bootcamp

## :rocket: About the challenge

In this challenge, I've must create an application to continue training what I have learned so far in Node.js with TypeScript, using the concept of models, repositories and services!

This will be an application to store incoming and outgoing financial transactions, which should allow the registration and listing of these transactions.

## :hammer: Do you want to check it out?

Clone the repository:

```sh
  $ git clone https://github.com/paulo-carvalho93/desafio-fundamentos-nodejs.git
```

```sh
  $ cd desafio-fundamentos-nodejs
  # Installing project dependencies
  $ yarn # or npm install
  
  # Running unit tests
  $ yarn test # or npm test

  # Start API
  $ yarn dev:server # or npm dev:server

```


## POST
```sh
   {
      "title": "Salary",
      "value": 4000,
      "type": "income"
    },
    {
      "title": "Car",
      "value": 2000,
      "type": "outcome"
    }

```

## GET
```sh
{
  "transactions": [
    {
      "id": "e21bd19c-99ba-4eb8-b60b-382825c6f90a",
      "title": "Salary",
      "value": 4000,
      "type": "income"
    },
    {
      "id": "d646a755-2d80-49bb-98a0-115e84f0c187",
      "title": "Car",
      "value": 2000,
      "type": "outcome"
    }
  ],
  "balance": {
    "income": 4000,
    "outcome": 2000,
    "total": 2000
  }
}
```
