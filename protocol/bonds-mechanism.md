# Bonds (MBOND)

![The "Pit", where you can interact with the protocol's bonding mechanism](<../.gitbook/assets/img2.png>)

### What are MBOND (Bonds)?

Bonds are unique tokens that can be utilized to help stabilize MEDAL price around peg (1 MEDAL = 1 FTM) by reducing the circulating supply of MEDAL if the TWAP (time-weighted average price) goes below peg.

### When can I buy MBOND (Bonds)?

MBOND can be purchased only during periods of supply contraction and when the TWAP of MEDAL is below 1.

At the beginning of every new epoch during contraction periods, MBONDs are issued in the amount of 3% of MEDAL's circulating supply, with a max debt amount of 35%. This means that if bonds reach 35% of the circulating supply of MEDAL, no more bonds will be issued.

{% hint style="info" %}
Note that during a zen epoch (when an epoch ends with a TWAP between 1.0 - 1.01), **no MBOND will be issued, even though the Boardroom does not print.**
{% endhint %}

{% hint style="danger" %}
MBOND TWAP (time-weighted average price) is based on the MEDAL TWAP from the previous epoch as it ends. In other words, the MEDAL TWAP is real-time but the MBOND TWAP is not.
{% endhint %}

### Where can I buy MBOND (Bonds)?

You can buy MBONDs if any are available through [medaldao.finance](https://medaldao.finance/bonds) in the [Pit](https://medaldao.finance/bonds). Anyone can buy as many MBONDs as they want as long as they have enough MEDAL to pay for them.

There is a limit of available MBONDs per epoch during contraction periods (3% of MEDAL's current  circulating supply), and are sold first-come-first-serve.

### Why should I buy MBOND (Bonds)?

The first and most important reason to buy MBOND is that they help to maintain the peg, but they are not the only measure in place to keep the protocol on track.&#x20;

MBONDs don't have an expiration date, so you can view them as an investment in the long-term health of the protocol to be redeemed for a premium at a later date.

#### Incentives for Holding MBOND

The idea is to reward MBOND buyers for helping the protocol, while also protecting the protocol from being manipulated by big players.

So after you buy MBOND using MEDAL, you have two possible ways to get your MEDAL back:

1. Sell back your MBOND for MEDAL **while the peg is between 1 - 1.1** (1 MEDAL = 1 FTM) with no redemption bonus. This is in place to prevent an instant dump as soon as peg is recovered.
2. Sell back your MBOND for MEDAL **while the peg is above 1.1** (1 MEDAL = 1 FTM) with a bonus redemption rate.

The longer you hold, the more both the protocol and you benefit from MBOND.

{% hint style="success" %}
Example:

1. When MEDAL = 0.8, burn 1 MEDAL to get 1 MBOND (MBOND price = 0.8)
2. When MEDAL = 1.15, redeem 1 MBOND to get 1.105 MEDAL (MBOND price = 1.27)&#x20;
{% endhint %}

So, which one is better?

If I buy MEDAL at 0.8, and hold it until 1.15 and then sell, I'm getting +$0.35 per MEDAL.

But, if I buy MEDAL at 0.8, burn it for MBOND, and redeem it at 1.15, I'm getting 1.105 MEDAL \* 1.15 (MEDAL current price) = 1,271 (+$0.47) per MBOND redeemed.

But, what if getting back to peg is taking too long?

We will adjust our use cases to have different behaviors on contraction and expansion periods to benefit both MEDAL and MBOND holders when needed.

### What is the formula to calculate the redemption bonus for MBOND?

To encourage the redemption of MBOND for MEDAL when MEDAL's TWAP > 1.1 and in order to incentivize users to redeem bonds at a higher price, MBOND redemption is designed to be more profitable with a higher MEDAL TWAP value. The MBOND to MEDAL ratio is 1:R, where R can be calculated using the formula as shown below:

$$
R=1+[(MEDALtwapprice)-1)*coeff)]
$$

$$
coeff = 0.7
$$

### When can I swap MBOND for a premium?

You can only redeem MBONDs for a premium when the previous epoch's TWAP is greater than 1.1.
