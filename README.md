### How to deploy bytecode to your Ethereum network of choice using Remix
* On [Remix](https://remix.ethereum.org/), deploy `DeployBytecode.sol` on your preferred Ethereum network.
* Copy and paste any smart contract's bytecode and deploy it via the `deployBytecode` function.
* Use a pseudo smart contract or an ABI file to deploy with the `at address` option.

For a pseudo smart contract you only need the same function names and arguments as the contract at the address. These can be abstract functions as they are defined by interfaces. An implementation of those functions is not necessary. While the name of the smart contract's functions must be exact (language matters), the arguments must only match in number and type.

