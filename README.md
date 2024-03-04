# Simple Storage

This is a basic Solidity smart contract named SimpleStorage, showcasing fundamental concepts such as state variables, structs, arrays, and mappings.

## Features

- **Storage of Favorite Number**: The contract allows users to store their favorite number using the `store` function.

- **Retrieval of Favorite Number**: Users can retrieve their stored favorite number using the `retrieve` function.

- **Person Struct and List**: The contract includes a `Person` struct representing individuals with a favorite number and a name. It maintains a public array `listOfPeople` to store instances of the `Person` struct.

- **Mapping of Name to Favorite Number**: The contract uses a mapping (`nameToFavoriteNumber`) to associate names with their corresponding favorite numbers.

## Usage

1. Deploy the contract on a compatible Ethereum blockchain.
2. Use the `store` function to set your favorite number.
3. Retrieve the stored favorite number using the `retrieve` function.
4. Add a person with a name and favorite number using the `addPerson` function.

## Smart Contract Details

- **Solidity Version**: 0.8.19
- **License**: MIT

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
