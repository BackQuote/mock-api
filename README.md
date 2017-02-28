# BackQuote mock API

Simple mock API for the BackQuote Backtester. 

Ressources exposed : 
  - [http://localhost:5000/algorithms](http://localhost:5000/algorithms)
  - [http://localhost:5000/templates](http://localhost:5000/templates)
  - [http://localhost:5000/simulations](http://localhost:5000/simulations)
  - [http://localhost:5000/tickers](http://localhost:5000/tickers)
  - [http://localhost:5000/runs](http://localhost:5000/runs)
  - [http://localhost:5000/trades](http://localhost:5000/trades)
  - [http://localhost:5000/quotes](http://localhost:5000/quotes)
  - [http://localhost:5000/simulation_tickers](http://localhost:5000/simulation_tickers)

## Requirements
```
npm install -g json-server
```

## Running
To start the mock server, simply run
```
npm start
```
Then, navigate to  http://localhost:5000

To start the server on a different port, use the following command
```
npm run server -- --port=8080
```
