# DISCONTINUED
This program is no longer fully functioning and is no longer being updated. If you would like to improve upon it and update it, feel free to clone this repository and add your own contributions. Thank you!

# LichessBot
Bot created for lichess.com using open source stockfish chess engine

Using Javascript you can utilise the open source chess engine stockfish https://github.com/nmrugg/stockfish.js alongside websockets to have a fully automated bot that does not even need to be viewable on your screen (no mouse clicks etc) in around 40 lines of code.

# How to Use

1. Get tampermonkey extension
2. Create userscript and paste the chosen version lichess.js into it
3. Go to lichess.org
4. Play any game
5. Enjoy!

# Different Versions

There are 3 scripts, each which are varying levels of skill.

lichessLegit is stockfish level 6 and moves at a good human level pace

lichessFast is stockfish level 6 and moves at very fast speeds (still doable for a human)

lichessBot is stockfish level 7 and moves almost instantly (very obviously a bot)

There is a feature which allows you to have the bot automatically find a new game (so it can continue to play without you needing to touch anything after a match ends) This is disabled by default. If you wish to enable it, search for the line //findNewOpponent(); and remove the //

# Disclaimer
Using this script against real players is cheating and may get you banned
