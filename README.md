# BackQuote mock API

Simple mock API for the BackQute Backtester. 

Ressources exposed : 
  - [http://localhost:8888/algorithms](http://localhost:8888/algorithms)
  - [http://localhost:8888/templates](http://localhost:8888/templates)
  - [http://localhost:8888/simulations](http://localhost:8888/simulations)
  - [http://localhost:8888/tickers](http://localhost:8888/tickers)
  - [http://localhost:8888/runs](http://localhost:8888/runs)
  - [http://localhost:8888/trades](http://localhost:8888/trades)
  - [http://localhost:8888/quotes](http://localhost:8888/quotes)
  - [http://localhost:8888/simulation_tickers](http://localhost:8888/simulation_tickers)

## Requirements
```
npm install -g json-server
```

## Running
To start the mock server, simply run
```
npm start
```
Then, navigate to  http://localhost:8888

To start the server on a different port, use the following command
```
npm run server -- --port=9999
```