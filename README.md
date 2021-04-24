# [FlowX](https://www.onflow.org)

FlowX is a fast, secure, and developer-friendly blockchain built to support the next generation of games, apps, and the digital assets that power them.

- For a high-level overview of FlowX's architecture, check out the [primer](https://www.onflowx.org/primer).
- Details about the protocol can be found in the [technical papers](https://www.onflowx.org/technical-paper).
- For more documentation and tutorials, check out [docs.onflowx.org](https://docs.onflowx.org/docs).

## Getting Started

>  🔨 Let's build!

The following sections introduce common use cases for developers building on Flowx.

### Writing Smart Contracts

> 🏃‍♀️ Cadence is the smart contract programming language of the future.

Cadence introduces resource-oriented programming, a new paradigm that pairs linear types with object capabilities to create a secure and declarative model for digital ownership.

Give Cadence a try and learn the fundamentals with the [FlowX Developer Playground](https://docs.onflowx.org/docs/getting-started-1).

### Managing Keys and Signing Transactions

> 🔑 Sign transactions from any device and stay secure with native multisig support.

FlowX supports a variety of signature algorithms and curves, making it easy for users to manage keys using the secure enclave on their laptop, phone or inside a battle-ready HSM.

Every FlowX account has built-in support for multi-signature transactions, making it simpler than ever to secure your account with multiple weighted keys.

Learn more about accounts, weighted keys and transactions [in this guide](https://docs.onflowx.org/concepts/accounts-and-keys).

### Building Apps

> 💻 Build on FlowX from the comfort of your own dev machine.

The FlowX Emulator is a feature complete replica of the real network that looks, acts and talks like FlowX. You can use the emulator _right now_ to build real applications that are compatible with both testnet and mainnet.

- [Install the emulator](/docs/emulator.md)

### Accessing the Network

> ⛓️ Submit transactions and read chainstate with the FlowX Access API.

The FlowX Access API provides a single unified interface for applications and user agents to connect to the FlowX network. The API is implemented by both the FlowX Emulator and the network itself.

- Submit a transaction
- Query the status of a transaction
- Get the latest block
- Query events emitted by your transactions
- Read state stored in contracts and accounts

You can find an in-depth description of each of the above features in the [FlowX Access API Specification](https://docs.onflowx.org/access-api).

To interact with the Flow Access API from JavaScript you can use the [FlowX JavaScript SDK](https://github.com/onflowx/flowx-js-sdk)

## Documentation

> 📖 Learn the fundamentals of FlowX.

- [Introduction to Cadence](https://docs.onflowx.org/docs/getting-started-1)
- [Accounts, Keys & Signing](/docs/accounts-and-keys.md)
- [Transaction Lifecyle](/docs/transaction-lifecycle.md)
- [FlowX Access API](/docs/access-api-spec.md)
  - [JSON-Cadence Data Interchange Format](/docs/json-cadence-spec.md)
- [Using the Emulator](/docs/emulator.md)

## Tools

> ⚙️ Practical tools for building on FlowX.

### Development

- [FlowX Emulator](/docs/emulator.md)
- [FlowX CLI](/docs/cli.md)
- [FlowX Playground](https://play.onflowx.org)
- [Cadence Visual Studio Code extension](/docs/vscode-extension.md)
