# Hello world
Simple hello world application that gets ETH balance for an address.

Source: [ethbalance](https://github.com/shawntabrizi/ethbalance)


## Technologies involved

Technologies used so far in a somewhat particular order.

* [web3.js](https://web3js.readthedocs.io/)
* [Ethereum](https://ethereum.org/en/developers/docs/)
* [Metamask](https://metamask.io/)
* [http-server](https://www.npmjs.com/package/http-server)


## Run locally

* Install [Metamask](https://metamask.io/) in your browser, will be used as a web3 provider to connect to Ethereum.
* Serve the files in this directory with `http-server` or some other http server.
* Access the website locally on http://127.0.0.1:8080/
* Type in an Ethereum account on mainnet, either your own or one you find on [etherscan](https://etherscan.io/)


## Ideas for improvement and learning

* Make the fronten prettier.
* Implement [ENS](https://ens.domains/) support to be able to look up accounts via their ENS names, eg. `alice.eth`.
* Make it possible to use a local ethereum provider and use that by default if available.
* Make it detect Metamask and use that if available.
* Make the page usable without Metamask, meaning use a public provider such as [Cloudflare](https://developers.cloudflare.com/distributed-web/ethereum-gateway), 
* Also print the balance of popular ERC20 tokens.
* Print any other information about the account.