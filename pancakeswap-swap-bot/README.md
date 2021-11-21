# INTRODUCTION

Hey guys,

I am a big fan of sniping and overall dex trading bots so I built a very simple version of a sniping bot I personally use. It's opensourced so check it out in the "pancakeswap" folder and modify the settings to your liking.

What is done:

- [x]  Buy early token/coins with custom gas fee, slippage, amount.
- [x]  Open source, with free node services already connected

To be done:

- [ ]  Sell bought token

<a href=""><img src="/demov2.png" width="700" /></a>

# HOW TO RUN

Pancakeswap-2:

1. $ npm install (<---- write this after you open the folder in the terminal of your favorite code editor)
1. Set the settings in "Bot settings" at the top of bot.js
1. Input enough funds for fees and purchases into your wallet
1. Run with "node bot.js" command in the same terminal
1. Stop bot with Ctrl + C.


# TIPS AND TROUBLESHOOTING

- For Pancakeswap have at least 1 BNB in your wallet
- For Uniswap at least 0.5 ETH to get everything working smooth as some tokens you will want to snipe have big slippage and if the transaction fails you still pay the gas so don't waste money
- Check new tokens on dextools
- DYOR on dextools and see if the token contract you are sniping doesn't have rug pulls included
- WARNING This bot is free and I did it as a hobby project. Great starting place for new devs. DYOR.


TROUBLESHOOT If your transaction failed:

1. Your gas price is too small 
1. Your slippage is too small (use 20+ for early token)



