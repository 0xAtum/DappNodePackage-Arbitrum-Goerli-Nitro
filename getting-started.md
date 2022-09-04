# Arbitrum Goerli Nitro Node

### Getting Started
Be sure to have a valid Goerli-Eth node (Config/ETH_GOERLI_RPC_URL) by default it's `http://goerli-geth.dappnode:8545`

#### Note:
If you check the log during the initial download, you'll see `transferred XXXXX / XXXX bytes (X.XX%) [XXX Mbps, -XmXXs remaining]` and then nothing else. It seems like this is stuck but in reality, the messages are just continuing without any jump line (They forgot to add one).


### More info
You might want to take a look at [Arbitrum's doc :: Optional-parameters](https://developer.offchainlabs.com/node-running/running-a-node#optional-parameters). There are some interesting parameters that you might want to add into EXTRA_OPTS.