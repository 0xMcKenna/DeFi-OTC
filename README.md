# Basic DeFi OTC

## Overview

This project aims to build out the basic functionality of over-the-counter (OTC) trades within DeFi but instead of a CEX trading desk filling orders as specified prices all
functionality will be handled by smart contracts. This means traders can fill large orders close to the market price with minimal slippage if there is a counter-party willing
to be on the opposite side of the trade.

## Scenario

Alice has 1000 ETH she wants to offload to a single individual in a non-custodial manner. Bob wants to purchase a large spot bid using a stablecoin such as USDC but does not
want to take the slippage on a DEX or DEX aggregator. This will especially be useful with ERC20 OTC trades.

Alice triggers a sell order at a specific price & transfers assets to the OTC contract. Bob can see this order in the front-end and chooses to fill the entire position or
the minimum amount specified by Alice. Bob then deposites USDC into the contract and the OTC functionality faciliates the swap between the two addresses.

## Functionality

- [] Create a buy/sell order for ETH
- [] Entire position filled w/ USDC
- [] Partial position filled w/ USDC 
