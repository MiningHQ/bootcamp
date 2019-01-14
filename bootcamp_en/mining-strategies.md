# Mining Strategies

MiningHQ is based on the concept of mining 'strategies'. A strategy controls how and what you are mining at any given time.
Some strategies run forever while others are timed and change based on some external factor. Most strategies are available
per rig as well as on the account level.

**Rig vs account-wide strategy**

Rig strategies are set for just a specific rig while account strategies apply
to *all* the rigs on your account. Account strategies make it really simple to control
all your mining power with a few clicks. Account strategies also apply to any disconnected rig
that reconnects or any new rig that registers.

When you change your account strategy to 'separate rigs', the rigs will continue using the strategy
currently assigned to it until you wish to change it.


## Single coin
<small class="text-success">available</small>

The single coin strategy mines a single coin using a single wallet and pool until it is changed

## Most coins
<small class="text-danger">in development</small>

This strategy will switch you to mine one of the coins supported that will gain you the most
coins. We'll only switch once every 100 minutes to ensure you gain at least some coins.

Note: We can only mine coins that you have a wallet address for. Ensure you have set up wallets for
all the coins you wish to mine


## Most profitable
<small class="text-danger">in development</small>

The most profitable strategy will switch you to mine one of the supported listed coins that will gain you the most
in Bitcoin. We'll only switch once every 100 minutes to ensure you gain at least some coins.

Note: We can only mine coins that you have a wallet address for. Ensure you have set up wallets for
all the coins you wish to mine


## Split mining
<small class="text-danger">in development</small>

The split mining strategy is a special kind of strategy. It splits your rig's resources into smaller units so that you
may assign parts of your rig to different strategies.

You can set your CPU to mine currency A and our GPUs to mine currency B.

## Custom coin
<small class="text-danger">in development</small>

We allow you to define your own custom coin and pool if we don't support it yet. If you'd rather
have us support your favourite coin, please let us know on <a target="_blank" class="text-link text-primary" href="/connect">any of our support channels <i class="fa fa-fw fa-external-link"></i></a>
