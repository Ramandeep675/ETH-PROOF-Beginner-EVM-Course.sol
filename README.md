Key Features Public Variables:

tokenName: Stores the name of the token (e.g., "Matic"). tokenAbbrv: Stores the abbreviation of the token (e.g., "MTC"). totalToken: Stores the total supply of the token.

Balance Mapping: A mapping to keep track of the token balance for each address.

Mint Function: Allows the creation of new tokens and assigns them to a specific address.

Burn Function: Permits the destruction of tokens from a specific address, with a check to ensure sufficient balance.

Deployment Ensure Solidity version 0.8.18 or later is installed. Compile the contract using a Solidity compiler. Deploy the contract on your preferred Ethereum network. Usage

Minting: Use the mint function to generate new tokens and assign them to a specific address. Burning: Use the burn function to destroy tokens from a specific address, ensuring the address has sufficient tokens to proceed.

Token Name and Abbreviation: The contract defines public variables to store the token's name and abbreviation.

Total Supply: It also stores the total supply of tokens.

Mapping: The contract keeps track of each address's token balance using a mapping.

Minting: The mint function allows creating new tokens and assigning them to a specific address.

Burning: The burn function allows destroying tokens from a specific address, but only if the address has enough tokens.
