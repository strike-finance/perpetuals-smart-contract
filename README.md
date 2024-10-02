# Strike Finance Perpetuals Smart Contract

## Table of Contents

- [What are Perpetuals](#introduction)
- [Technical High-Level Overview](#technical-high-level-overview)
- [Smart Contract Implementation](#smart-contract-implementation)
  - [Batcher](#batcher)
  - [Enter Position](#enter-position)
  - [Close Position](#close-position)
  - [Stop Loss](#stop-loss)
  - [Take Profit](#take-profit)
  - [Provide Liquidity](#provide-liquidity)
  - [Withdraw Liquidity](#withdraw-liquidity)

## What are Perpetuals
Perpetual futures are a type of derivative contract that allows traders to speculate on the continuous price movement of an underlying asset without an expiration date, enabling positions to be held indefinitely. These contracts typically offer leverage, meaning traders can control larger positions with a relatively small amount of capital by essentially borrowing, which amplifies both potential gains and losses. To manage the increased risk associated with leveraged trading, perpetual futures require maintenance margins—minimum account balances that must be maintained to keep positions open. 

There are two positions that a trader can take, a long and a short. Traders will open a long position when they think the underlying asset will up in value and a short position when they think it will go down in value. To open a position, the trader will need to deposit USDM as collateral. 

**Scenario** 
**Long Position**


**Short Position** 


When traders use leverage, they will need to pay interest on the amount borrowed hourly. The formula for calculating borrowed hourly is as follows

## Technical High-Level Overview

## Smart Contract Implementation

### Batcher

### Enter Position

### Close Position

### Stop Loss

### Take Profit

### Provide Liquidity

### Withdraw Liquidity
