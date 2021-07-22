# Coinsale_Crowdsale


# Crowd Sale


We need to create an ERC20 token that will be minted through a Crowdsale contract that can leverage from the OpenZeppelin Solidity library.

This crowdsale contract will manage the entire process, allowing users to send ETH and get back PUP (PupperCoin). This contract will mint the tokens automatically and distribute them to buyers in one transaction.

It will inherit `Crowdsale`, `CappedCrowdsale`, `TimedCrowdsale`, `RefundableCrowdsale`, and `MintedCrowdsale`.

Then conduct the crowdsale on the Kovan or Ropsten testnet in order to get a real-world pre-production testing.

## Steps:

1. Using Remix, created a file called PupperCoin.sol and create a standard `ERC20Mintable` token. I used a standard `ERC20Mintable` and `ERC20Detailed` contract, hardcoding `18` as the `decimals` parameter, and leaving the `initial_supply` parameter alone.

2. Created a new contract named PupperCoinCrowdsale.sol, with standard crowdsale features.

3.Then bootstrapped the contract by inheriting the following OpenZeppelin contracts:
* `Crowdsale`

* `MintedCrowdsale`

* `CappedCrowdsale`

* `TimedCrowdsale`

* `RefundablePostDeliveryCrowdsale`

3. 

