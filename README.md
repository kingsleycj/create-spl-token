# Creation of an SPL token

## Steps to creating a new token

- Create a devnet/custom RPC connection
- Create a new wallet from a generated keyPair (fromWallet and toWallet)
- Airdrop SOL into that wallet for confirmation of transactions
- Create a new token mint (ie a new mint account) and get the token account from the fromWallet
- Mint a new token to the fromWallet with the newly created mint account
- Get the token account of the to-wallet address and if it does not exist, create it
- Transfer the new token to the to-wallet's token account that was just created
- Transfer the new token to the "toTokenAccount" we just created

## Run
* Clone this repository
* run `node index.js` and results should look like:
    * mint tx: 5zzT4tXiv4hHVKAU7KZA45xAJMAAcus9iAF19kXEUcSe3KwBvumEKfmak739qnQrqLhC3UgFhMEXbqs2Luc8QQFz
    * transfer tx: 2ZxmiftpkLhS3X6aMChpyJ5U2Zi2tyJMXs8wgxj3kkcqcezmcaTVDEqsyf4SVQbSMUJwFNMZbsAugAwfYcpYr7qU


# LICENSE
METACRAFTERS ACADEMY