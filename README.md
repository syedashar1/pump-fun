# Pump fun Smart Contract

Pump.fun smart contract clone that works just like pump.fun site, like pump.fun, this smart contract creates the pool on contract, and make users to buy and sell from the pool.

anchor-cli-wasm v0.29.0 is used.


### **Instruction Explanations**

1. **`initialize`**  
   Sets up the bonding curve configuration, including parameters like fees and curve constants, ensuring only authorized users can initialize it.

2. **`create_pool`**  
   Creates a liquidity pool tied to the bonding curve, initializing accounts to manage token liquidity and transactions.

3. **`add_liquidity`**  
   Allows users to deposit assets into the liquidity pool, increasing the pool's balance and potentially minting pool tokens as a reward.

4. **`remove_liquidity`**  
   Enables users to withdraw their share of liquidity from the pool, burning their pool tokens and adjusting the pool's balances.

5. **`buy`**  
   Lets users purchase tokens based on the bonding curve price, transferring payment to the pool and minting tokens to the buyer.

6. **`sell`**  
   Allows users to sell tokens back to the pool, burning tokens and receiving payment based on the current bonding curve price.

