# MuffinDex
 
Reto a resolver:

Crear un Fronttrunning-resistant DEX a travez de Aztec Connect, obteniendo la ventaja de poder resolver el problema de las large orders y a su vez obteniendo una layer de privacidad de las transacciones como un Dark Pool Dex.

Avances: 

## Aztec Protocol:

Por parte del backend se logro correr el ejemplo documentado de Aztec Protocol, logrando realizar algunas tranferencias desde mi cuenta en Metamask interaccionando con el contrato de Aztec mediante su ejemplo en Javascript.

My Goeri ETH Address:
- https://goerli.etherscan.io/address/0xa34b5fc6dc798aedd8f90b525662d6c5620e1c22

<img src="https://i.ibb.co/dLYdF4R/image.png">

Aqui dejo una de las cadenas de trasacciones que hizo el ejemplo de [Aztec Test](./Aztec%20Test/demo.js).

1. https://goerli.etherscan.io/tx/0x2f3169eb3e457a337c7c5c855ccefcb7a623f9fd4138aae9a2bd046df12987a7
2. https://goerli.etherscan.io/tx/0x4b43dd7955c449ab483e9c425e4bca68dead482a4ab259716cf999ba36dd10db
3. https://goerli.etherscan.io/tx/0x6a9bf1f555e27e8190fe53ea5fb66f1b0991ad32a4430142a9693f7dc22104db
4. https://goerli.etherscan.io/tx/0x9e99a55d909e3de2d721903a4479797c1c18dcced3b13b092f7fab0c0171bd17

## Uniswap:

Para poder crear el dex se decidio que se usaria Uniswapv3, durante la creacion de este Dex se logro crear un pool mediante su SDK como se muestra en [Uniswap](./Uniswap/index.ts)

<img src="https://i.ibb.co/2ssmG1F/image.png">

## Fin del reporte Joaquin.