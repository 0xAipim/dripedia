---
label: Faucet
order: -2
icon: verified
description: DRIP Faucet is a low-risk high-reward contract that operates similarly to a certificate of deposit investment. Learn about how it works, including the referral system, and the whale tax.
---

# Faucet
A low-risk high-reward contract that operates similarly to a certificate of deposit investment.

---
### How does it work?

Players can participate in the Faucet by depositing DRIP tokens into it. Deposited DRIP tokens are permanently sent to the Faucet tax pool and cannot by redeemed by the player. The Faucet yields 1% daily rewards (in DRIP) of total deposits, with a max payout of 365% of total deposit amount or 100K DRIP tokens (whichever is smaller).

The 1% daily rewards come from the Faucet tax pool, which is funded by DRIP Faucet deposits and DRIP token transaction taxes. If there’s ever a situation where there aren't not enough DRIP tokens in the Faucet tax pool to pay out Faucet rewards, new DRIP tokens will be minted to ensure rewards are paid out. Given the game theory behind the project, the probability that new DRIP tokens will be minted is extremely low.

---
### Actions

**Deposit:**
Deposits DRIP tokens from your wallet into the Faucet contract. There’s a minimum deposit amount of 1 DRIP. Also, there's a 10% tax for depositing DRIP into the Faucet.

**Hydrate:**
Redeposits your available Faucet rewards back into the Faucet. There’s a 5% tax for hydrating DRIP Faucet rewards. Hydrating allows players to increase their daily earnings, by increasing their total deposits into the Faucet. Frequent hydrating generates exponential daily rewards.

**Claim:**
Withdraws your available DRIP Faucet rewards into your wallet. There is a 10% tax for claiming DRIP Faucet rewards.

**Airdrops:**
Airdrops DRIP tokens from your wallet directly to another player’s Faucet deposits. There is a 10% tax on sending DRIP Faucet airdrops.
Sending airdrops can help ensure that your account has a positive net deposit status, as well as being a great tool for giving back to your team and attract new members.


| Transaction | Tax |
|:---:|:---:|
| Faucet deposit | 10% |
| Faucet hydrate (recompound) | 5% |
| Faucet withdraw | 10% |
| Sending airdrop | 10% |

---

### Teams and Referrals

Before a player can deposit into the Faucet, they will have to join another person’s team by inputting the person’s wallet address into the Buddy Referral System. This buddy (team leader) must already be active in the Faucet (have a Faucet deposit) and have 14 or less people above them (there's a limit of 15 levels). It is not possible to change teams.

Player’s aren’t required to develop teams under them, and will still earn Faucet rewards regardless of their team size.

With the goal of promoting the growth of the platform, DRIP Network has implemented a referral system. This system seeks to fairly reward players for their work in helping expand the reach of the DRIP Network.

The amount of the referral reward is 10% of the deposited amount (after deposit taxes), or 5% of the hydrated amount (after hydrate taxes). Received referral rewards are send to one's Faucet deposits.

Requirements to receive referral rewards from your downlines:
-   Hold the required BR34P token amount in your wallet (see table bellow)
-   Have a positive net deposit status: (Faucet deposits + Faucet hydrations + Airdrops sent) > (Faucet withdraws)


| Downlines accessible | BR34P in Wallet Requirement |
|:---:|:---:|
| 1 | 2 |
| 2 | 3 |
| 3 | 5 |
| 4 | 8 |
| 5 | 13 |
| 6 | 21 |
| 7 | 34 |
| 8 | 55 |
| 9 | 89 |
| 10 | 144 |
| 11 | 233 |
| 12 | 377 |
| 13 | 610 |
| 14 | 987 |
| 15 | 1597 |


If these conditions aren’t met, the next person upline will have their eligibility checked, successively until an eligible player can be selected to receive the rewards.

If the selected player’s team has less than 5 direct members, the selected player will receive 100% of the reward.
If the selected player's team has more than 5 direct members, the selected player will receive 75% of the reward, and the person who is depositing/hydrating will receive 25% of the reward.

| Selected player's team size | Selected player's reward | Depositing player's reward |
|:---:|:---:|:---:|
| < 5 | 100% | 0% |
| ≥ 5 | 75% | 25% |

!!!primary
Referral reward tokens received by the [dev wallet](https://bscscan.com/address/0xe8e9720e39e13854657c165cf4eb10b2dfe33570) will be used as a promotional tool to help the growth of the platform. For example: team competition rewards, being burned, etc. These tokens won't be dumped on the market.
!!!

To better explain how the referral system works, let's take a look at an example illustrated by the image bellow:

![Illustration of the following referral tree: Dev wallet (5 direct team members, 1600 BR34P) → Alicia (2 direct team members, 10 BR34P) → Bruno (1 direct team members, 0 BR34P) → Chang (3 direct team members, 2 BR34P) → Diana (0 direct team members, 0 BR34P).](/static/banner_faucet_referral.jpg)

Whenever Diana (rightmost of image) deposits or hydrates, a wallet on her upline will receive a reward (a percentage of the amount deposited or hydrated).

The 1º time that Diana makes a deposit, the reward will go to the person **1 level** above her (if the account is eligible), in this case Chang. Chang will receive the rewards because he holds enough BR34P tokens in his wallet to reach 1 downline, and has a positive net deposit status.

The 2º time that Diana deposits or hydrates, the reward will go to the person **2 levels** above her, in this case Bruno. Bruno is ineligible to receive this reward because he doesn't have enough BR34P tokens in his wallet to reach 2 downlines. Since Bruno is ineligible to receive the reward, the reward will go to the next person upline, Alicia, who is **3 levels** above Diana. Alicia will receive the reward because she holds enough BR34P tokens in her wallet to reach 3 downlines and has a positive net deposit status.

The 3º time that Diana deposits or hydrates, the reward will go to the person **4 levels** above her, the dev wallet. The dev wallet is eligible and will receive the rewards.

Since there's no account above the dev wallet, the reward level will reset to level 1. So next time Diana deposits or hydrates, the cycle restarts with Chang receiving the reward if he's eligible.

---

### Whale Tax

In order to maintain the sustainability of the project, an additional tax on Faucet withdraws is applied on players according to the sum of their **total withdraws + available Faucet rewards** in relation to the total supply of DRIP tokens.

| % of total DRIP supply | Tax |
|:---:|:---:|
| < 0.99% | 0% |
| ≥ 1% | 5% |
| ≥ 2% | 10% |
| ≥ 3% | 15% |
| ≥ 4% | 20% |
| ≥ 5% | 25% |
| ≥ 6% | 30% |
| ≥ 7% | 35% |
| ≥ 8% | 40% |
| ≥ 9% | 45% |
| ≥ 10% | 50% |
