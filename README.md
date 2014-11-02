# @automaticstartup

What is this?

[@automaticstartup](http://twitter.com/automaticstartup) is one of the most common styles of twitter bot: A Markov text generator. [@automaticstartup](http://twitter.com/automaticstartup) analyzes startup names that were pulled from crunchbase.com and then constructs tweets that are scalable, enterprise-ready and inspirational.

This bot is based upon [Drake-o-matic](https://twitter.com/drakeomatic) which uses [markov-text](https://github.com/codebox/markov-text) by [Code Box](http://http://codebox.org.uk) and can learn to construct sentences after studying any body of text.

Requirements:
 * [Twitter for Python](https://pypi.python.org/pypi/twitter)

How To Use:
 * Clone this repo and edit the settings in `keys.py.example`.
 * Assemble a corpus of text and save it in the automaticstartup directory as a plaintext file.
 * Tell the bot to analyze your corpus of data using the following command: `python automaticstartup.py parse <name> <depth> <file>`
 * Setup cron jobs to tweet at regular intervals using the following command: `python automaticstartup.py gen <name> <count>`

Todo:
 * Incorporate startup descriptions and/or pitches into the source database for better viral growth wordage.

Thanks:
 * To [Anthony Prestia](https://github.com/prestia).
 * To [Rob Dawson](https://github.com/codebox).