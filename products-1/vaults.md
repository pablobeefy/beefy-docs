# Vaults

### What is a Vault?

Vaults are investment instruments that employ a specific set of strategies for yield farming. They make use of automation to continually invest and reinvest deposited funds, which help to achieve high levels of compounded interest. They are the core of the Beefy.Finance ecosystem.

When browsing the vaults on the platform, you will see the annual percentage yield \(APY\) which takes into consideration all compounding. You will also see the daily interest and amount invested in the vault by all users. 

Each vault can either refer to a pair of tokens invested in liquidity pools within the Binance Smart Chain ecosystem or a single token invested in lending platforms. After investing their tokens, the user is supplied with mooTokens which represent their stake.

Anyone in the Cowmunity can work together to build new strategies and submit them to governance for voting.

Simply put, vaults can:

* Use any asset as liquidity.
* Provide one asset as collateral for another.
* Manage collateral at a safe level to mitigate default.
* Put any asset to work generating a yield.
* Reinvest earned profits.

### Why can't someone just do this themselves?

They could, but vaults help you save on gas, maintain healthy collateral to debt ratios, self-optimize for the best possible yields, and automatically reinvest earnings. Attempting to do this manually would result in large inefficiencies.

### Does the vault page show the APY?

Yes. Our displayed APY values reflect the predicted rate earned on a vault in a year. This rate is determined by the platform, the strategy it's interacting with at the time, and also takes into account the effect of compounding. As a unique feature, we have also included all vault fees in the APY calculation. What you see is what you get, according to the calculations on the day.

### What risks do the vaults have?

* The team does take steps to quantify the security risks of smart contracts and only will interact with ones that meet a specific set of requirements. 
* As with any smart contract, an investor’s funds can end up stolen or unable to be withdrawn. 
* Assets deposited into the vault have no risk of decreasing in quantity but can decrease in monetary value. For example, when depositing 10 BNB, you will always be able to withdraw 10 BNB, but BNB may decrease in monetary value during that period.

### **What are the different vaults?**

* **Money Market :** Utilizes stable lending platforms, such as Fortube, to generate the highest possible yield for these coins \(BUSD, LINK, DOT, DAI, USDT, ETH, or BTCB\). 
* **Native Token Farming :** Takes advantage of the high yield on popular farms by depositing another asset to earn, sell and compound profits of the native reward token.

### What will I get out when I make a vault withdrawal?

* You will always withdrawal only the token type that you deposited. 
* You will get the amount you put in, plus the yield generated,  minus the fees.

### What are the fees?

* Vaults have a 0.1% withdrawal fee.
  * The main purpose of this fee is to prevent possible exploits from bad-faith actors. Without the fee, somebody could deposit just before the harvest\(\) function execution and withdraw straight after that event, taking a % of the gains generated by legitimate stakers.
* Performance fee on additional yield.
  * This performance fee was implemented to promote community engagement and governance participation. A successful and engaged community is critical for our further growth, which in-turn rewards platform users. 
  * A small portion of the performance fee is also routed to a treasury which will be used to fund further platform security and product initiatives.
  * Currently, the performance fee varies, depending on the vault being used, and is detailed in each vault section.
* Call fee of 0.5% during each harvest\(\)
  * This fee is used to cover the cost of each harvest\(\) call.
  * It is a shared cost across all vault users and significantly cheaper than performing transactions individually.

### **Does Performance fee get taken out when I withdraw my funds?**

* No,  the fees are taken every time someone calls the harvest\(\) function.

### **How often are balances updated in the vaults?**

* Pending rewards are not reflected in the balance until they are swapped for the initial deposited token. This can vary depending on the strategy running. 

### **Why do I have less mooToken than the amount of tokens I deposited?**

* The mooTokens represent the share of the Vault the user has. As the vaults generate profit, the amount of shares \(mooToken\) remain constant, and the underlying token amount increases. 
* There is no deposit fee, so the amount of tokens you deposit is maintained the second after you deposited. That amount should increase over time as the strategy generates profit.
