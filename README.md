# Proof-of-Concept Implementation of a `node.js` Echo Server and Client using `child_process`

This proof-of-concept was motivated by my research into techniques to run a
`node.js` session within
[IJavascript](https://github.com/n-riesco/ijavascript.git).

## Installation

```sh
git clone https://github.com/n-riesco/node-echo.git
npm install node-echo
```

## Usage

To start up the echo client and server, type in the terminal:

```sh
node-echo
```

Every line type in the terminal is read by the client, then sent to the server.
The echo server replies back using the same line. The client prints out every
response sent by the server. E.g.:

```sh
node-echo
Hello, World!
Hello, World!
```

Press CTRL-C to kill both the echo client and its server.
