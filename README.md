# Monte_Carlo_and_Central_Limit_Theorem

## Motivations
- use of **Monte Carlo** methods
- application to the **Central Limit Theorem**
- comparison with analytical derivation

## Task
*Here's the problem:*
> How many packs of football stickers must you buy to fill a world cup album 90% of the time?
> Assume 5 stickers per pack randomly shuffled, 300 stickers to collect in total, no swapping allowed!

## Structure
Let T be our random variable: number of packs needed to collect the 300 stickers
- We do not know its distribution.
- We will approximate it with MC-sampling
- We will derive its mean and std analytically 

Hence the plan is:
- 1- warm up: expected packs to get p=90% of the stickers
- 2- coupon collector: analytical derivation of mean and std
- 3- Monte Carlo method: approximate the distribution