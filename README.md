# Simple Storage

This is a basic Solidity smart contract named SimpleStorage, showcasing fundamental concepts such as state variables, structs, arrays, and mappings.

## Features

- **Storage of Favorite Number**: The contract allows users to store their favorite number using the `store` function.

- **Retrieval of Favorite Number**: Users can retrieve their stored favorite number using the `retrieve` function.

- **Person Struct and List**: The contract includes a `Person` struct representing individuals with a favorite number and a name. It maintains a public array `listOfPeople` to store instances of the `Person` struct.

- **Mapping of Name to Favorite Number**: The contract uses a mapping (`nameToFavoriteNumber`) to associate names with their corresponding favorite numbers.

## Getting Started

1. Go to [Remix](https://remix.ethereum.org/)
2. Paste the code from `FundMe.sol` and `PriceConverter.sol` into new files in Remix
3. Hit `Compile`
4. Hit `Deploy`

For a more in depth blog on working with remix, [read here](https://docs.chain.link/docs/deploy-your-first-contract/)

## Smart Contract Details

- **Solidity Version**: 0.8.19
- **License**: MIT

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
