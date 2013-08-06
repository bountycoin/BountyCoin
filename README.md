[ANN][BOC]BountyCoin - PoW+PoS|CPU&GPU Friendly|Slow start|Lots of Bounties


## Features

    - Proof of work + Proof of stake
      with 2.5% POS interest
      
    - Modified Scrypt
      carefully selected N to be both CPU & GPU friendly
      
    - Transacation Comment
      like CosmosCoin and FlorinCoin
      
    - 0.0001 transaction fee
      a small fee to pay
      miners will still have incomes after all coin has been mined
      
    - 60 seconds block time
      minimize orphans
      
    - Trade confirm: 3, Mine confirm: 30
      fast transcation
      
    - 5 coins per block
      Day generation: 7200 coins or 1440 blocks, stable reward after 5 days of launch
      
    - Total number of coins 1500000000 (1.5 billion)
      enough to mine over 570 years
    
    - Diff re-targets every block
      no more afraid of coin-hoppers
      
    - Slow start
      Block 1-1440 = 1 coin
      Block 1441-2880 = 2 coins
      Block 2881-4320 = 3 coins
      Block 4321-5760 = 4 coins
      Block from 5761 = 5 coins
    
    - port: Connection: 8512 and RPC Port:18512 
      start mining now!!


## Website:

http://bountycoin.oicp.net


## Download:

Windows Binaries:
https://bountycoin.codeplex.com/releases

Source Code:
https://github.com/bountycoin/BountyCoin


## Getting Started:

1. Start up BountyCoin-qt, wait for it to load, then exit.
2. Put BountyCoin.conf (see sample file below) in your C:/Users/(computerusername)/Appdata/Roaming/BountyCoin
3. Restart BountyCoin-qt, and you should connect and sync.
4. For solo mining, launch CPU miner or GPU miner
5. Solo example: cgminer-mod.exe --scrypt --thread-concurrency 1000 -g 1 -o localhost:18512 -O (yourusername):(password)


## Sample BountyCoin.conf:

    listen=1
    daemon=1
    server=1
    rpcuser=(yourusername)
    rpcpassword=(password)
    rpcport=18512
    rpcconnect=127.0.0.1
    addnode=bountycoin.oicp.net
