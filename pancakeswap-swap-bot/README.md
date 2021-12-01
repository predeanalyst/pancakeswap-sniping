# TUTORIAL

Hey,

If you want to snipe and swap tokens for fun and profits check out my bot that I built on BSC. This bot can be used for swing trading and swapping already listed coins.


# HOW TO RUN

Okay so to run the bot you just need Visual Studio Code, nodejs installed and that's it:

0. https://nodejs.org/en/download/ - Install nodejs
0. Extract the zip that's present
0. Open the folder "pancakeswap-swap-bot" you downloaded, in Visual Studio Code and click on the "Terminal" tab -> Open new Terminal
2. Set the settings in "Bot settings" at the top of swapbot.js
3. Input enough funds for fees and purchases into your wallet (You need BNB for fees, BUSD to start the default swap)
4. Run with "node swapbot.js" command in the same terminal
5. Stop bot with Ctrl + C.

If an error appears:

1. Your gas price is too small 
1. Your slippage is too small (use 20+ for early token)
3. Some tokens have no liquidity in BUSD for example so you need to snipe tokens with BNB etc.
