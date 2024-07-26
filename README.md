
# Solana ARB Bot

This repository contains a Solana arbitrage bot that leverages the Jupiter API to find and execute profitable trading opportunities across various Solana-based decentralized exchanges. Additionally, it supports flash loans with Marginfi and Solend, transaction spamming with Jito, custom fees with Helius priority fees, and multi-threaded transaction processing.

*For Sell*

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Demo](#demo)
- [Price](#price)
- [Contact](#contact)

## Introduction
Arbitrage trading involves buying an asset at a lower price on one platform and selling it at a higher price on another. This bot automates the process on the Solana blockchain, ensuring quick and efficient trades using the Jupiter API

## Features
- **Automated Arbitrage:** Automatically identifies and executes arbitrage opportunities.
- **Flash Loans:** Utilizes flash loans from Marginfi and Solend to maximize trading capital.
- **Transaction Spamming:** Supports spamming transactions with Jito using proxy or no proxy.
- **Custom Fees:** Integrates Helius priority fees for custom transaction fees.
- **Multi-threading:** Allows multiple threads with custom values for each transaction.
- **Multiple Nodes:** Enables transaction spamming with multiple nodes for redundancy and efficiency.

## Requirements
- Python: For bot orchestration and script execution.
- Rust and Anchor Framework: For building and deploying Solana programs (if you need to tip Jito according to % profit).
- 2 VPS:
    - One for spamming transactions (At least 4 vCPU)
    - One for the Jupiter API (At least 16 vCPU)
- 2-3 Nodes: For blockhash, Jupiter API, and spamming transactions.
- 1 gRPC: for Jupiter API (if you can)
- Solana Balance: Required for spamming transactions and tipping.

## Demo
- **Account:** [55EbCijru6wHjvehzNGTLzwmkDCH634pGtd9cdbEBXHB](https://solscan.io/account/55EbCijru6wHjvehzNGTLzwmkDCH634pGtd9cdbEBXHB#balanceChanges) | [7777777AhjoS1N5DkTBLgcSoGmgK4WszHvLcPHspM5Xx](https://solscan.io/account/7777777AhjoS1N5DkTBLgcSoGmgK4WszHvLcPHspM5Xx)
- **Transaction:** [Txn1](https://solscan.io/tx/3TzXnd9pv7vnCgBdNjhuWN6hBNse1tJBtnNeTR6rD49unyNTjmrQmqooUs4We3uq9Q8t9A4ncWyiz3QMwW5oFSjw) | [Txn2](https://solscan.io/tx/4iu9AYvfHArrUouuATsPUGBFtyj4xdxjHMJaZMLPC734iAkNshJC9jiXHonYvgPZ2Vsa7VnoJPGGjD6F3ddaTYmF) | [Txn3](https://solscan.io/tx/4dKcknxSj1Bb9SAkqi7MGXGaQ7xSrTAPnVr6c5aq6FYCUSYe6aeWrGSuWNoA95Ta1VcQg6PFxawGLZbw67qKKGTV) | [Txn4](https://solscan.io/tx/34eUXR9jesgrCfKjTJDijPuSoJN4s1ws6QTXtGPvs7wcTZRHrJAdKPQoerbpbS7XF8Yr2Ehr6Vp38wqWm97qx5U7) | [Txn5](https://solscan.io/tx/2pB9oR9evBLmtypustwhzqYCtM7z1E43R7cA7MzV1c2BNPrM1rDPxYytDrrLvgfukWctjhM3pgU8D1vE5DatcvQN)
- **Prove:** Every transaction has a memo with my contact information there![Alt Text](https://i.imgur.com/vXWYGUA.png)

## Price
- **Price: 20 SOL for full source code**

## Contact
- **Telegram:** [@luuvietha](https://t.me/luuvietha)
