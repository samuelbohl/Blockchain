# Blockchain

The goal of this project was to understand how blockchains work and how they are implemented in their simplest form.

## Functionality

You can create new transactions, view the status of the blockchain and mine.

### Getting started

You need to have installed Flask to use the script. And you need somethin like Postman to make the requests.

### View the chain

make a GET request to:

```
http://localhost:5000/chain
```

### Add a transaction

make a POST request to:

```
http://localhost:5000/transactions/new
```
with a body like:
```
{
 "sender": "d4ee26eee15998ee92c6cd394edd974e",
 "recipient": "0llsxaelr87cjan9ltmnx7w4edd9th",
 "amount": 100
}
```

### Mine the new transaction

make a GET request to:

```
http://localhost:5000/mine
```
