# MuffinDex
 
Challenge to solve:

Create a Fronttrunning-resistant DEX through Aztec Connect, obtaining the advantage of being able to solve the problem of large orders and in turn obtaining a layer of privacy of the transactions as a Dark Pool Dex.

What we did:

## Aztec Protocol:

On the part of the backend, the documented example of Aztec Protocol was able to run, managing to make some transfers from my account in Metamask interacting with the Aztec contract through its example in Javascript.

My Goeri ETH Address:
- https://goerli.etherscan.io/address/0xa34b5fc6dc798aedd8f90b525662d6c5620e1c22

<img src="https://i.ibb.co/dLYdF4R/image.png">

Here I leave one of the transaction chains that made the example of [Aztec Test](./Aztec%20Test/demo.js).

1. https://goerli.etherscan.io/tx/0x2f3169eb3e457a337c7c5c855ccefcb7a623f9fd4138aae9a2bd046df12987a7
2. https://goerli.etherscan.io/tx/0x4b43dd7955c449ab483e9c425e4bca68dead482a4ab259716cf999ba36dd10db
3. https://goerli.etherscan.io/tx/0x6a9bf1f555e27e8190fe53ea5fb66f1b0991ad32a4430142a9693f7dc22104db
4. https://goerli.etherscan.io/tx/0x9e99a55d909e3de2d721903a4479797c1c18dcced3b13b092f7fab0c0171bd17

## Uniswap:

In order to create the dex it was decided that Uniswapv3 would be used, during the creation of this Dex it was possible to create a pool through its SDK as shown in [Uniswap](./Uniswap/index.ts)

<img src="https://i.ibb.co/2ssmG1F/image.png">

