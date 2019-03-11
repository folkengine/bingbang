# bingbang
BingBang is a collection of primarily Ethereum development shell scripts that I like to install on any system I am working on. 

## Usage

1. Clone BingBang.
2. Add the repo to your PATH.
3. ...
4. PROFIT!

## Bash Scripts

### cloc-git

Breaks down all the lines of code in a github repository. From [this Stack Overflow post](https://stackoverflow.com/a/29012789).

### drink

Drink gets Eth from the [Ropsten Ethereum Testnet](https://ropsten.etherscan.io/). 

By default it will use [my Testnet wallet](https://ropsten.etherscan.io/address/0x16a94747d128c3ebb779ce32a9ecf125f3f89799) unless you declare the TESTNET_WALLET environment variable. Run the command more than once a day and you will be greylisted for 24 hours. 

### git-crawl

Magnus Stahre's wonderful [git-crawl script](https://github.com/magnusstahre/git-stuff). I don't claim any legal rights to his code. I just like it.

### rndpwd

Generates a random password. Taken from [this article](https://www.howtogeek.com/howto/30184/10-ways-to-generate-a-random-password-from-the-command-line/) by [@LowellHeddings](https://twitter.com/lowellheddings).

### testnet

Fires up a local geth Ropsten(aka testnet) instance.
