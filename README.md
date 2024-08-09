## Pre-requisites

Before you begin, do ensure you have the following installed on your system:

- Git
- Node.js

## Project Setup ⚙️

1. Clone the repository

```bash
git clone https://github.com/clement-stackup/token_swap.git
```

2. Navigate to the project directory:

```bash
cd token_swap
```

3. Install the necessary dependencies & libraries

```bash
npm install --save
```

4. Configure Environment Variables
   Create a .env file in the root directory of the project and populate it with the following environment variables:

```
RPC_URL=<Your Ethereum Node RPC URL>
PRIVATE_KEY=<Your Private Key>
```

## Project Overview 📝

This project is designed to:

Approve tokens for swapping.

1. Fetch the pool information from Uniswap.
2. Prepare parameters for swapping USDC for LINK tokens.
3. Execute the token swap.
4. Supply the swapped LINK tokens to Aave Lending Pool.

Now that you're set up, Follow the steps as outlined in the campaign. Each step contains detailed instructions to guide you through the process. 📜

## Conclusion

This project allows you to perform a complete DeFi operation by swapping tokens on Uniswap and supplying the swapped tokens to Aave Lending Pool.

For further assistance or questions, feel free to reach out to the community or refer to the [Uniswap documentation](https://docs.uniswap.org/) and [Aave documentation](https://docs.aave.com/developers).
