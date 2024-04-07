# Warp [⛓️ Crosschain bridge] 

### Problem statement: 

Crosschain bridging in Solana usually face liquidity issue for destination chain bridged tokens, making bridged funds barely usable for any transactions.
Web3.0 native users do not like centralisation and do not want to bridge funds to centralised exchange to swap and bridge.
causing difficulties for cross-chain interoperability and scaling issues.

### Solution:

All-in one crosschain bridge + swap, users will get to choose their src chain and src chain token, dest chain  and dest chain token. Our bridge will swap funds into the valid tokens.

### Additional Feature:

- NFT bridging.


### launch instruction

```
npm install
```

```
npm run dev
```

Or visit our [website](https://warp-finance.vercel.app/)

[Bridge page]([website](https://warp-finance.vercel.app/bridge)


( 

Smart contracts are yet to me made, 

planning to implement swap with :
- raydium on solana, 
-uniswap on evm

womrhole as the primary crosschain messaging protocol

ipfs as storage.


References:
[womrholedocumentation](https://docs.wormhole.com/wormhole)
[uniswap](https://docs.uniswap.org/sdk/v3/overview)
[raydium](https://docs.chainstack.com/docs/solana-how-to-perform-token-swaps-using-the-raydium-sdk)
)


