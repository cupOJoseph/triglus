# Triglus

A trigonometry smart contract library written in Rust for Arbitrum Stylus. Great for polar coordinate systems and most other trig uses.

## Usage and Import instructions for devs who want to use the library

### Installing as a Foundry Library

To use Triglus as a dependency in your Foundry project, run:

```shell
forge install cupojoseph/triglus
```

This will add the library to your `lib/` directory and update your `foundry.toml` configuration.

### Using in Your Contracts

After installation, you can import and use the library in your Solidity contracts:

#### Solidity 
```solidity
import "triglus/src/Triglus.sol";

contract MyContract {
    Triglas trig_library;
    
    // Your contract logic here

    uint answer = trig_library.cos(x);
}

#### Rust (Arbitrum Stylus)
```rust
use stylus_sdk::prelude::*;

// Import the Triglus library
use triglus::Triglus;
```

## Arbitrum Deployments

Coming soon




## Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

-   **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
-   **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
-   **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
-   **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```
