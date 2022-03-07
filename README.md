---
description: About medaldao.finance
---

# Introduction

Welcome to Medal Finance! If this is your first time here, please take some time to read through this documentation before you begin using the protocol. This documentation is intended to take you through the entire process of how to get started using Medal Finance to earn stable, high yields that are only possible through the power of DeFi, but with the stability and security of exposure to Ftm, the world's largest and most stable crypto asset. Let's dive in!

## Origins

Medal Finance is based upon the work of the brilliant **tomb.finance** project on the Fantom network. At the time, it was hard to believe that nothing similar existed on any other larger networks, so it was a great opportunity to bring an amazingly stable and robust DeFi protocol like **tomb.finance** with a few unique twists to the masses.
\
This project would certainly not be possible without the work of the [tomb.finance](https://tomb.finance) team. Their project being fully open source and developed exceptionally well made it a pleasure to work with, and we would not be here today without their efforts, so we want to give a special thank you to them for that.

{% hint style="info" %}
Medal Finance will launch on March 5, 2022!&#x20;
{% endhint %}

## What's the point?

Ultimately, the purpose of the Medal Finance protocol is to provide the means for its underlying MEDAL asset to maintain a value that is algorithmically pegged to the value to Ftm at a 1 to 1 ratio.

So, what good is that? We will explore this idea further throughout this documentation, but for now without getting _too_ technical, this opens up a world of possibilities for existing, long-time Ftm holders, people already familiar with DeFi, as well as new users just coming into the space.

Ftm transactions are slow and expensive. There are not nearly as many attractive yield earning opportunities in DeFi for people to put their precious Ftm to work for them. MEDAL, through the Medal Finance protocol, can solve many of these problems and more, generating immense value for our users in the process.

As the Medal Finance ecosystem grows over time, the potential future applications are quite literally endless. And, as you proceed through this documentation and learn more about how the Medal Finance protocol works, we will explore some of that potential in more detail.

{% hint style="info" %}
MEDAL is the native token of the Medal Finance protocol. The built-in stability mechanisms within the protocol aim to maintain MEDAL's peg of 1 MEDAL = 1 FTM in the long run.
{% endhint %}

## What are the Medal Finance protocol tokens?&#x20;

Medal Finance’s multi-token protocol currently consists of the following four tokens, and each plays a critical role in how the protocol works to maintain peg:

1. **MEDAL Tokens ($MEDAL)** - The MEDAL token is designed for use as a medium of exchange, and is intended to have many other use cases as the Medal Finance ecosystem grows. MEDAL is algorithmically pegged to FTM at a ratio of 1 MEDAL to 1 FTM.
2. **MEDAL Shares ($MSHARE)** - MSHARE can be staked in the [Boardroom](protocol/boardroom.md) to earn a portion of minted MEDAL as rewards to those MSHARE holders for investing in the health and stability of the protocol.
3. ****[**MEDAL Bonds ($MBOND)**](protocol/bonds-mechanism.md) - MBOND’s main job is to help incentivize and reward users for helping to regain peg during times of supply contraction below peg.

## How does it work?

The Medal Finance protocol works through a synergistic design of unique tokens and mechanisms that create an automatic, self-reinforcing system to help maintain the peg (1 MEDAL = 1 FTM). Each of these tokens and mechanisms will be explained in further detail within this documentation, but for now let's have a look at a brief overview of how it all works:

* When **MEDAL price is over the peg**, new MEDAL are minted by the protocol to inflate the supply in an attempt to drive the price down towards the peg. These new MEDAL are allocated to MSHARE holders in the Boardroom, as a reward for their investment and trust in the protocol. This in turn increases the demand for and the value of MSHARE.
* When **MEDAL price is at the peg**, no new MEDAL will be minted, keeping the supply fixed during this time. Since there will be no new supply coming in, the peg will be maintained indefinitely at this point unless there is a shift in demand. More buying pressure during this time will push the price back up above the MEDAL minting threshold. Conversely, more selling pressure will push the price below the peg.
* When **MEDAL price drops below the peg**, the protocol will begin to mint MBONDs (up to a maximum debt limit). Experienced investors will have the ability to exchange their MEDAL for these MBOND, which they can then redeem for MEDAL at a premium above peg in the future. This removes MEDAL from the total supply, applying upward pressure on the price towards the peg. Besides this, investors who believe in the protocol's ability to maintain peg can just buy MEDAL to essentially purchase FTM at a discount to the market. Both of these incentives are intended to create upward pressure on MEDAL's price when under the peg so that the peg can be regained over time.

{% hint style="info" %}
There are so many different ways you can utilize the mechanisms of the Medal Finance protocol to earn yield. Pick a strategy that is right for you, based upon your own knowledge and experience. Even the most simple and basic of strategies can earn great returns, but feel free to experiment with more complex strategies as you learn how the protocol works!
{% endhint %}

## What exactly is the peg?

MEDAL is a token that is intended to track the price of FTM algorithmically. The ratio for this peg is set at 1 MEDAL to 1 FTM. MEDAL **actively tracks this peg via an algorithm**, but that **does not mean** it will be valued at 1 MEDAL to 1 FTM at all times as **it is not collateralized**. **MEDAL is not to be confused for a crypto or fiat-backed stablecoin.**&#x20;

The entire design of the Medal Finance protocol is intended to try and maintain this peg as closely as possible, but as it is an algorithmic peg, this will never be a completely stable process. In fact, some of the unique profit-generating opportunities offered by the protocol actually only exist because of these price fluctuations.

To put it simply, there will **almost certainly be times when the price of MEDAL is below peg**. This is a natural part of the process, and opens up opportunities for active investors/traders to "buy the dip" and help support the protocol by regaining peg, while also profiting from the discounted price.

![A visualization of MEDAL price in relation to peg]

When the protocol is healthy and stable, the price of MEDAL will likely look similar to above, with price fluctuating above and below peg as the mechanisms of the protocol work to influence supply and demand and maintain an average price around the peg.

Keep this in mind when developing your strategies and when taking a more active role in the protocol.
