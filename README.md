# lightWalletCLI

A php based cli wallet for [Gaman][Gan] blockchain. Gaman is an Blockchain which containing GAN Coin as the main cryptocurrency. This blockchain is forked from Arionum (ARO) Blockchain.

Requires php 7.2

## Usage

```bash
light-gaman-cli [command] [options]
```

## Commands

Command                                                                                     | Description
------------------------------------------------------------------------------------------- | ------------------
`balance`                                                                                   | Prints the balance
`export`                                                                                    | Prints the wallet data
`block`                                                                                     | Show data about the current block
`encrypt`                                                                                   | Encrypts the wallet
`decrypt`                                                                                   | Decrypts the wallet
`transactions`                                                                              | Show the latest transactions
`transaction [id]`                                                                          | Shows data about a specific transaction
`send [address] [value] [message]`                                                          | Sends a transaction (message optional)
`alias send [alias] [value] [message]`                                                      | Sends a transaction to an alis (message optional)
`alias set [alias]`                                                                         | Set your alias to the specified value
`masternode create [ip]`                                                                    | Send a masternode announcement transaction
`masternode pause`                                                                          | Pause the masternode
`masternode resume`                                                                         | Resume the masternode
`masternode release`                                                                        | Close the masternode and return the funds
`masternode voting-key`									    | Generates and sends to the blockchain the voting key
`masternode vote [voteid]`								    | Votes for a blockchain config change
`masternode change-ip [ip]`								    | Changes the masternode IP
`asset create [max_supply] [tradable] [price] [dividend only] [autodividend] [allow_bid]`   | Transforms this wallet into an asset
`asset send [asset id] [destination] [amount]`                                              | Sends asset units to another address
`asset market [asset id] [price] [units] [cancelable] [ask/bid]`                            | Submits an order on the blockchain asset market
`asset cancel-order [order-id]`                                                             | Cancels a blockchain asset market order
`asset dividends [amount]`                                                                  | Distributes amount as dividends to all asset holders
`asset inflate [amount]`                                                                    | Increases the max supply if the asset is inflatable
`asset balance`                                                                             | Shows all assets

To activate the testnet mode, create a file called .testnet in the same folder

## Development Fund

Coin | Address
---- | --------
[ARO]: | UnhhKyFdmdRrHDFxEyLJ76Q1JSxYfGptjj3W2hTJDkDpv2j9prUEsC6EwaGDMgHF4DA8QvR7vKCy4sKpE8tLfqa
[LTC]: | 
[BTC]: | 
[ETH]: | 
[BCH]: | 

If you'd like to support the Gaman Blockchain development, you can donate to the addresses listed above.

[aro]: https://arionum.com
[ltc]: https://litecoin.org
[btc]: https://bitcoin.org
[eth]: https://ethereum.org
[bch]: https://www.bitcoincash.org
