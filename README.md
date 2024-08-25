<a id="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">

  <h3 align="center">Dice Roll</h3>

  <p align="center">
    The Dice Roll dapp documentation.
  </p>
</div>

## About

<p>
    Dice Roll is decentralized application (dapp) powered by <a href="https://docs.cartesi.io/cartesi-rollups/1.3/">cartesi</a> rollups technology.
</p>
<p> 
    How It Works: The user guesses a number between 1 and 6. The game simulates a dice roll and reveals if the user's guess was correct.
</p>

## Getting Started

Below you'll find instructions on how setting up this dapp locally.

### Prerequisites

Here are some packages you need to have installed on your PC:

- [nodejs](https://nodejs.org/en), [npm](https://docs.npmjs.com/cli/v10/configuring-npm/install), [yarn](https://classic.yarnpkg.com/lang/en/docs/install/#debian-stable)

- [docker](https://docs.docker.com/get-docker/)

- [cartesi-cli](https://docs.cartesi.io/cartesi-rollups/1.3/development/migration/#install-cartesi-cli)
  ```sh
  npm install -g @cartesi/cli
  ```

### Installation

1. Clone this repo
   ```sh
   git clone https://github.com/Koniesjay/dice_roll.git
   ```
2. Install NPM packages
   ```sh
   yarn install
   ```
3. Build and run the dapp via `cartesi-cli`
   ```sh
   cartesi build
   ```
   and
   ```sh
   cartesi run
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage

1. Make an advance request.

```
   cartesi send generic
```

2. Choose Foundry as the preferred chain.

```
❯ Foundry
  Arbitrum Sepolia
  Base Sepolia
  OP Sepolia
  Sepolia
  Arbitrum One
  Base
  Ethereum
  OP Mainnet
```

3. Press Enter for the default RPC URL.

```
RPC URL http://127.0.0.1:8545
```

4. Choose Mnemonic as the preferred wallet option.

```
❯ Mnemonic
  Private Key
```

5. Press Enter for the default Mnemonic phrase.

```
Mnemonic (test test test test test test test test test test test junk)
```

6. Choose your preferred account.

```
❯ 0xf39Fd6e51aad88F6F4ce6aB8827279cffFb92266 9993.476291596530017783 ETH
  0x70997970C51812dc3A010C7d01b50e0d17dc79C8 9899.778501376664201744 ETH
  0x3C44CdDdB6a900fa2b585dd299e03d12FA4293BC 10000 ETH
  0x90F79bf6EB2c4f870365E785982E1f101E93b906 10000 ETH
  0x15d34AAf54267DB7D7c367839AAf71A00a2C6A65 10000 ETH
  0x9965507D1a55bcC2695C58ba16FB37d819B0A4dc 10000 ETH
  0x976EA74026E726554dB657fA54763abd0C3a0aa9 10000 ETH
  0x14dC79964da2C08b23698B3D3cc7Ca32193d9955 10000 ETH
  0x23618e81E3f5cdF7f54C3d65f7FBc0aBf5B21E8f 10000 ETH
  0xa0Ee7A142d267C1f36714E4a8F75612F20a79720 10000 ETH
```

7. Press Enter for the default Application address.

```
Application address (0xab7528bb862fb57e8a2bcd567a2e929a0be56a5e)
```

8. Choose String encoding as the preferred Input option.

```
❯ String encoding
  Hex string encoding
  ABI encoding
```

9. Input your guess string.

```
Input (as string): 2
```

10. Check the running node in your terminal for the result.

```
validator-1  | Dice rolled number 5
validator-1  | You guessed 2
validator-1  | The result didn't match. Try again!!!
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributing

We welcome contributions from the community! If you'd like to contribute to Dice Roll, please follow these steps:

- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes and commit them with descriptive commit messages.
- Push your changes to your forked repository.
- Submit a pull request to the main repository.
- Please ensure that your code adheres to the project's coding standards and includes appropriate tests.

## License

Dice Roll is released under the MIT License.

## Acknowledgments

Dice Roll is built on top of the Cartesi platform and utilizes various open-source libraries and tools. We would like to express our gratitude to the developers and contributors of these projects.
