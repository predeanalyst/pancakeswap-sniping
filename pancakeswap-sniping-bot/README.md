# TUTORIAL

Hey,

If you want to snipe and swap tokens for fun and profits check out my bot that I built on BSC. It can snipe newly added tokens and swap tokens using Pancakeswap (The one and only) .


# HOW TO RUN

Okay so to run the bot you just need Visual Studio Code, nodejs installed and that's it:

0. https://nodejs.org/en/download/ - Install nodejs
0. Extract the zip that's present
0. Open the folder "pancakeswap-sniping-bot" you downloaded, in Visual Studio Code and click on the "Terminal" tab -> Open new Terminal
0. Set the settings in "Bot settings" at the top of trading.js
0. Input enough funds for fees and purchases into your wallet (You need BNB for fees, BUSD to start the default swap)
0. Run with "node trading.js" command in the same terminal
0. Stop bot with Ctrl + C.

If an error appears:

0. Your gas price is too small
0. Your slippage is too small (use 20+ for early token)
0. Some tokens have no liquidity in BUSD for example so you need to snipe tokens with BNB etc.
