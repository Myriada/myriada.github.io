---
layout: default
metatags: cardano, ADA, stake pool, PoS, proof of stake, blockchain 
---

## Myriada at a glance:

Our yearly uptime goal *(SLO) is: 99.9%*

We use a [tax-ratio of 4%][1] - this means no fees unless rewards are issued and 4% of the reward, not your principal.
  
Our ticker is: ``MYRI``  

Our servers are located in Ireland.  
We rotate logs every 14 days. Disks are encrypted.    
We use (D)DoS burst protection on nodes and will blacklist nodes with consistently mismatched hashes- Since IOHK nodes are whitelisted, this will not affect rewards in the test net  

## How to delegate / stake:
Please checkout the [Shelly Incentivized Testnet page](https://staking.cardano.org/en/delegation/) - the latest daedalus supports all steps from the UI!

In short:
1. Download daedalus 
2. Create a rewards wallet (if you don't have one)
3. Move your ada to your rewards wallet
4. Go into the staking menu and find our pool via ticker: *MYRI*
5. Click the icon and hit delegate - you will see short summary of our pool statistics and fees

## Our Roadmap:

We are exited to be an active member of the Cardano community and are currently working on providing the following services, in addition to the stake pools:

- live dashboards for pool uptime, performance and relevant statistics

- optional rss or email alerts for delegators, in case the pool is down or degraded performance (we do not want you to miss out on rewards)

- wash trading detection for our favourite exchanges

[1]:https://input-output-hk.github.io/jormungandr/stake_pool/registering_stake_pool.html#the-primitives
