# mybitcoin
This is an implementation of Justin Moon's Digital Cash project: a short, near replica of bitcoin in python. A few interesting features:

  - divisible UTXO transaction model (there never were any coins!)
  - a p2p network
  - sound monetary policy (21,000,000,000 satoshi cap)
  - mining with difficulty adjustments every 1 min
  - mining rewards include coinbase rewards with halvenings and fees (let's hope these fees are enough to incentivize miners once the rewards are gone!)
  
It took me ~1 year, but I finally finished the tutorial! I'll probably add a few cool additional features as well.
