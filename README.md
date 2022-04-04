---
description: A QSG for Fuzz Betting and Authoring
---

# Fuzz-Quick-Start-Guide

## Setup Metamask

Fuzz Bets is a DAPP that runs on the Harmony One blockchain, to interact with any DAPP on this blockchain you must setup a metmask wallet. Luckily there is a very thorough guide to do exactly this from [Harmony One themselves](https://docs.harmony.one/home/general/wallets/browser-extensions-wallets/metamask-wallet). The ONE coin is what fuels all transactions on the Harmony blockchain, a very small amount is needed for every transaction to complete. Transaction fees can range from a few dollars on some networks to a few cents on others, luckily Harmony ONE is one of the fastest and cheapest network to transact on and most transaction fees are fractions of a penny.

## Acquire ONE

To acquire the ONE coin I would recommend using the [RAMP network](https://ramp.network). RAMP accepts credit card payments with very low fees and deposit your purchased crypto asset directly into your personal wallet, this is the easiest way I have experience purchasing ONE. Other methods of purchasing ONE would involve using a centralized exchange like Binance, however the problem with centralized echanges is withdrawing the asset from the exchange to your persoanl wallet. Far too often centralized exchanges restrict withdrawls for one reason or another and can trap your fund on their platform.\
\
The amount of money you wish to put towards using Fuzz (or any other DAPP on Harmony) should first be placed into ONE. You can use decentralized echanges on Harmony to swap ONE for the tokens you may need, in this case, FUZZ.

## Acquire FUZZ

To participate in Fuzz Bets you must have some FUZZ tokens to author your own events or to place bets. The way to acquire FUZZ is by visiting the decentralized exchange on [fuzz swap](https://swap.fuzz.fi/swap), then swap some of your ONE for FUZZ. You must be careful and always reserves some ONE to pay for the transactions. If you are betting I would recommend keeping at least 5 ONE for these transactions, and if you're authoring I would recommend keeping at least 10 ONE on the side.

## Placing Bets

To participate in an event go to the fuzz bets [dashboard](https://fuzz.fi/FuzzBet) and browse for events you're interested in entering. You will need to complete two transactions for every event you enter, one to approve the event contract to access some of your FUZZ, and the other to submit the amount of FUZZ you want to place on the event. The payout of events on fuzz is a function of your % share of the winning side's pool of fuzz less the 10% commission givent to the author and burning mechanics.\
\
Example and event has Side A with 20000 FUZZ bet on it, and Side B with 30000 FUZZ bet on it.\
Side A wins and your bet was 2000 FUZZ.\
\
Your payout is caluclated as follows\
\
Your share of winning pool = 2000/20000 = 0.1 or 10%\
The effective pot for the winners = 30000\*0.9 = 27000\
Your winnings = 0.1\*27000 = 2700 FUZZ\
\
Amount returned = original bet + winnings = 4700 FUZZ\
\
Bets take on phases in order to complete

1. Event open - the event has not started yet and bets are open
2. Event closed - the event has begun and bets are closed
3. Winner selection - the event has ended and the author now chooses the winner
4. Dispute window - participants in the event can dispute the results if the event was scored untruthfully
5. Payout - when a consensus is reached on the results of the event the author can initiate payout of the event.

## Become an Author

The most compelling feature of Fuzz Bets is the decentralized authoring of events, meaning anyone can become 'the house' and earn commission from the events they create and promote. To author an event you must first create and author profile that is linked to a keybase account and a twitter account; there is a guide in the [fuzz documentation](https://docs.fuzz.fi/fuzzbet/authors/creating-author-profile) to help you through this part.\
\
Once your author account is approved you must have 10000 FUZZ per event to put up as collateral to secure the event. This is an important part of the platform because it deters authors from scoring games maliciously, because if they do the 10000 FUZZ is lost and the author's reputation score is slashed. The author reputation score indicates the number of successfully paid out events created by the author, this not only builds trust in those who bet on the author's event but it also gives higher commission payouts to the author [shown here](https://docs.fuzz.fi/fuzzbet/authors/reputation-commission-levels).\
\


Enjoy and have fun!
