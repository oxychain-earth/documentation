# Overview

Oxychain DApp is a platform and a set of smart contracts protocol designed to support oxygen generation and carbon removal practices.

The DApp front-end is designed with the end-user experience in mind, providing a simple way to buy and retire carbon offsets from the [RSK network](https://rsk.co). The protocol provides an on-chain interface for tokenization and retirement of carbon offsets, eliminating middlemen and allowing faster, transparent, and more efficient transactions.

This site will serve as a project overview for Oxychain - explaining how it works, how to use it, and how to build on top of it. These docs are actively being worked on and more information will be added on an ongoing basis.

## Features

* Tokenization of carbon offsets with an ERC1155 implementation \(O2 tokens\) - onlyOwners
* Buy/Sell O2 tokens
* List your O2 tokens
  * Send O2 tokens peer-to-peer
  * Release O2 tokens
* Positive impact history and reference module
* MetaMask integration
* Mobile optimized front-end implementation

## How it works

Oxychain is made of an RSK-ERC1155 token contract. There's a single contract that holds the information of different O2 tokens

