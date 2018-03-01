
# algobox | Forked from ![Melphi/algobox](https://github.com/melphi/algobox)

Algobox is an open source algorithmic trading software. The software is used in production however the profitable strategies are in a privare repository.

If you have a profitable trading strategy you would like to automate please write me at info@robertomarchetto.com, we might consider a business deal.

Thanks for the original version
I will keep working on this repository. See if I could learn something from the original code.

## Modules
The features currently implemented are:

* Multiple connectors support (Currenlty Oanda, IgIndex and FXMC) to receive prices and manage orders.
* Collects histotical price ticks.
* Supports multiple strategies written in Java, other languages like Python can be considered.
* Trading service written in Java and API exposed via REST, this allow to use any language as a client.
* Very basic market rick module which can be extended.
* A good balance of microservice architecture with Docker, without marking the system too complex to manage.
* Client in Python. The management, monitoring and data analysis is performed mostly with [Jupyter Notebook](http://jupyter.org).

## FAQ

### How can I install and use it?
First make sure you have the docker environment. Then download the code and execute 

```bash
docker-compose up
```

### What is this platform aimed at?
The goal of the project is to run profitable strategies and have all the tools requried for analysis, backtest and optimisation. It was not designed for low latency however few milliseconds of lacency are manageable.

### Are you using it in production?
Yes I am, with a simple strategy which is generating decent profits. I plan to add more strategies in future, all the strategies are in a private separated repository.
