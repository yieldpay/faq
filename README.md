
# Vaults

What happens to my funds in the vault?

They are invested using a series of smart contracts into yield farming and other attractive opportunities. Interest and other tokens received as yield are automatically sold to compound profits, so that your investment grows over time without any action needed on your part.

What's a lock up?

Some vaults have a lock up period, meaning that you will need to wait a period of time before taking out your investment. This feature is especially used in investments that carry a risk of impermanent loss (a loss due to price movements that will be eliminated if the prices return to previous levels), where it helps to smooth out such fluctuation and prevents malicious actors from attempting to attack the pools by timing their entries and exits to harm other investors.


Naturally, to protect investors, the contracts have been written to make it impossible for us to extend the lock up period.


# Risks and Protection

Are my funds at risk?

Every investment carries some type of risk; ours are no exception. Please see the risk disclosure attached to each vault product before making any investment decisions.


What is YDP's Investor Protection Commitment?

All our vaults have a maximum withdrawal fee of 0.3%. The contract only allows us to lower this fee, never to raise it, so that there is no risk that your funds can be held captive. Likewise, all strategy contracts only allow profit fees to be lowered from their original level. We believe vaults should be usable as passive investments that do not need to be monitored constantly. Other projects, like YFII, have increased their management fees in the past, potentially leaving investors unwittingly paying more than they signed up for. We will not do that, and we've ensured we cannot do that.



# Fees and Token Burn



What fees are there?

Note that under our Investor Protection Commitment, fees can only be reduced in the future. The current fee level serves as a hard cap on any future fees.

There is a withdrawal fee of 0.3% on removing funds from a vault.

The vaults have total fees on profits of 4%. Of this, 1% is paid to whoever triggers the harvest function. That function can be called by anyone, including you. The remaining fee (currently 3%) is divided between a token burn function, the YDP treasury, and the strategy creator. See the following questions for details on each of them.

Note that some vaults generate income in multiple ways. Some of the income is fee-free. For example, for Curve pools the profit fee is only applied to harvested CRV tokens. The underlying tokens may also generate swap fees and interest, for which there are no fees.


What is the token burn?

A portion of each harvest (currently 0.6% but subject to change as voted by token holders) is used to permanently remove YDP tokens from circulation for the long term benefit of token holders. The fee is automatically taken on each harvest and sent to the Incinerator smart contract. Anyone can call the burn function of the contract to recycle the collected tokens into YFP and to burn them.


What is the YDP treasury?

Funds collected into the treasury will be automatically distributed to token holders who stake their YDP in the governance contract. Token holders may also vote to use them in other ways to benefit the YDP ecosystem.


Who are strategy creators? How can I become one?

Anyone can do their part! You are welcome to submit your own strategies for consideration. Strategy contracts that pass initial checks will be voted on by the token holders. For your efforts, you will receive a portion of the profit fees.

We will publish detailed strategy development guidelines here soon.




# YDP and Competitors


Aren't you just a copy of yearn.finance?

In the spirit of open source, we have built upon the work of projects like yearn.finance, much like they built upon the work of other projects like Synthetix. However, we are hard at work on our own innovative DeFi products, and we expect in time to influence other projects to come.


Aren't you harming development by undercutting others like yearn.finance?

On the contrary, competition forces everyone to pay more attention to the needs of their investors, both by keeping fees affordable and by protecting investors' interests in good faith.

In a recent scandal, yearn.finance promised early vault investors they would be able to claim the CRV tokens they'd earned, yet then decided to renege on its promise and keep the tokens as a yield boost. A competitive field where investors have many options to choose from works as a deterrent against such unethical behavior. We hope that our Investor Protection Commitment will become standard practice in the future.

In short, we believe we are working to the benefit of not only our vault investors and YDP token holders, but also the field of DeFi as a whole.


# About YDP

Who are the team?

We are a group of DeFi enthusiasts with a long experience in the field. We believe at this time the product can speak for itself without being carried by association with our previous projects.


What is the YDP token?

YDP is the governance token of the YieldPay DAO. It entitles holders to vote on changes to the way YieldPay operates, such as adding new vaults and other products, reducing fees, and spending treasury funds on new initiatives. It also entitles holders to share in the revenue generated by YieldPay, for example from vault fees.


How can I get YDP tokens?

We will be releasing YDP tokens to the public in an initial yield mining initiative. Future issuance of tokens will be voted on by token holders. YDP tokens will be distributed to liquidity providers over a period of time, as detailed in this schedule:

(TODO: insert actual dates)

Seed pool: Stake DAI, USDC, USDT or TUSD to gain YDP tokens. 5% of total YDP tokens to be farmed, starts at t, lasts for 2 weeks.
Team allocation: 12%, vests evenly over 1 year starting from t.
YFI pool: stake YFI/YDP in a 98/2 Balancer pool. 8% of total YDP tokens to be farmed, starts at t+2, lasts for 8 weeks.
YFII pool: stake YFII/YDP in a 98/2 Balancer pool. 4% of total YDP tokens to be farmed, starts at t+2, lasts for 8 weeks.
BTC pool: stake RenBTC/wBTC/YDP in a 49/49/2 Balancer pool. 14% of total YDP tokens to be farmed, starts at t+5, lasts for 8 weeks.
WETH pool: stake WETH/YDP in a 98/2 Balancer pool. 14% of total YDP tokens to be farmed, starts at t+5, lasts for 8 weeks.
LINK pool: stake LINK/YDP in a 98/2 Balancer pool. 14% of total YDP tokens to be farmed, starts at t+5, lasts for 8 weeks.
Vault token pool: stake ydpCRV/YDP in a 98/2 Balancer pool. 14% of total YDP tokens to be farmed, starts at t+12, lasts for 8 weeks.
YDP pool: stake YDP tokens. 15% of total YDP tokens to be farmed, starts at t+4, lasts for 26 weeks.
Distribution of rewards to the governance contract begins concurrent with the ending of the YDP staking pool.


