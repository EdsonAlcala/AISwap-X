# AISwap-X
Cross chain swaps with intents using natural language and a novel OFA model for instant cross chain swaps.

<img width="1370" alt="Screenshot 2023-07-23 at 00 43 08" src="https://github.com/EdsonAlcala/AISwap-X/assets/3077635/4f97d932-e9fb-48cd-a57b-abd0d4ba11d7">

## Architecture

The AISwap-X architecture consist of 3 elements:

- [AISwap-X UI](https://github.com/EdsonAlcala/aiswap-frontend). A user friendly interface, where Swappers can express their intent using natural language .
- [AISwap-X Protocol](https://github.com/EdsonAlcala/aiswap-x-contracts). The coordination mechanism that allows Swappers and Bidders to interact in a secure way using the UMA optimistic oracle.
- [AISwap-X Market Makers Engine](https://github.com/EdsonAlcala/aiswap-x-market-maker). A custom implementation that allow bidders to submit bids in order to win a swap intent and fullfil user's orders.

## Demo 

Check the [Demo](https://aiswap-webapp.vercel.app/)

Check the [Video](https://www.youtube.com/watch?v=TQbNctSCdpk)

Note: It requires to run infrastructure and is currently running in my computer. So if it doesn't work reach out to me edson.alcala@machinalabs.tech.

Be aware of some limitations:

- Only supports cross chain stablecoin swaps
- Only supports Gnosis chain, Arbitrum, Linea
 
## Technologies
- Langchain
- Solidity
- Next.JS
- Wagmi
- Ethers
- Docker
