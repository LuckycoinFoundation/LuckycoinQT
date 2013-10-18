LuckycoinQT Windows Client v0.8.8
===========

Luckycoin - a fork of Litecoin version with random bonus blocks. Like Litecoin it uses scrypt as a proof of work scheme.

   - 1 min block target
   - Difficulty retargets every 20 min with accelerated diff adjustment in the beginning
   - Initially 88 coins per block, halves every 2 years (1,036,800 blocks)
   - Total around 200 millions coins
   - connection port is 9917, RPC-port 9918

   Random Super-blocks:
    For the 1st 50000 blocks (1st month)
    - 5% chances 188 coins/block
    - 1% chances 588 coins/block
    - 0.01% chances 5888 coins/block (so expect 5 such blocks)

    After 50000 blocks
    - 5% chances 2 times the normal coins (i.e. if normal is 88 coins, you get 176 coins)
    - 1% chances 5 times the normal coins
    - 0.01% chance 58 times the normal coins

  
