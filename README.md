# BloomFi-Celo
# BloomFi - Smart Contracts
Project for Celo Proof of Ship (Open Track).

## Deployment
- **Network:** Celo Sepolia Testnet 
- **Contract Address:** 0xa7FBc4B8CAE65344821D367698BbF345E15952e0
- **Stablecoin:** cUSD (Mento)

## Logic
A Factory-style ROSCA where users pool cUSD.
1. Users join via `joinCircle()`
2. Users `deposit()` cUSD (requires Approval)
3. Contract automatically payouts the pot to the next member in the queue.
