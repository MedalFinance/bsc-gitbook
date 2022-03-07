# Tokens

### MEDAL - medaldao.finance Token

![medaldao.finance (MEDAL)](<../.gitbook/assets/medal_card.png>)

Contract: [0xcE180dBFBe6BB6E6b6724fD289A7f8840480E7eD](https://ftmscan.com/address/0xcE180dBFBe6BB6E6b6724fD289A7f8840480E7eD)

The MEDAL token is designed to be used as a medium of exchange. The built-in stability mechanisms within the protocol aim to maintain MEDAL's peg of 1 MEDAL = 1 FTM in the long run.&#x20;

{% hint style="warning" %}
Note that MEDAL **actively pegs via an algorithm**, but that **does not mean** it will be valued at 10 MEDAL to 1 FTM at all times as **it is not collateralized**. **MEDAL is not to be confused for a crypto or fiat-backed stablecoin.**
{% endhint %}

### MSHARES - MEDAL Shares

![SHARE](<../.gitbook/assets/mshare_card.png>)

MEDAL Shares (MSHARE) are one of the ways to measure the value of the Medal Money Protocol and shareholder trust in its ability to consistently maintain MEDAL close to peg. During epoch expansions the protocol mints MEDAL and distributes it proportionally to all MSHARE holders who have staked their tokens in the [**Boardroom**](boardroom.md).

MSHARE has a **maximum total supply of 65,001** tokens distributed

{% hint style="success" %}
The Medal team will use the treasury funds in any way that they feel is best for the long-term success of the protocol.&#x20;
{% endhint %}

### [MBOND - MEDAL Bonds](bonds-mechanism.md)

![MBOND](<../.gitbook/assets/mbond_card.png>)

The main purpose of MEDAL Bonds (MBOND) is to help incentivize fluctuations in the MEDAL supply during epoch contraction periods. When the TWAP (time-weighted average price) of MEDAL falls below 1 to 1 FTM, MBONDs are issued and can be bought with MEDAL at the current price. Exchanging MEDAL for MBOND burns MEDAL tokens, taking them out of circulation (deflation) and helps to get the price back up to peg. These MBOND can be redeemed for MEDAL when the price is above peg in the future, plus a premium based on how high above peg we currently are. This conversely creates inflation and subsequent sell pressure for MEDAL when it is above peg, helping to push it back toward 1 MEDAL to 1 FTM ratio.

{% hint style="info" %}
Unlike early algorithmic protocols, MBONDs do not have expiration dates.
{% endhint %}

All MBOND holders will be able to redeem their MBOND for MEDAL tokens as long as the treasury has a positive MEDAL balance, which typically happens when the protocol is in epoch expansion periods.
