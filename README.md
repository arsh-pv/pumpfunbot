# PumpPumpBot [Raydium & pump.fun]

The [@PumpPumpBot](https://t.me/pumppumpfunbot) is a telegram bot focused on trading tokens (raydium & pupm.fun) on the Solana block, offering various features and settings.

## Multiple wallet
The wallet management interface allows users to navigate between multiple wallets, refresh wallet details, manage tokens within a wallet, and either import or create new wallets. Additionally, users can export the private key of the current wallet and delete a wallet. These features offer comprehensive control and flexibility for managing cryptocurrency wallets.

## Swap
The swap interface provides options to buy or sell tokens. Users can quickly select preset amounts to trade, such as 1 SOL, 0.1 SOL, or 0.01 SOL, or choose to buy a custom amount (Buy X SOL) and the sell interface allows users to specify the percentage of their available tokens, with options to sell 100%, 50%, or 25% of their balance. This setup facilitates quick and efficient trading.

## Auto Buy
The auto buy interface allows users to set up recurring purchases of tokens. Users can specify the total amount to buy, the amount per interval, and the time interval between each purchase. The interface supports configuring purchases for multiple wallets or a default wallet. Once set, the auto-buy process can be started, it can be used to bump tokens or spread out transactions.

## Sniper
The "PumpPumpBot Sniper" interface is designed for buying or selling newly minted "pump" tokens with specific configurations. Users can set criteria such as market cap limits, creator balance thresholds, and whether the token creator has had a successful previous launch. The bot can be configured to use multiple or a default wallet and can execute automatic selling if certain conditions are met, such as the creator selling their tokens or after a set timeout period. Buy and sell settings, including amounts, priority, slippage, and timeout, are customizable. This tool is tailored for trading in pump tokens based on defined parameters.

This interface also includes an additional feature for **sniper simulation**. When the "Simulate" option is enabled, the sniper bot can perform paper trading on newly minted tokens in real-time, without requiring a set wallet. This simulation mode uses the same settings as a live trade, allowing users to test various configurations and strategies. The bot generates detailed reports on the simulated trades, helping users to analyze their settings before executing real trades. This feature is valuable for users looking to fine-tune their approach to sniping pump tokens without any financial risk.

## Referrals
The "Referral Program" allows users to earn free transactions by inviting others to join using a referral link. Every new user receive 25 free transactions, while the referrer earns an additional 5 free transactions for each new user that uses the link. Users can track their available free transactions using the referral command.

## Settings
The "Global Settings" interface provides default configurations that apply across all operations unless some interface have their own settings then these are overridden.

## Commands
- **/start** - Open dashboard
- **/wallets** - Manage all wallets
- **/swap** - Buy | Sell a token, pass token or pump.fun url
- **/snipe** - Snipe newly minted coins
- **/referral** - Check free transactions
- **/settings** - View | Edit settings
- **/cancel** - Cancel any scheduled job
- **/support** - Support links
- **/help** - Get all commands
