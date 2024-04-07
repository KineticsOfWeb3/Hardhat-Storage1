# Hardhat-Storage1

*README.md*

# AdvancedStorage Unit Tests

# Overview
This repository contains unit tests for the AdvancedStorage smart contract using Hardhat, a popular Ethereum development environment. The unit tests ensure the correctness and functionality of the AdvancedStorage contract, which allows for advanced storage management on the Ethereum blockchain.

# Prerequisites
Before running the unit tests, ensure that you have the following prerequisites installed:

- Node.js and npm (Node Package Manager)
- Hardhat Ethereum development environment

 Installation
1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/yourusername/advanced-storage-tests.git
    ```

2. Navigate to the repository directory:

    ```bash
    cd advanced-storage-tests
    ```

3. Install dependencies using npm:

    ```bash
    npm install
    ```

## Usage
After installing the dependencies, you can run the unit tests using Hardhat. The tests are located in the `test` directory and can be executed using the following command:

```bash
npx hardhat test
```

# Unit Tests Description
The unit tests in this repository verify various functionalities of the AdvancedStorage smart contract:

1. Should add an item and emit an event:
   - Tests the addItem function to ensure it adds an item to the storage and emits the ItemAdded event with the correct arguments.

2. Should update total supply and emit an event:
   - Tests the updateTotalSupply function to ensure it updates the total supply and emits the TotalSupplyUpdated event with the correct argument.

3. Should return the correct item count:
   - Tests the getItemCount function to ensure it returns the correct count of items stored in the contract.

4. Should return the correct item details:
   - Tests the getItem function to ensure it returns the correct details (name and quantity) of the specified item.

5. Should revert if trying to access out-of-bounds item:
   - Tests that attempting to access an out-of-bounds item reverts with the appropriate error message.


