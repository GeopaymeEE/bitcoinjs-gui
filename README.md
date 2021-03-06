# bitcoinjs-gui

JavaScript client for the BitcoinJS API. This client connects to an
[Exit Node](https://github.com/bitcoinjs/node-bitcoin-exit) and a
[Wallet Node](https://github.com/bitcoinjs/node-bitcoin-wallet) to
provide a full Bitcoin client in the browser.

# Status

The basic exit node functionality is implemented. However the client
does not yet support the wallet API.

Prototype software, use at your own peril.

# Basic Usage

## Configuration

Copy the config/config.sample.js file to config/config.js and make any
necessary adjustments.

This defines the default settings for all users of your installation.

## Installation

Check out the code using

``` sh
git clone git://github.com/bitcoinjs/bitcoinjs-gui.git --recursive
```

From there, just make sure bitcoinjs-gui/index.html is accessible
through an HTTP server.

## Running

Open the URL for bitcoinjs-gui in your browser.
